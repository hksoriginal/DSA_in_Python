# Data Structures & Algorithms in Python 🚀

Welcome to the **DSA in Python** repository! This repository contains a structured, hands-on compilation of core Data Structures and Algorithms (DSA) concepts implemented in Python. All topics, code implementations, and optimal solutions are documented interactively in a Jupyter Notebook.

---

## 📂 Repository Contents

The primary notebook in this repository is:
* 📓 **[DSA_Python.ipynb](./DSA_Python.ipynb)** - The interactive playground containing code explanations, execution blocks, and output streams for each algorithm.

---

## 🛠️ Topics Covered

### 1. Basic Mathematical Algorithms
Fundamental mathematical operations and properties optimized for algorithmic efficiency:
* **Palindrome Checker**: Checks if a given number is symmetric.
* **Armstrong Number**: Computes and checks if a number equals the sum of its digits raised to the power of the number of digits.
* **Factors Finder**: Prints all factors of a number using:
  * A brute force approach.
  * An optimal $O(\sqrt{N})$ approach.

### 2. Hashing Techniques
Basic frequency tracking techniques that form the basis of lookup optimizations:
* **Number Hashing**: Count frequencies of numbers in arrays using Python dictionaries (`hash map` equivalent).
* **Character Hashing**: Build string lookup hashes to fetch occurrence frequencies in $O(1)$ lookup time.

### 3. Recursion (From Basics to Advanced)
A comprehensive guide to understanding and visualizing call stacks and recursion types:
* **Recursion Basics**:
  * **Head Recursion** vs. **Tail Recursion** (Backtracking structures).
* **Recursion Paradigms**:
  * **Parameterized Recursion** (carrying state through arguments).
  * **Functional Recursion** (returning values up the call stack, e.g., Sum of 1 to $N$).
* **Classic Recursion Problems**:
  * **Factorial Calculation**
  * **Array Reversal** (using recursive left/right pointer swap).
  * **String Palindrome Check** (using recursive character comparisons).
  * **Fibonacci Sequences** (multiple-branch recursion tree).

### 4. Sorting Algorithms
Implementation and comparisons of fundamental sorting algorithms:
* **Selection Sort**: Find the minimum/maximum and place it in the correct position.
* **Bubble Sort**: Repeatedly swap adjacent elements if they are in the wrong order, optimized with a flag to exit early if already sorted.
* **Insertion Sort**: Build the final sorted array one item at a time.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ and `jupyter` or `notebook` installed on your system.

### Running the Notebook

1. **Clone the repository:**
   ```bash
   git clone git@github.com:hksoriginal/DSA_in_Python.git
   cd DSA_in_Python
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
   ```

3. **Install Jupyter Notebook:**
   ```bash
   pip install jupyter
   ```

4. **Launch Jupyter:**
   ```bash
   jupyter notebook DSA_Python.ipynb
   ```

---

## 📈 Roadmap

Future updates to this repository will cover:
- [ ] Advanced Sorting (Merge Sort, Quick Sort, Heap Sort)
- [ ] Linked Lists (Singly, Doubly, Circular)
- [ ] Stacks & Queues
- [ ] Trees & Graphs
- [ ] Dynamic Programming & Greedy Algorithms

Feel free to open an issue or submit a pull request if you want to contribute new algorithms or optimizations!
