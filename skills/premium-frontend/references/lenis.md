
### 6. Lenis reference

`references/lenis.md`:

```md
# Lenis

Repository:
https://github.com/darkroomengineering/lenis

Install:

npm install lenis

## Purpose

Lenis provides smooth scrolling for modern web experiences.

Use it when smooth scrolling contributes meaningfully to the design.

Avoid excessive scroll hijacking.

Preserve usability and accessibility.

## GSAP integration

When using GSAP ScrollTrigger with Lenis:

- synchronize ScrollTrigger with Lenis scroll events
- use a shared animation timing strategy
- update ScrollTrigger when scrolling changes
- clean up listeners on unmount

Do not create multiple competing requestAnimationFrame loops unnecessarily.