# NumPy Analyzer

## 📌 Project Description

**NumPy Analyzer** is a Python-based menu-driven program that allows users to create and analyze NumPy arrays. It provides options for array creation, mathematical operations, combining/splitting arrays, searching/sorting/filtering, and statistical calculations.

The project is designed to demonstrate the practical use of the **NumPy library** in Python.

---

## 🚀 Features

The NumPy Analyzer provides the following features:

### 1. Create a NumPy Array

* Create a **1D Array**
* Create a **2D Array**
* Create a **3D Array**
* Perform **Indexing**
* Perform **Slicing**

### 2. Perform Mathematical Operations

* Addition
* Subtraction
* Multiplication
* Division
* Dot Product
* Matrix Multiplication

### 3. Combine or Split Arrays

* Combine arrays using **Vertical Stack**
* Split an array

### 4. Search, Sort, or Filter Arrays

* Search for a value
* Sort the array
* Filter values

### 5. Compute Aggregates and Statistics

* Sum
* Mean
* Median
* Standard Deviation
* Variance
* Minimum
* Maximum
* Percentiles
* Correlation Coefficient

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**

---

## 📦 Installation

Install NumPy using pip:

```bash
pip install numpy
```

---

## ▶️ How to Run

Run the Python program using:

```bash
python numpy_analyzer.py
```

The program displays a menu:

```text
==========================================
           NUMPY ANALYZER
==========================================

Choose an option:
1. Create a Numpy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
```

---

## 📖 Working of the Program

### Create a NumPy Array

The user can select the type of array:

```text
Select the type of array to create:
1. 1D Array
2. 2D Array
3. 3D Array
```

Example of a 2D array:

```text
Array created successfully:
[[10 20 30]
 [40 50 60]]
```

The user can then perform:

```text
Choose an operation:
1. Indexing
2. Slicing
3. Go Back
```

Example slicing result:

```text
Sliced Array:
[[20 30]
 [50 60]]
```

---

### Mathematical Operations

The program provides:

```text
Choose a mathematical operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Dot Product
6. Matrix Multiplication
```

Example of addition:

```text
Original Array:
[[10 20 30]
 [40 50 60]]

Second Array:
[[5 5 5]
 [5 5 5]]

Result of Addition:
[[15 25 35]
 [45 55 65]]
```

---

### Combine or Split Arrays

The program allows the user to:

```text
Choose an option:
1. Combine Arrays
2. Split Array
```

Example of combining arrays using vertical stacking:

```text
Original Array:
[[10 20 30]
 [40 50 60]]

Second Array:
[[1 2 3]
 [4 5 6]]

Combined Array (Vertical Stack):
[[10 20 30]
 [40 50 60]
 [ 1  2  3]
 [ 4  5  6]]
```

---

### Search, Sort, or Filter

The available options are:

```text
Choose an option:
1. Search a value
2. Sort the array
3. Filter values
```

Example of sorting:

```text
Original Array:
[[10 20 30]
 [40 50 60]]

Sorted Array:
[[10 20 30]
 [40 50 60]]
(Sorting applied row-wise.)
```

---

### Aggregates and Statistics

The program provides several statistical operations:

```text
Choose an aggregate/statistical operation:
1. Sum
2. Mean
3. Median
4. Standard Deviation
5. Variance
6. Minimum
7. Maximum
8. Percentiles
9. Correlation Coefficient
```

Example:

```text
Median of Array: 35.0
```

---

## 🎯 Learning Objectives

This project helps in understanding:

* NumPy arrays
* 1D, 2D, and 3D arrays
* Array indexing and slicing
* Mathematical operations
* Array stacking and splitting
* Searching and filtering
* Sorting arrays
* Statistical functions
* Menu-driven Python programs
* Practical use of NumPy

---

## 📂 Project Structure

```text
NumPy-Analyzer/
│
├── numpy_analyzer.py
└── README.md
```

---

## 💻 Example Workflow

```text
Create a NumPy Array
        ↓
Index / Slice
        ↓
Perform Mathematical Operations
        ↓
Combine / Split Arrays
        ↓
Search / Sort / Filter
        ↓
Calculate Statistics
        ↓
Exit
```

---

## 👋 Exit Message

When the user selects option `6`, the program displays:

```text
Thank you for using the NumPy Analyzer! Goodbye!
```

---

## 📌 Conclusion

The **NumPy Analyzer** is a simple and useful Python project for practicing NumPy array operations. It combines different NumPy functionalities into one menu-driven application and helps build a strong understanding of array manipulation and statistical analysis.
