# React Three Fiber

Official documentation:
https://r3f.docs.pmnd.rs/

Package:

npm install three @react-three/fiber

For TypeScript:

npm install -D @types/three

## Purpose

React Three Fiber is a React renderer for Three.js.

Use it when a React application requires real-time 3D/WebGL.

## Basic structure

```tsx
import { Canvas } from '@react-three/fiber'

export default function Scene() {
  return (
    <Canvas>
      <ambientLight intensity={0.5} />
      <mesh>
        <boxGeometry />
        <meshStandardMaterial />
      </mesh>
    </Canvas>
  )
}