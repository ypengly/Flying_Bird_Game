FLYING BIRD - browser prototype
================================

This is a single-file, self-contained browser game (Three.js + WebGL).
It is NOT a Unity project — there is no separate engine project, scene
files, or asset pipeline behind it, so this zip contains just the one
playable file plus this note.

HOW TO RUN
----------
Double-click flying-bird.html, or drag it into any modern desktop
browser (Chrome, Edge, Firefox, Safari). It needs an internet
connection once, to load the Three.js library from a CDN.

You can also play the hosted version at:
https://claude.ai/artifact/D8GeDyHwh6i33CtMPbfGyV

CONTROLS
--------
W / S      Speed up / slow down
A / D      Turn left / right
Space      Climb
Shift      Dive
E          Gentle nose-down landing assist
V          Toggle first-person / third-person camera

WHAT'S IN THIS BUILD
---------------------
- Procedurally generated terrain with forest, plains, desert, and
  snow biome regions
- Animated water with rolling waves
- Full day/night cycle with a fading starfield
- A bird with layered tail feathers, spreading wing primaries,
  talons, and eyes, driven by momentum/lift/drag flight physics
  and banking turns
- Background flocks of birds circling the sky
- A minimap (top-right) tracking your position and points of
  interest, plus a "new area discovered" banner as you explore
- 11 named points of interest and one large landmark spire

WHAT'S NOT IN THIS BUILD (by design, to keep it running well)
---------------------------------------------------------------
Villages with NPCs, ground wildlife (deer/wolves/etc.), weather
(rain/storms/fog), missions and a full progression/customization
system, a full-screen zoomable world map, and true chunk-streamed
terrain for a 20km+ world. These are all reasonable next steps if
you want to keep building this out.
