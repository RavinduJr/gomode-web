modules -> core
modules -> shared

shared -> Nothing
core -> shared

core x-> modules
shared x-> modules

if many modules need a function it supposed to go core or shared
but core and shared never supposed to depend on modules