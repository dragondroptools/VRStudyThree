# VRStudyThree
A study created for Intro to VR
# Study 3 - Worlds and Stories


## Requirements

These projects are compatible with the following versions of the Unity Editor:

- 2019.4 and later

## Getting started

The full project files are avialable and can be browsed or loaded into Unity. Please see video file for a demo of all interactables and recommended flow.

## Project overview

This study experiments with how spatial sound and animation triggers on interactables can be used to build a narrative. The focus was on building atmosphere rather than telling a linear narrative. 

### Technical Overview

|**Scene**|**Description**|
|---|---|
| 00_UnityStoreAssets |

\_Barking_Dog
Modular kit used to build the hallway
https://assetstore.unity.com/packages/3d/environments/3d-free-modular-kit-85732

\Azerilo
Rug
https://assetstore.unity.com/packages/3d/props/interior/free-rug-pack-118178

\Chair
Armchair
https://assetstore.unity.com/packages/3d/props/furniture/chair-and-armchair-26360

\FurniturePack
Lamp and sidetable
https://assetstore.unity.com/packages/3d/props/furniture/retro-furniture-83306

\Georgian, by Tokyo Liu
Desk and chair set
https://assetstore.unity.com/packages/3d/pbr-georgian-desk-and-chair-90192

\Particle Ribbon by Moonflower Carnivore

\PolyLabs LLC
Radio on the side table
https://assetstore.unity.com/packages/3d/props/electronics/vintage-style-radio-158856

\Rooms
Bookshelves and candles
https://assetstore.unity.com/packages/3d/environments/free-medieval-room-131004


//Other model used:
Open book:
https://www.cgtrader.com/free-3d-models/sports/book/hardcover-book-28e34b7b-9d06-4987-8f23-59138a5cac5e

| 01_CharacterAnims |
Model and animations used were downloaded from Mixamo.com

| 02_MyMaterials |
Colours amended by me in Photoshop.
Materials downloaded from: https://www.sketchuptextureclub.com/textures/materials/wallpaper/damask/damask-wallpaper-texture-seamless-10955
https://3djungle.net/textures/parquet/4232/
| 03_MyScripts |
Fader.cs, LightSwitch.cs, SwitchObject.cs, TimelineController.cs and TriggerZone.cs:
Files as created in class. Variables have been added to public functions within the Unity project.

bookcaseTimeline.playable and TriggerAreaTimeline.playable:
Control the bookcase animation sequence and the trigger area in the hallway respectively.

| 04_MyAudio |
Sound effects used from zapsplat.com

SoundEditing.wav:
This file includes two clang sound effects, with reverb added and made into a looping file in Adobe Audition.

Thursday6April.wav:
A reading of an excerpt from Derek Jarman's Modern Nature. I recorded my voice and cleaned the audio file in Audition before running it through a filter on voicechanger.io  

The Garden(1990) ORIGINAL TRAILER.mp3
Audio file from the trailer of said movie. 

| 06_Scenes\Study 3 |
This is the active scene, examples left for reference.

| 07-10_XR |
These are the XR Toolkit associated files.

### Bug fixes
Animation on character in the hallway now working correctly and with audio file added to footsteps.
