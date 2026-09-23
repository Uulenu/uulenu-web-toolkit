---
name: frontend-performance
description: Audit and optimize performance of animation-heavy React, Next.js, Three.js, React Three Fiber, GSAP, and Lenis websites.
---

# Frontend Performance

Analyze:

- bundle size
- React renders
- WebGL performance
- animation loops
- DOM complexity
- texture memory
- model complexity
- image loading
- fonts
- layout shifts
- mobile performance

Prioritize actual bottlenecks instead of premature optimization.

For animation prefer:

transform
opacity

Avoid repeatedly animating layout properties when unnecessary.

For R3F inspect:

- draw calls
- geometry complexity
- texture sizes
- shadows
- postprocessing
- DPR
- unnecessary useFrame callbacks

For React inspect:

- unnecessary state
- unnecessary renders
- expensive effects
- large client components

Maintain visual quality while removing unnecessary computational cost.