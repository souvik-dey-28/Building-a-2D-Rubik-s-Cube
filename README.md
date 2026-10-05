<img width="800" height="396" alt="image" src="https://github.com/user-attachments/assets/01728d79-7f9f-4e9b-8470-6064dd8f2417" />

# 2D Planar Rubik's Cube Simulator 🧊🔄

A mathematically accurate, interactive 2D projection of a $3 \times 3 \times 3$ Rubik's Cube built entirely with Vanilla JavaScript and HTML5 Canvas. 

Instead of rendering a 3D block, this engine maps the strict permutation group of a Rubik's Cube onto a flat geometric graph of intersecting circular tracks. It allows for independent slice rotations, full-block face turns, and fluid orbital animations.

![Preview Placeholder](link-to-your-gif-or-screenshot-here.gif)

## 🧠 The Mathematical Engine

Translating a 3D cube into a functioning 2D planar graph requires specific geometric rules to prevent the nodes (stickers) from drifting or breaking the permutation logic:

* **The 3 Lobes:** The cube is flattened into 3 main axes (lobes) arranged in an equilateral triangle. These represent the X, Y, and Z spatial axes.
* **The 9 Rings:** Each lobe contains exactly 3 concentric tracks. Overlapping the 3 lobes generates exact mathematical intersections.
* **The 54 Nodes:** The intersections of these rings create exactly 9 inner points and 9 outer points per paired intersection, totaling 54 nodes—flawlessly matching the 54 stickers of a physical $3 \times 3 \times 3$ cube.
* **Permutation Shifts:** A 90-degree face turn on a real cube translates mathematically to an exact 3-index array shift along these mapped circular tracks. 

## ✨ Features

* **True Slice Rotations:** Rotate the Outer, Middle, and Inner tracks independently, mapping perfectly to standard Rubik's notation (U/E/D, L/M/R, F/S/B).
* **Fluid Animation Engine:** Custom tweening and easing functions for smooth orbital node transitions.
* **Scramble Algorithm:** Uses a true scramble mechanic that applies 25 random, isolated slice rotations to thoroughly shuffle the board.
* **Zero Dependencies:** Built entirely with pure HTML, CSS, and JS. No external libraries, game engines, or frameworks required.
* **Dark UI Theme:** Sleek, responsive, sci-fi-inspired interface with move tracking and instant resets.

## 🚀 How to Run

Because this project has zero external dependencies, running it is instantaneous:

1. Clone or download this repository.
2. Double-click the `index.html` file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Play!

## 🎮 Controls

The UI is divided into the three spatial axes of the cube:
* **X-Axis (Left Lobe):** Controls the Left, Middle, and Right slices.
* **Y-Axis (Top Lobe):** Controls the Up, Equator, and Down slices.
* **Z-Axis (Right Lobe):** Controls the Front, Standing, and Back slices.
* Use the **↺** and **↻** buttons to rotate individual tracks or the entire lobe.

## 👨‍💻 Author

**Souvik Dey** 
<!--* B.Tech Information Technology
* [Link to your Portfolio/LinkedIn]-->