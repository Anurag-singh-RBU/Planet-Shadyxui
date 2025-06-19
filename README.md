# 🌍 Planet Component

This is a **3D Planet Component** created using React Three Fiber and Drei, with a GLTF model designed on Sketchfab.  
The planet rotates with lighting and shadows — perfect for creating an aesthetic hero section or 3D interactive background !

---

## About the Model

- The 3D model is sourced from [Sketchfab](https://sketchfab.com/).
- The model format used is `.gltf` — an efficient format for transmitting 3D scenes and models.
- Associated `.bin` file contains mesh data like geometry , normals , animations etc.

### What is `.gltf` ?

- **GL Transmission Format (GLTF)** is an open-standard 3D file format.
- It contains **scene structure, materials, textures** , animations , and more.
- It is lightweight and optimized for runtime transmission.

### What is `.bin` ?

- The `.bin` file stores **binary mesh data** (vertex positions, normals, tangents, skinning weights).
- It is referenced inside the `.gltf` file to provide geometry details.

---

## How to Use

1️⃣ Install the required dependencies.  
2️⃣ Copy all the 3D model files into /public/planet/.  
3️⃣ Create EarthCanvas.jsx or EarthCanvas.tsx component.  
4️⃣ Import the component into your page.  
5️⃣ Enjoy the Vibe !!

---

## Required Dependencies

To use this component, you need:

| Package                    | Purpose                                  |
|----------------------------|------------------------------------------|
| `three`                    | Core 3D rendering engine                  |
| `@react-three/fiber`       | React renderer for Three.js               |
| `@react-three/drei`        | Useful helpers for Three.js (OrbitControls, Preload, etc.) |

### NPM Commands:

```bash
# Using NPM
npm install three @react-three/fiber @react-three/drei

# Using Yarn
yarn add three @react-three/fiber @react-three/drei

# Using PNPM
pnpm add three @react-three/fiber @react-three/drei

# Using Bun
bun add three @react-three/fiber @react-three/drei


