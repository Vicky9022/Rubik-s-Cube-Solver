# 🎲 Rubik's Cube Solver

This project is a **Rubik’s Cube Solver** built in **JavaScript, HTML, and CSS** as part of an assignment task. The solver provides a visual and interactive representation of a Rubik’s Cube, allows manual rotations, scrambling, and solving using a simplified layer-by-layer algorithm.

---

## 🚀 Features

* **Cube Representation**: Object-oriented implementation of the cube with 6 faces and 54 stickers.
* **Manual Rotations**: Buttons to rotate each face clockwise or counterclockwise.
* **Scrambling**: Random scramble generator with configurable number of moves.
* **Solving Algorithm**: Step-by-step simplified **Layer-by-Layer (LBL)** solver.

  * White Cross
  * White Corners
  * Middle Layer
  * Yellow Cross
  * Position & Orient Yellow Corners
  * Position Yellow Edges
* **Visualization**: Each step displays the cube state using the provided `getCubeSvg()` method.
* **Interactive Controls**: Reset cube, scramble, or auto-solve with a single click.
* **Status Indicator**: Shows whether the cube is solved or scrambled.

---

## 🛠️ Tech Stack

* **HTML5** – Structure & layout
* **CSS3** – Styling and responsive UI
* **JavaScript** – Cube logic, solver algorithm, and rendering

---

## 📂 Project Structure

```
.
├── index.html   # Main project file with JS, CSS, and HTML combined
└── README.md    # Project documentation
```

---

## 📖 How It Works

1. **Cube Representation**

   * The cube is stored as 6 arrays of 9 elements (one for each face).
   * Each face is initialized with a uniform color (`r, g, b, y, o, w`).
2. **Rotations**

   * Implemented manually for all 6 faces (`F, B, U, D, L, R`) in clockwise and counterclockwise directions.
3. **Solver**

   * A simplified solver algorithm (`CubeSolver` class) attempts to solve the cube in **multiple steps**, showing each intermediate state.
   * The solution may not be optimal but guarantees reaching a solved cube.
4. **Visualization**

   * The cube state is converted into a string and passed to `getCubeSvg()` for rendering in the browser.
   * Each step of the solution is shown with a small cube diagram.

---

## 🎮 How to Use

1. Clone the repo or download the project files.
2. Open `index.html` in a modern web browser.
3. Use the controls:

   * **Reset Cube** → Returns the cube to the solved state.
   * **Scramble Cube** → Generates a random scramble.
   * **Solve Cube** → Runs the solver and shows each step visually.
   * **Manual Rotations** → Rotate individual cube faces manually.

---

## 📷 Demo

* **Reset & Scramble:** Instantly reset or randomize the cube.
* **Step-by-Step Solving:** Watch the cube solve itself with intermediate states.
* **Status Updates:** Know when the cube is solved or scrambled.

---

## 🔗 Assignment Requirements

This project implements all required tasks:

1. **Cube representation (object-oriented)** – Done ✅
2. **Manual rotations** – Done ✅
3. **Cube scrambling** – Done ✅
4. **Solver algorithm with visualization** – Done ✅

---

## 📌 Developer Info

* **Name:** Vikas Rathod
* **Highest Qualification:** B.Tech (CSE) Final Year
* **Skills:** JavaScript, HTML, CSS, React, Node.js
* **Contact:** 9022265650 | [vikasrathod90222@gmail.com](mailto:vikasrathod90222@gmail.com)

---

## 📎 Links

* **Resume:** https://drive.google.com/file/d/102Wrf0MZNBTp6qwIfglcuklD49t1i5WV/view?usp=drivesdk
* **GitHub Repo:** https://github.com/Vicky9022/Rubik-s-Cube-Solver.git

---

## ⚠️ Notes

* The solving algorithm is **simplified** and not optimized for minimal moves.
* The purpose of this project is to **demonstrate problem-solving and programming skills**, not to compete with advanced solvers.
