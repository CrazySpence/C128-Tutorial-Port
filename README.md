# C128-Tutorial-Port
Porting as many of the C64 Tutorials to C128 as I can

The C128 side of TRSE was ignored and mostly rightfully so, the platform was ignored in its heyday as well

However I am trying to fix that as it does have some unique properties compared to a C64
Due to the alck of Documentation and Tutorials I am trying to port as many of the C64 tutorials to C128

Some common issues are screen_height is not defined for some reason,
waitforverticalblank() doesnt do anything so when it was used ive replaced it for waitforraster(somenumber)

The ones in this repository should already work as I run them on my machine before committing

--CrazySpence
