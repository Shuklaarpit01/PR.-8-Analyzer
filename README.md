# 🚀 PR. 8 ANALYZER (NumPy Analyzer)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6A5ACD,100:00C9A7&height=230&section=header&text=PR.%208%20NumPy%20Analyzer&fontSize=38&fontColor=ffffff&animation=fadeIn"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=24&pause=1000&color=00C9A7&center=true&vCenter=true&width=700&lines=🐍+Python+NumPy+Analyzer;📊+1D+2D+3D+Array+Operations;🔎+Search+Sort+Filter+Arrays;📈+Statistics+and+Matrix+Operations;✨+Created+by+Shukla+Arpit"/>
</p>

---

# 👨‍💻 Project Information

| Detail            | Value          |
| ----------------- | -------------- |
| **Practical No.** | PR. 8          |
| **Project Name**  | NumPy Analyzer |
| **Language**      | Python         |
| **Library Used**  | NumPy          |
| **Developer**     | Shukla Arpit   |

---

# 🌟 About Project

**NumPy Analyzer** is a menu-driven Python application that performs different array operations using the NumPy library.

### ✨ Features

* 📦 Create 1D, 2D and 3D Arrays.
* ✂️ Indexing & Slicing.
* ➕ Addition, Subtraction, Multiplication, Division.
* 🔢 Dot Product & Matrix Multiplication.
* 🔍 Search, Sort & Filter.
* 📊 Sum, Mean, Median, Variance, Standard Deviation.
* 📈 Percentile & Correlation Coefficient.

---

# 🎬 Python Animation

<p align="center">
  <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="240"/>
  <img src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif" width="240"/>
</p>

---

# 📚 Library Used

```python
import numpy as np
```

NumPy is used for creating arrays and performing mathematical and statistical operations.

---

# 📂 Project Structure

```text
PR-8-Numpy-Analyzer/
│
├── analyzer.py
├── README.md
└── requirements.txt
```

---

# 🚀 How to Run

```bash
python analyzer.py
```

---

# 💻 Main Menu Output

```text
==========================================
            NUMPY ANALYZER
==========================================

1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
```

---

# 📝 Code Snippets

## 1️⃣ Create Array

```python
self.array = np.array(values)
```

Creates a NumPy array from user input.

### Output

```text
Array created successfully:
[10 20 30 40 50]
```

---

## 2️⃣ Indexing

```python
print("Element:", self.array[i])
```

### Output

```text
Enter index: 2

Element: 30
```

---

## 3️⃣ Slicing

```python
result = self.array[s:e]
```

### Output

```text
Enter range: 1:4

Sliced Array:
[20 30 40]
```

---

## 4️⃣ Mathematical Operations

### Addition

```python
result = self.array + second
```

Output

```text
Result of Addition:
[11 22 33 44 55]
```

### Multiplication

```python
result = self.array * second
```

Output

```text
Result of Multiplication:
[10 40 90 160 250]
```

---

## 5️⃣ Dot Product

```python
result = np.dot(self.array, second)
```

Output

```text
Dot Product:
32
```

---

## 6️⃣ Matrix Multiplication

```python
result = self.array @ second
```

Output

```text
Matrix Multiplication Result:

[[19 22]
 [43 50]]
```

---

## 7️⃣ Combine Arrays

```python
result = np.vstack((self.array, second))
```

Output

```text
Combined Array:

[[1 2]
 [3 4]
 [5 6]
 [7 8]]
```

---

## 8️⃣ Split Arrays

```python
result = np.vsplit(self.array, sections)
```

Output

```text
Part 1
[[1 2]]

Part 2
[[3 4]]
```

---

## 9️⃣ Search Value

```python
positions = np.argwhere(self.array == value)
```

Output

```text
20 found at index:
[[1]]
```

---

## 🔟 Sort Array

```python
result = np.sort(self.array)
```

Output

```text
Sorted Array:
[10 20 30 40 50]
```

---

## 1️⃣1️⃣ Filter Values

```python
mask = self.array > value
print(self.array[mask])
```

Output

```text
Filtered Values:
[40 50]
```

---

## 1️⃣2️⃣ Statistics

```python
np.sum(self.array)
np.mean(self.array)
np.median(self.array)
np.std(self.array)
np.var(self.array)
```

Output

```text
Sum : 150
Mean : 30
Median : 30
Standard Deviation : 14.14
Variance : 200
```

---

## 1️⃣3️⃣ Percentile

```python
np.percentile(self.array,50)
```

Output

```text
50th Percentile : 30
```

---

## 1️⃣4️⃣ Correlation Coefficient

```python
corr = np.corrcoef(first_flat, second)[0,1]
```

Output

```text
Correlation Coefficient:
0.98
```

---

# 📊 Sample Complete Output

```text
==========================================
            NUMPY ANALYZER
==========================================

Enter Choice : 1

Select Array Type
1. 1D Array

Enter Elements : 10 20 30 40 50

Array created successfully:
[10 20 30 40 50]
```

---

# 🎯 Workflow

```text
START
   │
   ▼
Create NumPy Array
   │
   ├── Indexing & Slicing
   ├── Math Operations
   ├── Combine / Split
   ├── Search / Sort / Filter
   ├── Statistics
   └── Exit
```

---

# 📦 Python Concepts Used

* ✅ NumPy Arrays
* ✅ Object-Oriented Programming (Class & Methods)
* ✅ Static Method
* ✅ Class Method
* ✅ Private Methods
* ✅ Matrix Operations
* ✅ Statistical Functions
* ✅ Menu Driven Program

---

# 🎓 Viva Questions

| Question                         | Answer                                             |
| -------------------------------- | -------------------------------------------------- |
| NumPy kya hai?                   | Python library for numerical computing and arrays. |
| 1D Array kya hota hai?           | Single-dimensional array.                          |
| `reshape()` ka use?              | Array ka shape change karne ke liye.               |
| `np.dot()` kya karta hai?        | Dot product calculate karta hai.                   |
| `np.vstack()` kya karta hai?     | Arrays ko vertically combine karta hai.            |
| `np.mean()` kya karta hai?       | Average value calculate karta hai.                 |
| `np.percentile()` kya karta hai? | Given percentile calculate karta hai.              |

---

# ⭐ Project Highlights

* 📊 1D, 2D & 3D Array Analyzer.
* 🔢 Matrix Multiplication.
* 🔍 Search, Sort & Filter.
* 📈 Complete Statistics Dashboard.
* 🐍 Python NumPy Practical Project.

---

# 🙏 Thank You

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,100:6A5ACD&height=150&section=footer&animation=twinkling"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&pause=1000&color=F7971E&center=true&width=700&lines=✨+Thank+You+for+Visiting!;🐍+Happy+Coding+with+Python!;📊+Created+by+Shukla+Arpit"/>
</p>

<h3 align="center">👨‍💻 Created with ❤️ by Shukla Arpit</h3>


