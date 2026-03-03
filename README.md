🏎️ Racer Vibe Coding experiment
--------------------------------

A retro-inspired, 3D off-road buggy simulator built with Three.js. Inspired by the 90s classic Terep2, this game features procedural terrain, custom physics, and a high-speed balloon collection challenge.

🕹️ Live Demo
-------------

[https://bacce.github.io/terep2-clone/](https://bacce.github.io/terep2-clone/)

🌟 Features
-----------

**Procedural Landscapes:** Every game generates a unique 400m x 400m map using multi-octave noise. No two runs are the same.

**Custom Physics Engine:** A lightweight, math-based vehicle simulation. Experience uphill struggles, downhill speed boosts, and realistic suspension tilting without the overhead of a physics library.

**Retro Aesthetic:** Flat-shaded polygons and height-based terrain coloring (Grass, Dirt, Snow) for that classic 90s workstation look.

**Dynamic Buggy Model:** An open-air buggy featuring a roll cage, visible engine block, and responsive steering animation.

**Challenge System:** Three difficulty levels (Easy, Medium, Hard) requiring you to collect 10, 20, or 30 balloons before the 2-minute timer runs out.

**Zero Dependencies:** The entire game is contained within a single HTML file using CDN-linked Three.js.

⌨️ Controls
-----------

KeyAction

W / ↑Accelerate

S / ↓Brake / Reverse

A / DSteer Left / Right

RReset Car (if flipped or stuck)

SpaceHandbrake

🛠️ Technical Details
---------------------

Rendering: Three.js (WebGL).

Terrain: Non-indexed PlaneGeometry for hard-edge "flat" shading.

Physics: Custom terrH(x, z) height-sampling for collision detection and slope-based acceleration.

Camera: Framerate-independent exponential decay follow-camera with yaw-only rotation to prevent motion sickness on steep slopes.

Performance: Optimized to run at 60fps on most modern browsers.

🚀 Installation & Usage
-----------------------

Since this is a single-file project, there is no build step required.

Open index.html in any modern web browser.

Or just open the github pages link from the sidebar.

📜 Personal Note
----------------

This project was developed through a unique "Art Director" workflow, focusing on high-level system architecture and aesthetic "feel" using AI-assisted iterative planning. The goal was to recreate the specific soul of 90s sandbox driving games while utilizing modern web technologies.

⚖️ License
----------

This project is licensed under the MIT License - see the LICENSE file for details.
