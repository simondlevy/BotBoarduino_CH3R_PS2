This is a cleaned-up version of the LynxMotion 
[BotBoarduino_CH3R_PS2](https://github.com/Lynxmotion/3DOF-4DOF-Hex/tree/master/BotBoarduino/3%20DoF%20Ready/BotBoarduino_CH3R_PS2)
code:

<ul>
<li> Renamed Hex_globals.h to Hex_Globals.h, for case-sensitive OSs like Linux and Mac OS X.
<p><li> Fixed compiler warnings (in progress).
<p><li> Create abstract Controller class to support controllers other than PS2 (future work).
</ul>

In order to compile this code in Arduino, you will need to install the library
for the PS2 controller.  We recommend using our 
[cleaned-up version](https://github.com/simondlevy/PS2X_lib)
of the 
library, which eliminates compiler warnings.

