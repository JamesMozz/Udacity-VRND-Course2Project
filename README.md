# VR Developer Nanodegree Course 2 Project: 
Modern Apartment

For this project we were asked to create an apartment using a scene which included an empty room and an assets folder 
containing prefab furniture. We also had to animate a globe to start/stop spin on click. 

![Picture of modern apartment scene] ( https://docs.google.com/uc?id=0B6uYPHCWTV0xYlgxX09NU3R4VUE)

# Project Criteria

## Models

### Overall Layout

The overall placement of 3D objects in the scene is reasonable and is visually pleasing

### Sufficient Detail

The apartment contains at least 15 models arranged in an interesting way

### Static Models

All models are marked as Static (except the globe)

## Google VR

### VR Functionality

When you run the scene, the Cardboard stereoscopic view appears and functions correctly

## Deployment

### Player Settings.

Player Settings (Android):
Company Name
-e.g. Your Name (E.g. MattSonic)

Product Name, you must change this to something other than "MattSonic"
-e.g. “Course 2 Project”

Default Orientation: Landscape Left

Uncheck “Use 32-bit Display Buffer”

Set Bundle Identifier
-e.g. com.YourName.Course2Project

## Quality Settings

Delete all of the quality settings but one
-Click the trash can

Rename the quality setting to “Mobile”

Set the pixel light count to 0

Texture Quality: Full Res

Anti Aliasing: 2x Multi Sampling

Uncheck:
- NO Soft Particles
- NO Realtime rendering probes
- NO Billboards face camera position
- Shadows: Disable Shadows
- Blend Weights: 1 bone

## Screenshot of App Running on Phone

Take a screenshot of your phone screen with the app they built running. Ideally, it shows a nice wide view of the apartment.

## Lighting

### Lights

There are several spotlights and/or area lights

### Static Lights

All lights are marked as Static

### Baked

All lights are baked and none are realtime (except for one directional light if they choose)

### Lightmap Settings

Turn off Precomputed Realtime GI

Set Directional Mode to Non-Directional

Turn off Auto baking

Test different bakes with a Baked Resolution of between 2-5, then do a test bake at 40, then do a final bake with a resolution of 80

You’ll probably want to activate “Soft Shadows” on each light (so the baked lighting produces nice shadows)

If you notice lighting artifacts, then switch to uncompressed lightmap. If your app does not perform well any more, you may revert to compressed lightmaps, but you must include in your submission notes what you tried and what happened.

## Globe

### Globe Exists

A globe should exist and be readily visible in the scene

### Globe Spins

When you press the Cardboard button, the globe should spin until you press the button again

### Globe is Textured

The globe should have a texture map of a planet. We provide a texture map of the Earth, but feel free to use your own texture.
