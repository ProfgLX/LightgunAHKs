
This AHK is made specifically for use with Lethal Enforcers running in Snes9x Lightgun edition (Windows only).

The rom must be named "Lethal Enforcers (USA).sfc" or else you will need to change it in the AHK.


It solves 3 problems:

	- Mouse right is mapped as "Start" and is hardcoded in the emulator. Now Mouse right will reload. This means you can also use the pump handle to reload.
		- Start will now be mapped to "1", like the mame standard for player 1 start. You can change it in the AHK by changing the line $1::Rbutton
	
	- The game didn't reload when shooting at the bottom of the screen. This AHK fixes that. You can shoot anywhere that is outside the game screen.
	
	- The emulator and the game didn't like adding a bezel very much for 16:9 users. It's fixed with my code.

I'm pretty sure it will not work for multimonitor people. I'm sorry.

It will however work in any resolution that is a multiple of 16:9.



You CANNOT change the bindings of controller 1 in Snes9x for this to work! I need to use the "v" key to shoot offscreen!

*******You will need to run the AHK as administrator to allow the function "Block input" to work.********

Included is my conf file for snes9x so you will have the exact settings needed in Snes9x for this to work.




This has not been beta tested. If you encounter any problems, I might be able to fix them, but no guarantees.

This is the result of around 10 hours of work, personnal testing included. I hope you will enjoy it.

									- Prof_gLX