### Steam VR Template ###

Instruction guide [found in the onedrive](https://onedrive.live.com/redir?resid=6283336A7C9CA810!8154&authkey=!AOKDNvFGYwxzIB0&ithint=file%2cpdf)

Disclaimer: The goal of this template is to put together a noob-proof SteamVR pawn to drop in your scene. However, one size for all solutions will not answer to all specific implementations, but it can gives you a head start. The template will be updated regularly with Unreal forum contributors suggestions. 

My eternal thanks to (but not only) @mitchemmc for input maps and controllers mapping and @PenguinTD for amongst many functions , teleportation method #2 and Ultraman.

Thanks to @mordentral for the grabbing fantastic plugin.

All assets are whether homemade, from the public domain or from Epic demos (you can use them freely in UE4 projects).

I remind everyone that any contribution is welcome. The commercial/fun value of VR projects is definitively not on who can use the Vive, who cannot. It's in the whole experience, the universe you are creating, the feeling, the originality and the user experience.

Have fun!

Mat, at Proteus VR

Latest version 1.9.1 – UE4.11.2: May 27, 2016

Features

* Animated triggers in both controllers
* Map of all buttons/trackpad on controllers
* Toggle on/off debugging squares of controllers and/or base stations
* Toggle on/off debugging meshes of base stations
* 2 different ways to teleport
* Ghost move
* Basic vehicle
* Scalability settings for Vive
* Finger tracking on trackpad
* Trace line with trigger
* Force feedback
* Textures on cubes and sphere to test scalability settings
* Toybox: 4 objects with skeletal sockets: the sword, the gun, the baton, the lightsaber; 1 object with mesh socket: the book; 1 object without sockets: the hat
* Animated "grabbing" mesh right hand (will be refined) -- can be used instead of right controller mesh
* Teleportation with trackpad à la The Lab with cylinder & particles validation
* Go/No go teleportation zones with camera fade out
* Moving platform for testing purpose, by simple actor move (embark by triggering overlap volume or teleportation; disembark by teleportation) and matinee (embark/disembark with controller input)
* Triggerable poles at the 4 chaperone corners
* Addition of a cone at the tip of the right trigger -- can be rotated
* “UltraMan” mode
* Standing/seated experience switch
* Grab function
* Head mesh with mirror
* Selectable controllers skins & opacity
* Select alternate meshes for controllers
* Adjustable "safe" value to teleport on uneven surfaces

Setup
Files can be found [on OneDrive](https://onedrive.live.com/redir?resid=6283336A7C9CA810!6527&authkey=!AJMU7UC1E0IlaGc&ithint=folder%2czip "pre-authed link")

GitHub version at https://github.com/ProteusVR/SteamVR_Template (you need to be logged to Github to open the link) 

To install as a template, just unzip into the appropriate templates directory like C:\Program Files\Unreal Engine[Version]\Templates for launcher version or[ForkLocation]\UE4\Templates for source version. 

Launch a new project, and you'll find it in the blueprint section.

To install as a project file, unzip in your usual projects folder. Then, delete the file SteamVR_x-x/Config/TemplateDefs.ini and you’re ready to go.
