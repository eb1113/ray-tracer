# Ray Tracer — In a Weekend (C++)

This project is a C++ ray tracer built by following and learning from the excellent book  
**_Ray Tracing in One Weekend_** by **Peter Shirley**.

The goal of this repository is educational: to understand the fundamentals of ray tracing,
computer graphics, and physically based rendering by implementing everything from scratch.

---

## 📚 Credit & Attribution

This implementation closely follows the structure, algorithms, and ideas presented in:

> **Peter Shirley, _Ray Tracing in One Weekend_**  
> https://raytracing.github.io/books/RayTracingInOneWeekend.html

All core concepts (ray–object intersections, materials, reflection, refraction, camera,
sampling, etc.) are learned from and inspired by this book. Any mistakes or deviations
from the reference implementation are my own.

---

## ✨ Features Implemented

- Ray–sphere intersection
- Camera model with perspective projection
- Surface normals visualization
- Lambertian (diffuse) materials
- Metal materials with fuzzy reflection
- Dielectric (glass) materials with refraction
- Recursive ray tracing
- Anti-aliasing via random sampling
- Gamma correction
- Scene composition using polymorphic objects (`hittable` abstraction)

---

## 🚀 Planned Extensions

While this project currently mirrors the "In One Weekend" ray tracer, I intend to build on it by adding:

- **Axis-Aligned Bounding Boxes (AABB)**
- **Bounding Volume Hierarchy (BVH)** for faster rendering
- adding this ray tracing similar to the one found here to my Night-Forest Project
- Additional geometry types
- New materials and textures
- Performance improvements and optimizations

These extensions will go beyond the original tutorial and serve as further learning and experimentation.

---

## 🛠️ Build Instructions

This project uses **CMake**.

```bash
mkdir build
cmake -B build
cmake --build build
build/raytracer > image.ppm

