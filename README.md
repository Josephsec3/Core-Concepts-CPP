# Core Concepts in C++: Array Operations & Statistical Logic

## 🎯 Overview
This repository contains functional C++ source code demonstrating efficient array manipulation, sorting, and statistical calculations. The program processes a specific structure of datasets to calculate a precise **trimmed mean** by filtering out extreme data points.

## 🛠️ Logic & Algorithm
1. **Input Optimization:** Utilizes `ios_base::sync_with_stdio(false)` and `cin.tie(nullptr)` for fast I/O operations, making it highly optimized for large telemetry data.
2. **Data Filtering:** Accepts a dynamic range of numbers ($5N$), stores them in a flat vector, and sorts them in ascending order.
3. **Trimmed Calculation:** Discards the lowest $N$ elements and the highest $N$ elements (removing potential outliers) to compute the mathematical average of the middle $3N$ core data.

## 🚀 Technical Highlights
* **Language:** C++17
* **Key Components:** `std::vector`, `std::sort`, dynamic standard input streams (`std::cin`).
* **Precision:** Enforces a structural fixed-point output with a precision of 6 decimal places.
