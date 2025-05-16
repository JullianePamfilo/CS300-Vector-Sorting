# 🧠 CS 300 Module Two: Vector Sorting in Java

Hi there! I'm **Julliane Pamfilo**, and this project is part of my CS 300 coursework at SNHU. The goal of this assignment is to compare two sorting algorithms — **Selection Sort** and **QuickSort** — and understand their performance when applied to a list of auction bid data from a municipal government system.

---

## 🚀 What This Program Does

- Loads bid data from a `.csv` file
- Sorts the data by title using:
  - ✅ Selection Sort (basic, but slow)
  - ✅ QuickSort (faster and more efficient)
- Displays the number of bids and timing results
- Demonstrates how algorithm choice impacts performance

---

## 🔍 Features & Concepts Covered

- File I/O and CSV parsing
- Vector manipulation
- Selection sort implementation (O(n²))
- QuickSort implementation (O(n log n) average case)
- Use of `clock_t` to measure execution time
- Object-oriented design with a `Bid` struct

---

## 🧪 How to Run This Project

### 1. Compile the Code
In your terminal, run:

```bash
g++ VectorSorting.cpp CSVparser.cpp -o VectorSorting
```

### 2. Run the Program
```bash
./VectorSorting eBid_Monthly_Sales.csv
```

> Or use the smaller sample:
```bash
./VectorSorting eBid_Monthly_Sales_Dec_2016.csv
```

---

## 📂 File Overview

| File                  | Description                                 |
|-----------------------|---------------------------------------------|
| `VectorSorting.cpp`   | Main logic, sorting methods, menu interface |
| `CSVparser.cpp`       | Custom CSV parsing utility                  |
| `CSVparser.hpp`       | Header file for CSV parser                  |
| `eBid_*.csv`          | Input datasets                              |
| `README.md`           | This file 😊                                |

---

## 🧠 What I Learned

- How algorithm selection dramatically affects performance
- How to implement and compare classic sorting methods
- How to work with vectors, structs, and timing in C++
- Why clean, modular design improves readability and testing

---

## 📌 Project Context

- **Course**: CS 300 – Operating Platforms
- **Instructor**: SNHU Faculty
- **Student**: Julliane Pamfilo
- **Topic**: Static sorting performance analysis

---

Thanks for checking this out! I had a great time building and testing this. Feel free to clone it and try out different datasets or sorting approaches!
