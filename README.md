# NumPy Practice & Revision 🔢

A dedicated repository for learning and revising the core functionalities of the **NumPy** library in Python. These scripts serve as a practical guide to handling N-dimensional arrays effectively, covering everything from basic creation to advanced manipulation.

## 🚀 Key Topics Covered

The repository contains modular Python scripts demonstrating various NumPy capabilities:

### 1. Array Operations and Broadcasting
File: `Array_Operations_and_Broadcasting.py`
- Basic arithmetic (addition, subtraction, multiplication, division) between arrays.
- **Broadcasting:** How NumPy handles operations between arrays of different shapes (e.g., adding or multiplying a scalar to an entire array).

### 2. Array Manipulation
File: `Array_Manipulation_in_NumPy.py`
- Reshaping arrays to different dimensions using `.reshape()`.
- Transposing arrays using `.T`.
- Flattening ND arrays into 1D arrays using `.flatten()`.
- Modifying arrays conditionally with `np.where()`.
- Adding and removing specific rows and columns (`np.vstack`, `np.hstack`, `np.delete()`).

### 3. Indexing and Slicing
File: `Indexing_and_Slicing_of_NumPy_Arrays.py`
- Accessing specific elements in an N-dimensional array using coordinate indexing.
- Slicing syntax to extract rows, columns, or specific submatrices.
- Updating and modifying specific slices of an array directly.

### 4. Adding and Removing Elements
File: `Methods_for_Adding_and_Removing_Elements.py`
- Appending values to the end of an array using `np.append()`.
- Inserting values at specific indices utilizing `np.insert()`.
- Concatenating multiple arrays using `np.concatenate()`.
- Deleting single or multiple elements based on their index using `np.delete()`.

### 5. Stacking and Splitting Arrays
File: `Stacking_and_Splitting_of_Arrays.py`
- Vertically combining (stacking) arrays using `np.vstack()`.
- Horizontally stacking arrays using `np.hstack()`.
- Slicing existing arrays into multiple smaller, equal-sized arrays across specified axes using `np.vsplit()` and `np.hsplit()`.

## 🛠 Prerequisites

To run these scripts, you must have Python installed along with the NumPy library.

```bash
pip install numpy
```

## 📝 Running the Scripts

Execute any of the `.py` files in your terminal to see the printed outputs of the various array operations:

```bash
python Array_Manipulation_in_NumPy.py
```