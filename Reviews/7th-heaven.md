# 7th Heaven
Review for the 7th Heaven installer.

Maintainer: @sjenkins7

**Is the program properly opened?**  
Grade: Platinum  
Additional notes: n/a

**Is it showing alerts or other warnings?**  
Grade: Platinum  
Additional notes: n/a

**Does it show graphical glitches?**  
Grade:   
Additional notes: As long as DXVK is off - none

**Does it require some tweaking in order to work properly? (Out of normal software configuration)**  
Grade:   
Additional notes:

DXVK must be disabled. Must be toggled on and back off

**Did it crash during tests execution?**  
Grade: 
Additional notes:

Fails to launch with mods, if caffe is used. Workaround usually used in app for Windows ( "Code 5 Fix" in settings ) is non-functional. Stick to Vaniglia.

Game always crashes first time - Game needs to be launched for the first time, before being able to change Graphics API to something compatible

**Is it usable?**  
Grade:   
Additional notes: as long as DXVK is disabled & Vaniglia runtime is used.

**Final grade? (the lower evaluation from previous questions)**  
Grade:   
Additional notes: n/a

**Additional notes**
Using the 1998 CD is untested.

DXVK must be disabled for 7th heaven to function.

`start` method may fail - Steam doesn't register it until the first time it is launched

Install is not silent, as Steam doesn't provide a way to install a game silently.

Recommended settings to tweak once installed:

Game Driver ( will need to launch vanilla for the first time before you can set these ):

* set `Graphics API` to `DirectX 12`( Game appears to always crash without this )
* Set `Music Option` to `VGMStream` ( No music without this )
