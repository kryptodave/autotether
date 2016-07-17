auto tether
=============

refactored code from https://github.com/jonhannis/CM-AutoTether
no longer statically linked to 10.1 
tested on 12.1 cyanmodgen nexus 7 2012

should work with all cyanmodgen versions up to 13 or marshmellow

*tested on 2013 12.1 as well, but tether and adb icons hang in systembar, still works tho*

code is still a bit dumb, only handles detection from power off events, so if tether disconnects for whatever reason other than power or plug then it wont tether without 3rd party intervention. (ie autotether crashes etc)

