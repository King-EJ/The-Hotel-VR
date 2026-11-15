# The-Hotel-VR
VR mod for The Hotel


<img width="1086" height="1448" alt="VR Hotel_ Blood and Shadows" src="https://github.com/user-attachments/assets/aa3a0bf5-d41e-453e-83af-9966eb0cd273" />



THE HOTEL VR  -  VR mod (Unity 2019.4, Mono x64, HDRP, BepInEx 5)
=================================================================
Version 0.1.9 (test build)

INSTALL
 unzip to game folder, only tested with virtual desktop XR

VIEWS (right stick click switches)
  THIRD PERSON (default): you stand where the game's camera is - its fixed camera angles, in 3D. When the camera
    angle changes your view turns to the new camera.
  FIRST PERSON: you are the player (the head is hidden). Both ARMS follow your controllers, the weapon is in the
    right hand. The left stick walks where you look, the right stick turns you (snap 30 degrees).
  Menus / puzzles / videos: the game's picture on a screen in front of you. In play the HUD floats in front of you.

CONTROLS (the controllers are an Xbox controller for the game - the game's layout in brackets)
-
  Left stick ............ move  
  
  **Right stick click ... FIRST / THIRD PERSON**
  
  A ..................... A (shoot / interact)
  
  B ................... B (cancel
  
  X ..................... X (run, hold) 
  
  Y ................... Y (map)
  
  Right trigger ......... RT  (also A) 
  
  Left trigger ........ also X (run)
  
  Right grip ............ RB (AIM, hold)
  
  Left grip (tap) ..... LB
  
  Left stick click ...... START / MENU (inventory; open and close)
  
  Right stick ........... third person: the game's right stick
  
                          **Right stick first person: left / right = turn, UP = laser on / off**
                          
                          **Right stick DOWN (both views) = the game's FLASHLIGHT on / off**
                          
  Left grip + Y ......... Start (inventory; open and close) 
  
  Left grip + B ....... Select
  
  Left grip + left stick  D-pad
  
  **Left grip + A ......... DOTS OVER ITEMS on / off**
  
  Left grip + X ......... **LIVE HAND ADJUSTMENT** (first person): the hands stay put in the air - move your controllers
                          to where you want to hold them, left grip + X again keeps it. Each weapon keeps its own.
                          
  Both stick clicks ..... re-centre the view (hold 1.2 s = VR settings menu)
  
  
6DOF (first person)
  * Shots go where your right controller points (they leave from the controller); the red laser shows it.
  * What you use / pick up is where your right controller points (within 2.5 m).
  * Hand positions per weapon: [Weapons] in the config, or left grip + X in the game.

GRAPHICS/ [Graphics] in the config, or the VR settings menu)

  No room light glare ......... on   (bloom off: no glow / haze around lamps and room lights, no lens dirt)
  
  No light halos .............. off  (also switches off the volumetric fog light shafts - changes the look more)
  
  Flashlight .................. right stick down switches the game's **flashlight on / off** (remembered)

  Laser ....................... right stick up laser on\off
  
  Dots over items ............. Pickups: a dot floats over things you can pick up (Off / Pickups / AllInteractables)
  
  Melee swing ................. first person, knife / **melee weapon: swing the right controller into an enemy**
                                ([Melee] MeleeWeapons = the weapon numbers that are melee - see "In your hands:" in the log)

Issuses
-
 * you have to live adjust any new weapon picked up (Left grip + X ......... **LIVE HAND ADJUSTMENT** use lase on to help)
 * quick small flicker (fixed camera trying to switch)

Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
