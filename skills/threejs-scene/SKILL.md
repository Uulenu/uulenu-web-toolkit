---
name: threejs-scene
description: Design and implement performant Three.js and React Three Fiber scenes for React applications, including lighting, cameras, models, particles, interaction, shaders, and animation.
---

# Three.js Scene Builder

Use this skill for 3D/WebGL implementation.

Before writing code determine:

- scene purpose
- camera type
- lighting requirements
- geometry/model requirements
- interaction
- animation
- performance constraints

Prefer React Three Fiber for React applications.

Keep scene components modular.

Example structure:

Scene
├── Camera
├── Lights
├── Environment
├── Models
├── Effects
└── Controls

Avoid unnecessary geometry complexity.

Optimize:

- draw calls
- textures
- model size
- shadows
- postprocessing
- animation loops

For mobile, reduce expensive effects when necessary.