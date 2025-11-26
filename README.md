# 🌌 3D Solar System Project – Autodesk Maya (Arnold Renderer)

A visually realistic **3D Solar System** created in **Autodesk Maya** using **Arnold**, featuring HDRI-based skydome lighting, planet textures, and animation.

## ✨ Project Overview
This project demonstrates:
- Realistic planet textures
- HDRI lighting via Arnold Skydome
- Rotational & revolutionary planetary animation
- Cinematic camera path
- High‑quality Arnold rendering workflow

## 🎯 Objectives
- Create a solar system scene in Maya  
- Apply PBR textures  
- Use HDRI for global illumination  
- Animate rotation & revolution  
- Produce final rendered output  

## 🛠️ Toolchain
- Autodesk Maya  
- Arnold Renderer  
- HDRI Maps  
- Optional: Photoshop/GIMP for texture edits  
- Optional: After Effects/Premiere for video compile  

## 🌞 Methodology

### 1. Scene Setup
- Create spheres for each planet  
- Scale proportionally (simplified)  
- Create emissive Sun shader

### 2. Scaling Solar system
| Planet      | Formula   | Size (Scale XYZ) |
| ----------- | --------  | ---------------- |
| **Mercury** | 53 × 0.05 | **2.65**         |
| **Venus**   | 53 × 0.08 | **4.24**         |
| **Earth**   | 53 × 0.1  | **5.3**          |
| **Mars**    | 53 × 0.07 | **3.71**         |
| **Jupiter** | 53 × 0.4  | **21.2**         |
| **Saturn**  | 53 × 0.35 | **18.55**        |
| **Uranus**  | 53 × 0.25 | **13.25**        |
| **Neptune** | 53 × 0.24 | **12.72**        |
| **Sun**     | 53 × 0.8  | **42.4**         |

### 3. Apply Textures
Each planet uses:
- Albedo map  
- Roughness/specular map  
- Normal/bump map  

### 4. Lighting (Skydome + HDRI)
- Create Arnold → Skydome Light  
- Load HDRI (space environment)  
- Adjust exposure/intensity  

### 5. Animation
- Planet rotation (self‑spin)  
- Revolution around Sun using grouped transforms  

### 6. Camera
- Animate along path or manual keyframing  

### 7. Rendering
- Arnold Renderer  
- EXR/PNG sequence  
- Samples 3–5  
- Motion blur ON  

## 📂 Project Structure
```
SolarSystem_Project/
 ┣ scenes/
 ┃ ┗ solar_system.mb
 ┣ textures/
 ┣ renders/
 ┗ README.md
```
