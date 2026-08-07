<div align="center">

# 🧮 Algorithmic Challenges in C++

### A hand-built collection of classic algorithm & data-structure problems, solved from scratch in modern C++

[![C++](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://github.com/Aditya152602/algorithmic-challenges-cpp)
[![License](https://img.shields.io/github/license/Aditya152602/algorithmic-challenges-cpp?style=for-the-badge&color=blue)](https://github.com/Aditya152602/algorithmic-challenges-cpp/blob/main/LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/Aditya152602/algorithmic-challenges-cpp?style=for-the-badge&color=success)](https://github.com/Aditya152602/algorithmic-challenges-cpp/commits/main)
[![Stars](https://img.shields.io/github/stars/Aditya152602/algorithmic-challenges-cpp?style=for-the-badge&color=yellow)](https://github.com/Aditya152602/algorithmic-challenges-cpp/stargazers)
[![Issues](https://img.shields.io/github/issues/Aditya152602/algorithmic-challenges-cpp?style=for-the-badge&color=red)](https://github.com/Aditya152602/algorithmic-challenges-cpp/issues)

![Problems Solved](https://img.shields.io/badge/Problems_Solved-44%2B-success?style=flat-square)
![Topics](https://img.shields.io/badge/Topics-10-blueviolet?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)

</div>

---

## 📖 Table of Contents

- [About](#-about)
- [Topics Covered](#-topics-covered)
- [Repository Structure](#-repository-structure)
- [Problem Index](#-problem-index)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 📌 About

**`algorithmic-challenges-cpp`** is a growing, self-maintained library of classic algorithm and data-structure problems — the kind you'd meet in coding interviews, competitive programming, or any solid DSA course — each implemented from scratch in clean, readable C++.

- 🔥 **44+ problems** solved across **10 core DSA topics**
- 🧠 Every problem lives in its own self-contained folder
- ⚡ No dependencies, no build system — just a compiler and you're running
- 📈 Actively updated with new problems and refinements

Whether you're brushing up before interviews, learning C++, or just enjoy solving algorithms for fun, this repo is meant to be a clear, browsable reference.

---

## 🧩 Topics Covered

`Sorting` · `Searching` · `Math & Number Theory` · `Arrays & Two Pointers` · `Strings` · `Dynamic Programming` · `Linked List` · `Trees & Graphs` · `Stack` · `Design / Data Structures`

---

## 📂 Repository Structure

Every problem lives in its own top-level folder with a self-contained `.cpp` solution — there are no nested topic subfolders in the repo itself. The **[Problem Index](#-problem-index)** below groups everything by topic purely for readability.

```
algorithmic-challenges-cpp/
├── Armstrong Number/
├── Best Time to Buy & Sell Stock/
├── Binary Search/
├── Bubble Sort/
├── Coin Change (1D Dynamic Programming)/
├── ...
├── Valid Anagram/
├── Valid Parentheses/
└── README.md
```

---

## 📚 Problem Index

### 🔢 Sorting Algorithms

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Bubble Sort](./Bubble%20Sort) | Easy | O(n²) | O(1) |
| [Insertion Sort](./Insertion%20Sort) | Easy | O(n²) | O(1) |
| [Selection Sort](./Selection%20Sort) | Easy | O(n²) | O(1) |

### 🔍 Searching

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Binary Search](./Binary%20Search) | Easy | O(log n) | O(1) |

### ➗ Math & Number Theory

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Armstrong Number](./Armstrong%20Number) | Easy | O(d) | O(1) |
| [Count Digits](./Count%20Digits) | Easy | O(log n) | O(1) |
| [Factorial](./Factorial) | Easy | O(n) | O(1) |
| [Fibonacci Number](./Fibonacci%20Number) | Easy | O(n) | O(1) |
| [GCD (Euclidean Algorithm)](./GCD%20(Euclidean%20Algorithm)) | Easy | O(log(min(a,b))) | O(1) |
| [LCM](./LCM) | Easy | O(log(min(a,b))) | O(1) |
| [Prime Number](./Prime%20Number) | Easy | O(√n) | O(1) |
| [Reverse Integer](./Reverse%20Integer) | Medium | O(log n) | O(1) |

### 🧮 Arrays & Two Pointers

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Two Sum](./Two%20Sum) | Easy | O(n) | O(n) |
| [Best Time to Buy & Sell Stock](./Best%20Time%20to%20Buy%20&%20Sell%20Stock) | Easy | O(n) | O(1) |
| [Majority Element](./Majority%20Element) | Easy | O(n) | O(1) |
| [Merge Two Sorted Arrays](./Merge%20Two%20Sorted%20Arrays) | Easy | O(m+n) | O(1) |
| [Missing Number](./Missing%20Number) | Easy | O(n) | O(1) |
| [Move Zeroes](./Move%20Zeroes) | Easy | O(n) | O(1) |
| [Remove Duplicates from Sorted Array](./Remove%20Duplicates%20from%20Sorted%20Array) | Easy | O(n) | O(1) |
| [Merge Intervals](./Merge%20Intervals) | Medium | O(n log n) | O(n) |
| [Next Permutation](./Next%20Permutation) | Medium | O(n) | O(1) |
| [Product of Array Except Self](./Product%20of%20Array%20Except%20Self) | Medium | O(n) | O(1)* |
| [Rotate Array](./Rotate%20Array) | Medium | O(n) | O(1) |
| [Trapping Rain Water](./Trapping%20Rain%20Water) | Hard | O(n) | O(1) |

<sub>* excluding the output array</sub>

### 🔤 Strings

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Valid Anagram](./Valid%20Anagram) | Easy | O(n) | O(1) |
| [Palindrome String](./Palindrome%20String) | Easy | O(n) | O(1) |
| [Reverse a String](./Reverse%20a%20String) | Easy | O(n) | O(1) |
| [Longest Common Prefix](./Longest%20Common%20Prefix) | Easy | O(S) | O(1) |
| [Reverse Words](./Reverse%20Words) | Medium | O(n) | O(n) |
| [Longest Substring Without Repeating Characters](./Longest%20Substring%20Without%20Repeating%20Characters) | Medium | O(n) | O(min(n,m)) |
| [Group Anagrams](./Group%20Anagrams) | Medium | O(n·k log k) | O(n·k) |
| [String Compression](./String%20Compression) | Medium | O(n) | O(1) |
| [KMP Pattern Matching](./KMP%20Pattern%20Matching) | Hard | O(n+m) | O(m) |

### 🧠 Dynamic Programming

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Maximum Subarray (Kadane's Algorithm)](./Maximum%20Subarray%20(Kadane's%20Algorithm)) | Medium | O(n) | O(1) |
| [Longest Palindromic Substring](./Longest%20Palindromic%20Substring) | Medium | O(n²) | O(1) |
| [Longest Common Subsequence](./Longest%20Common%20Subsequence) | Medium | O(m×n) | O(m×n) |
| [Coin Change (1D Dynamic Programming)](./Coin%20Change%20(1D%20Dynamic%20Programming)) | Medium | O(n×amount) | O(amount) |
| [Minimum Path Sum](./Minimum%20Path%20Sum) | Medium | O(m×n) | O(m×n) |
| [Unique Paths (2D Grid DP)](./Unique%20Paths%20(2D%20Grid%20DP)) | Medium | O(m×n) | O(m×n) |

### 🔗 Linked List

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Reverse a Linked List](./Reverse%20a%20Linked%20List) | Easy | O(n) | O(1) |

### 🌳 Trees & Graphs

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Lowest Common Ancestor](./Lowest%20Common%20Ancestor) | Medium | O(n) | O(h) |
| [Number of Islands](./Number%20of%20Islands) | Medium | O(m×n) | O(m×n) |

### 📦 Stack

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [Valid Parentheses](./Valid%20Parentheses) | Easy | O(n) | O(n) |

### 🗃️ Design & Data Structures

| Problem | Difficulty | Time | Space |
|:---|:---:|:---:|:---:|
| [LRU Cache](./LRU%20Cache) | Medium | O(1) get/put | O(capacity) |

---

## 🚀 Getting Started

### Prerequisites
- A C++ compiler — GCC (`g++`), Clang, or MSVC
- C++11 or later
- `git`, to clone the repo

### Clone & Run

```bash
# 1. Clone the repository
git clone https://github.com/Aditya152602/algorithmic-challenges-cpp.git
cd algorithmic-challenges-cpp

# 2. Jump into any problem folder
cd "Two Sum"

# 3. Compile
g++ -std=c++17 -O2 -o solution *.cpp

# 4. Run
./solution
```

That's it — no build system, no external dependencies, just plain C++.

---

## 🤝 Contributing

New problems, cleaner approaches, extra edge cases, and better comments are all welcome.

1. **Fork** the repository
2. **Create a branch** — `git checkout -b add/problem-name`
3. **Add your solution** in a clearly named folder, one problem per folder
4. **Commit** — `git commit -m "Add: <Problem Name>"`
5. **Push** — `git push origin add/problem-name`
6. **Open a Pull Request**

Please keep code clean, commented, and consistent with the existing style.

---

## 📄 License

Check the repository's [LICENSE](https://github.com/Aditya152602/algorithmic-challenges-cpp/blob/main/LICENSE) file for current terms. If one hasn't been added yet, the [MIT License](https://choosealicense.com/licenses/mit/) is a popular, permissive choice for a learning repo like this — it lets others freely learn from, use, and build on the code.

---

## 👤 Author

**Aditya152602**

[![GitHub](https://img.shields.io/badge/GitHub-Aditya152602-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Aditya152602)

<div align="center">

⭐ **If this repository helped you, consider giving it a star!** ⭐

</div>
