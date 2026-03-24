# 📍 Closest Pair of Points — Interactive Visualization

An interactive teaching tool that demonstrates the **Closest Pair of Points** problem using both:

* 🔴 Brute Force — O(n²)
* 🟢 Divide & Conquer — O(n log n)

This project is built as a **single HTML file** using **HTML, CSS, JavaScript, and SVG**, with no external libraries.

---

## 🚀 Live Demo

👉 (Paste your GitHub Pages link here)

---

## 🎯 Project Objective

The goal of this project is to:

* Visualize how the Closest Pair algorithm works step-by-step
* Compare brute force and divide & conquer approaches
* Help users understand algorithm efficiency and optimization
* Provide an interactive learning experience

---

## 🧠 Key Concepts Covered

* Divide and Conquer paradigm
* Time complexity analysis
* Sorting and searching techniques
* Recursion and recursion trees
* Geometric optimization (strip method, ≤7 comparisons rule)

---

## 🧩 Features

### 🎮 Interactive Controls

* Custom point input
* Preset datasets (Simple, Cluster, Worst Case, Random)
* Speed control (0.25× – 4×)
* Playback controls:

  * Build Steps
  * Step
  * Play
  * Pause
  * Reset

---

### 📊 Visualization

* 2D scatter plot using SVG
* Animated:

  * Dividing line
  * Recursive splits
  * Strip region (2δ)
  * Closest pair highlighting
* Smooth step-by-step animation

---

### 📈 Complexity Analysis (CLO-1)

* O(n²) vs O(n log n) comparison
* Recurrence relation:
  T(n) = 2T(n/2) + O(n)
* Graph showing actual vs theoretical performance
* Operation (comparison) counting
* Worst-case explanation

---

### 🔍 Sorting & Searching (CLO-2)

* Sorting points by x-coordinate
* Sorting strip by y-coordinate
* Efficient strip search (≤ 7 comparisons)
* Explanation of why sorting is necessary

---

### 🌳 Divide & Conquer (CLO-3)

* Recursive splitting of points
* Visualization of recursion tree
* Combine step using strip method
* Comparison with brute force

---

### 📜 Learning Aids

* Pseudocode with line highlighting
* Step-by-step explanations
* History table (clickable steps)
* Color legend
* Educational sections (overview, examples, concepts)

---

## ⚙️ How It Works

### Brute Force

* Compares all pairs of points
* Time Complexity: O(n²)

### Divide & Conquer

1. Sort points by x-coordinate
2. Divide into left and right halves
3. Recursively find closest pairs
4. Compute δ = min(left, right)
5. Build strip of width 2δ
6. Check at most 7 neighbors per point

Time Complexity: O(n log n)

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript (ES6)
* SVG (for visualization)

---

## ▶️ How to Run

1. Download the project
2. Open `index.html` in any browser

No installation or dependencies required.

---

## 📌 Notes

* This project is designed for educational purposes
* Fully interactive and self-contained
* Works offline

---

## 👨‍💻 Author

(Omid Ghadim)

---

## 📄 License

This project is for academic use.
