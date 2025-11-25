# 🌌 3D Solar System Animation – Autodesk Maya  
### Realistic Texturing • HDRI Space • Planet Motion • Arnold Rendering

---

## 🚀 Project Overview

This project is a fully modeled, textured, animated, and rendered **3D Solar System**, created in **Autodesk Maya** using **Arnold Renderer**.  
It includes all eight planets, the Sun with plasma animation, Saturn’s rings, HDRI star environment, and cinematic camera motion.  
All planet sizes and distances follow the **Roll No. 53 scaling rule**.

---

## 🎯 Objective

- Create a realistic Solar System model in Autodesk Maya.  
- Apply **Roll No. 53** formula for scaling distances and sizes.  
- Use NASA 8K textures and AiStandardSurface for realism.  
- Animate:
  - Planet **rotation**
  - Planet **revolution**
  - Sun **plasma motion**
- Use HDRI lighting for a realistic star universe.  
- Render a final **1080p cinematic animation** using Arnold.

---

## 🛠️ Toolchain

| Tool / Resource | Purpose |
|-----------------|----------|
| **Autodesk Maya** | Modeling, animation, materials |
| **Arnold Renderer** | HDRI lighting & rendering |
| **AiStandardSurface** | Planet & Sun shading |
| **NASA 8K Textures** | Real planetary surfaces |
| **EXR HDRI Maps** | Space background & lighting |
| **Photoshop / GIMP** | Optional texture editing |
| **DaVinci / Premiere** | Final video assembly |

---

## 🔭 Methodology

### 1️⃣ Modeling
- Created Sun & planets using polygon spheres.  
- Built Saturn’s ring using a **Torus**.  
- Organized objects using a clean Outliner structure.  
- Applied scaling with `53 × multiplier` rule.

---

### 2️⃣ Texturing & Shading

**Sun**
- AiStandardSurface  
- Emission shader + procedural aiNoise  
- Animated plasma effect  

**Planets**
- Applied **NASA 8K textures**  
- Controlled roughness + specular  
- Tilted axis where necessary  

**Saturn’s Rings**
- Torus geometry  
- Rings PNG with transparency (opacity input)  

**Star Background**
- HDRI Skydome Light  
- Space EXR map for deep star universe  

---

### 3️⃣ Animation

#### 🔄 Planet Rotation (Spin)
Using Rotate Y animation:

| Planet  | Frames |
|---------|--------|
| Mercury | 80     |
| Venus   | 150    |
| Earth   | 120    |
| Mars    | 100    |
| Jupiter | 70     |
| Saturn  | 80     |
| Uranus  | 90     |
| Neptune | 110    |

#### 🌀 Planet Revolution (Orbit)
Planets grouped inside a parent node:

