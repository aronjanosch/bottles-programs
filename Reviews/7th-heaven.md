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
Grade: Bronze  
Additional notes: UI is just a black screen if DXVK is enabled. Hovering over UI elements temporarily draws them, but ultimately goes black again.

**Does it require some tweaking in order to work properly? (Out of normal software configuration)**  
Grade: Bronze  
Additional notes: 

* FF7 is not automatically installed - Either the 1998 CDs or via Steam ( included by default )
* When using Steam edition of FF7, an ISO at `<bottles prefix>/Program Files (x86)/7th Heaven/Resources/FF7DISC.ISO` must be manually mounted.
* With Flatpak, need to ensure that the mounted dir is accessible with FlatSeal.

**Did it crash during tests execution?**  
Grade: Bronze
Additional notes: Fails to launch with mods, if caffe is used. Workaround usually used in app for Windows ( "Code 5 Fix" in settings ) is non-functional. Stick to Vaniglia

**Is it usable?**  
Grade: Bronze  
Additional notes: as long as DXVK is disabled & Vaniglia runtime is used.

**Final grade? (the lower evaluation from previous questions)**  
Grade: Bronze  
Additional notes: n/a

**Additional notes**
Using the 1998 CD is untested.

Install is not silent.

FF7 is not automatically installed - Either the 1998 CDs or via Steam

Recommended settings to tweak once installed:
* Game Driver ( will need to launch vanilla for the first time before you can set these ):
* * set `Graphics API` to `DirectX 12`( Game appears to always crash without this )
* * Set `Music Option` to `VGMStream` ( No music without this )
* Game Launcher:
* * `Do not auto mount Disk` (This is non-functional)
* * Set `Auto-Mount Game Disk` to `off`
* * Set `Auto-Dismount Game Disk` to `off`
