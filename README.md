# Julia & Mandelbrot Fractal Generator in MATLAB  
**Visual exploration of adaptive control through fractal metrics**

## 🧠 Description

This project is an **educational MATLAB application** designed to visualize Julia and Mandelbrot fractals and connect them to adaptive control theory.  
The user can generate complex fractal images, compute image-based metrics (entropy and variation), and derive simulated PID coefficients from them.

While not simulating a real-world control system, the project serves as a **didactic tool** to illustrate how fractals can reflect complex, dynamic behaviors — similar to nonlinear systems in automation and control.

---

## 🧩 Key Features

- Generate **Julia** and **Mandelbrot** fractals with adjustable parameters
- Visualize effects of entropy and variation
- Compute simulated PID coefficients:
  - `P` ← image entropy
  - `I` ← pixel intensity variation
  - `D` ← |P - I|
- Animate evolution of Julia sets
- Built with MATLAB App Designer

---

## ⚙️ Technologies

- **MATLAB App Designer (.mlapp)**
- Complex number manipulation
- Image processing (entropy & variation)
- Interactive GUI (sliders, dropdowns, plot areas)

---

## 🧪 Educational Purpose

The project connects **fractals** (as chaotic, parameter-sensitive systems) with **adaptive PID control logic**.  
Fractal behavior helps illustrate system variability, unpredictability, and feedback responses — all key to understanding adaptive control in engineering.

> 🔍 *Entropy reflects system complexity (used as P)*  
> 🔍 *Variation shows distribution stability (used as I)*  
> 🔍 *Difference between the two used as D gain*

---

## 📌 Notes

This is a personal educational project created to support my studies in control theory and nonlinear systems.  
It is not a commercial tool and does not simulate any real industrial system.  
Some ideas and formulations were adapted using AI tools, MATLAB documentation, and academic inspiration.

---

## 👤 Author

Robert-Constantin Preda  
Automation and Applied Informatics  
University of Craiova

