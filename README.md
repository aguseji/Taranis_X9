# Taranis X9 GPS last positions Telemetry Screen

Telemetry Widget script for Taranis x9 v0.1

Copyright (C) by mosch   
License GPLv2: http://www.gnu.org/licenses/gpl-2.0.html       

Desription:

stores GPS coordinates every second into /SCRIPTS/TELEMETRY/GPSpositions.txt and 
displays the last 4 GPS positions and GPS sattelite count on the telemetry screen.
In case that telemetry is not available anymore (crash, power loss etc.) the screen 
won't be updated but still shows the last 4 postions. If 50 postions are stored, the log 
will be reset and starts at 0.


Install:
1. copy the pre-compiled file "GPS.luac" to /SCRIPTS/TELEMETRY/
2. Rename GPS.luac to GPSc.lua 
3. create a empty text file /SCRIPTS/TELEMETRY/GPSpositions.txt 
4. Add a new telemetry screen and select GPSc.lua



NOTE: not tested  outside yet !

![Alt text](https://github.com/moschotto/Taranis_X9/blob/master/screenX9.PNG)
