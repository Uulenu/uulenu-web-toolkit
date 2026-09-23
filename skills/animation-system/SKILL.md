---
name: animation-system
description: Design and implement animation systems for React and Next.js websites using GSAP, ScrollTrigger, Lenis, CSS animation, and React Three Fiber.
---

# Animation System

Choose animation technology intentionally.

Use CSS for:

- hover
- focus
- simple transitions
- small UI changes

Use GSAP for:

- timelines
- coordinated sequences
- stagger animation
- advanced transforms
- SVG

Use ScrollTrigger for:

- scroll-driven reveals
- pinned sections
- parallax
- timeline scrubbing

Use Lenis for:

- smooth scrolling

Use R3F/useFrame for:

- 3D animation

Do not animate everything.

Motion should establish hierarchy and communicate state.

Respect prefers-reduced-motion.

Avoid layout-triggering animation when transform or opacity can achieve the same result.