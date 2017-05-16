This is a cleaned-up version of the LynxMotion 
[BotBoarduino_CH3R_PS2](https://github.com/Lynxmotion/3DOF-4DOF-Hex/tree/master/BotBoarduino/3%20DoF%20Ready/BotBoarduino_CH3R_PS2)
code:

<ul>
<li> Renamed Hex_globals.h to Hex_Globals.h, for case-sensitive OSs like Linux and Mac OS X.
<p><li> Fixed compiler warnings (in progress).
<p><li> Create abstract Controller class to support controllers other than PS2 (future work).
</ul>

In order to compile this code in Arduino, you will need to install this library:
http://www.billporter.info/2010/06/05/playstation-2-controller-arduino-library-v1-0/

Please make sure you add the relevant files in your /Arduino/libraries/ folder.

You can find a copy of this library on the Lynxmotion GitHub here:
https://github.com/Lynxmotion/Arduino-PS2X
