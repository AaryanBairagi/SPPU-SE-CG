# 🎨 Computer Graphics Lab – CGL (SE IT | SPPU 2019 Pattern)

This repository contains solutions for **SPPU Second Year – Computer Graphics Lab (CGL)** assignments.  
All implementations are written in **C / C++** and stored as `.txt` files.  

---

## 📂 Repository Structure  

Each assignment is directly stored as a `.txt` file in the root folder.  

```

📂 SPPU-SE-CGL
├── Assignment 2.txt   → DDA & Bresenham Line Drawing (simple, dotted, dashed, solid)
├── Assignment 3.txt   → Bresenham Circle Drawing
├── Assignment 4.txt   → Polygon Filling (Flood Fill, Boundary Fill)
├── Assignment 5.txt   → Cohen–Sutherland Polygon Clipping
├── Assignment 6.txt   → 2D Transformations (Scaling, Rotation, Reflection)
├── Assignment 7.txt   → Fractal Patterns (Bezier, Koch Curve)
├── Assignment 8.txt   → Animation Principles

````

---

## 📌 Assignment Details  

### Assignment 2 — Line Drawing Algorithms  
* Implement **DDA** and **Bresenham** algorithms.  
* Support line styles:  
  - Simple Line  
  - Dotted Line  
  - Dashed Line  
  - Solid Line  
* Use **mouse interface**.  
* Display across four quadrants with `(0, 0)` as screen center.  
* Works for both positive and negative slopes.  

---

### Assignment 3 — Circle Drawing Algorithm  
* Implement **Bresenham Circle Algorithm**.  
* Draw any object using circle primitives.  
* Display object in **all quadrants** with respect to center and radius.  

---

### Assignment 4 — Polygon Filling Methods  
* Implement:  
  - Flood Fill (Seed Fill)  
  - Boundary Fill  
* Use **mouse click**, **keyboard interface**, and **menu-driven programming**.  

---

### Assignment 5 — Polygon Clipping  
* Implement **Cohen–Sutherland Polygon Clipping**.  
* Clip polygon w.r.t. viewport and window.  
* Use **mouse click** and **keyboard interface**.  

---

### Assignment 6 — 2D Transformations  
* Implement transformations on an object w.r.t. coordinate axes:  
  - Scaling  
  - Rotation about an arbitrary point  
  - Reflection  

---

### Assignment 7 — Fractal Patterns  
* Generate fractals using:  
  - Bezier Curves  
  - Koch Curve  

---

### Assignment 8 — Animation Principles  
* Implement animation for any simple object (translation, scaling, rotation, etc.).  

---

## ⚙️ Build & Run  

Each assignment is in a `.txt` file. Compile and run using GCC (or g++ if C++).  

```bash
gcc "Assignment X.txt" -o assignmentX.out -lGL -lGLU -lglut
./assignmentX.out
````

### Example:

```bash
gcc "Assignment 2.txt" -o assignment2.out -lGL -lGLU -lglut
./assignment2.out
```

---

## 🔧 Tech Stack

* **Language**: C / C++
* **Graphics Library**: OpenGL, GLUT
* **OS**: Linux (Ubuntu recommended)

---

## 🚀 Quick Start

1. Clone repo:

   ```bash
   git clone https://github.com/<your-username>/SPPU-SE-CGL.git
   cd SPPU-SE-CGL
   ```
2. Compile any assignment as shown above.
3. Interact with the program using mouse and keyboard inputs.

---

## 🙌 Author

**Aaryan Bairagi**
SE IT | Savitribai Phule Pune University
GitHub: [@AaryanBairagi](https://github.com/AaryanBairagi)

---

## 📌 License

This project is for academic learning purposes only.
© 2025 Aaryan Bairagi – All rights reserved.

