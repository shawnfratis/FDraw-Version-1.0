# FDraw-Version-1.0
Drawing program written in Icon

FDraw v.1.0 overview and basic instructions to get you started.

FDraw is a very simple drawing, perspective 3D and "helper" program.

All the commands are done with the keyboard. No mouse events whatsoever.

If you are familiar with command-line based programs you shouldn't have too much trouble finding your way around (I hope not anyway).

If you look at the basic instructions on the screen, or use the more detailed ones by pressing "=", you will see that there are a lot 
of functions that are initiated by individual keys. Otherwise, by pressing "\" you can input specific commands and parameters.

For instance, press "\", and then type "cube01", hit enter, type 100, hit enter, type 100 again, hit enter, type 50, and hit enter.
This will give you a cube placed at x = 100, y = 100 and z = 50. Pretty much all of the basic shapes in the program can be entered this way.

For basic drawing, press "\" and type "draw", hit enter, then (as with the cube) enter parameters -100,100,300,250 (hitting enter with each 
number). This will give you a diagonal line. With all lines, the first two numbers represent x and y of the beginning of the line, and the
last two numbers represent x and y of the end of the line.

At this point in development there is no save function. Instead, if you press "z", an image file will be written with everything on the screen. 
You can retrieve this image back into the program by pressing ",". Afterwords you can continue drawing over the image and save it by pressing
"z" again. NOTE: VERY IMPORTANT - Pressing "z" saves the file to "fg01.png". Every time you press "z" you overwrite this file. If you intend to 
save it you must rename it before pressing "z" again.

These are the most basic elements of FDraw. This is a work in progress. You are always welcome to access the code and hack it to your hearts 
desire if you see things that you think can be improved. Otherwise, I intend to add more complex features in the future. Stay tuned!

I wrote FDraw as a "helper" program to assist me while working as a CAD detailer in the steel fabrication business, so it contains a lot of
tables, charts and functions that can be of assistance to fabricators and engineers. I left these in for your use. 

Thank you for reading this.

SHAWN L. FRATIS
TUCSON, AZ. 2015
 


