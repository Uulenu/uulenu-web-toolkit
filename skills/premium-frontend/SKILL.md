---
name: premium-frontend
description: Build polished, highly interactive React and Next.js interfaces using React Three Fiber, Three.js, GSAP, Lenis, and Liquid Glass. Use for premium landing pages, portfolios, interactive websites, animated product experiences, and visually rich web applications.
---

# Premium Frontend

Build production-quality interactive frontend experiences.

Prefer React, Next.js, TypeScript, and modern CSS.

## Core stack

Use:

- React Three Fiber for WebGL and 3D experiences
- Three.js as the underlying 3D engine
- GSAP for complex animation
- GSAP ScrollTrigger for scroll-driven animation
- Lenis for smooth scrolling
- Liquid Glass for glass/refraction UI effects

Do not use these libraries merely because they are available.

Choose the simplest technology capable of producing the requested result.

## Before implementation

Determine whether the requested effect requires:

1. normal CSS
2. GSAP
3. GSAP + Lenis
4. Three.js / React Three Fiber
5. Liquid Glass

Avoid unnecessary WebGL.

## React Three Fiber

Read:

references/r3f.md

Use R3F when the interface requires:

- 3D scenes
- WebGL
- interactive models
- particles
- shaders
- 3D backgrounds
- camera movement
- 3D product presentation

## GSAP

Read:

references/gsap.md

Use GSAP for:

- timelines
- coordinated animations
- scroll animation
- complex transitions
- SVG animation
- staggered animation

Prefer CSS transitions for simple UI states.

## Lenis

Read:

references/lenis.md

Use Lenis when smooth scrolling materially improves the experience.

When Lenis and GSAP ScrollTrigger are both present, keep their animation loops synchronized.

## Liquid Glass

Read:

references/liquid-glass.md

Use Liquid Glass selectively for:

- navigation
- floating controls
- overlays
- cards
- hero UI
- contextual controls

Do not cover the entire interface with glass effects.

## Performance

Always:

- minimize unnecessary React renders
- clean up event listeners
- clean up GSAP timelines
- clean up WebGL resources
- lazy-load expensive components
- optimize textures and models
- use GPU-friendly transforms
- avoid excessive blur
- avoid excessive DOM animation
- test responsive behavior
- respect prefers-reduced-motion

Target smooth interaction on desktop and mobile.

## Code quality

Prefer:

- TypeScript
- reusable components
- semantic HTML
- accessible interactions
- responsive layouts
- clear component boundaries

Do not create giant components when functionality can be separated cleanly.