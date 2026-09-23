
Your reference files don't have to duplicate entire upstream documentation. In fact, they shouldn't. They should contain the **important rules, patterns, installation commands, pitfalls, and links to canonical docs**.

### 5. GSAP reference

`references/gsap.md`:

```md
# GSAP

Repository:
https://github.com/greensock/gsap

Install:

npm install gsap

## Purpose

Use GSAP for complex and coordinated animation.

Typical use cases:

- timelines
- stagger animations
- page transitions
- scroll effects
- SVG animation
- hero sequences

## React

Use gsap.context or @gsap/react when appropriate.

Always clean up animations when components unmount.

Example:

```tsx
useEffect(() => {
  const ctx = gsap.context(() => {
    gsap.from(".hero-title", {
      y: 50,
      opacity: 0,
      duration: 1
    })
  })

  return () => ctx.revert()
}, [])