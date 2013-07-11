

This is the first part of the Raywenderlich Tile Based Game where Tiled is used to generate Tile Map for the game.
In this module it is successfully depicted in the Win32 form with some run time errors which i cant fix at this moment.


To add more information i can say that the X,Y co-ordinate system of the Tiled software is Inverted Y axis where any point
that has a value of (10,20) will originally pointed to (10,-20) in Tiled. So to simplify this calculation the y value when
extracted from the TMX file was substracted from the tile height and tile width i.e. 32X50 = 1600-Y value. Thus properly
mapping in side the Win32 co-ordinate.

Another point to be noted is here i have played with the normal resolution of the Cocos2dx-3.2.1 software by making changes 
in the main.cpp file where i had to figure out many possible resolution that can properly show the output.


Opening the TMX file with the Text editor will show the resource paths so it s suggested to check the paths before running
the program are properly located to the resource folder or not. Due to this there could be many Exception Raised while
compiling.


