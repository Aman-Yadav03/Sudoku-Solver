# 🧠 Real-Time Sudoku Solver using Deep Learning & OpenCV

This project demonstrates a real-time Sudoku puzzle solver that detects a Sudoku board from a webcam feed, recognizes digits using a trained Convolutional Neural Network (CNN), and solves the board using a backtracking algorithm. The final solution is projected back onto the original video frame — all in real time.

> 👁️‍🗨️ Computer Vision + 🧮 Deep Learning + 🧠 Backtracking = 🧩 Real-Time Sudoku Solver

---

## 🎯 Project Objective

The main objective is to automate the process of solving Sudoku puzzles directly from images or video streams using a combination of:

- Image Processing (for grid detection and preprocessing)
- Digit Recognition (via a CNN model)
- Sudoku Solving (backtracking algorithm)
- Visualization (solution overlaid on original image)

---

## 📂 Repository Structure

```text
├── Main.ipynb                  # End-to-end overview of the entire system
├── RealTimeSudokuSolver.ipynb  # Real-time detection, recognition, solving, and display
├── sudokuSolver.ipynb          # Sudoku solving algorithm (backtracking)
├── digitRecognition.ipynb      # CNN model training for digit recognition
├── README.md                   # You're reading this
```
---

## 🚀 Features

- 🔍 **Sudoku Grid Detection** – Detects 9x9 Sudoku puzzles from camera frames using OpenCV.
- 🧠 **Digit Recognition** – Classifies digits using a Convolutional Neural Network (CNN) trained on MNIST.
- 📐 **Perspective Correction** – Applies transformations to obtain a top-down view of the Sudoku board.
- 🤖 **Sudoku Puzzle Solving** – Uses a backtracking algorithm to solve the puzzle efficiently.
- 🖼️ **Solution Overlay** – Maps and displays the solved puzzle back onto the original image/video in real-time.
- 📷 **Real-Time Webcam Integration** – Captures live video feed to detect and solve Sudoku puzzles automatically.
- 🧪 **Interactive Testing** – Modular notebooks allow testing and development of individual pipeline components.

---

## 🛠 Technologies Used

| Category        | Tools & Libraries                         |
|----------------|--------------------------------------------|
| Programming     | Python 3                                   |
| Computer Vision | OpenCV, Imutils                            |
| Deep Learning   | TensorFlow, Keras                          |
| Data Handling   | NumPy, Matplotlib                          |
| Development     | Jupyter Notebook                           |
| Dataset         | MNIST (Modified for Sudoku digit training) |

---

## 📦 Requirements

Before running the notebooks, make sure you have Python 3 installed and then install the following libraries:

```bash
pip install numpy opencv-python tensorflow matplotlib imutils
