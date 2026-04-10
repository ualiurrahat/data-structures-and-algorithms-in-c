# 📗 Data Structures and Algorithms in C

**A complete, well-structured reference repository covering core Data Structures and Algorithms implemented in C — written with clarity, clean code, and educational value in mind.**

[![Stars](https://img.shields.io/github/stars/ualiurrahat/DSA-using-C-programming?style=for-the-badge&color=f4c430&labelColor=1a1a2e)](https://github.com/ualiurrahat/DSA-using-C-programming/stargazers)
[![Language](https://img.shields.io/badge/Language-C-00599C?style=for-the-badge&logo=c&logoColor=white&labelColor=1a1a2e)](https://en.wikipedia.org/wiki/C_(programming_language))
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&labelColor=1a1a2e)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge&labelColor=1a1a2e)](https://github.com/ualiurrahat/DSA-using-C-programming)

> *"C is quirky, flawed, and an enormous success."* — Dennis Ritchie

**⭐ If this repository helped you understand DSA in C, please give it a star — it helps others find it too!**

---

## 📖 About This Repository

This repository contains clean, well-commented implementations of all fundamental **Data Structures and Algorithms** written in **C**. Every implementation is designed to be readable, self-contained, and educational — making it ideal for university students, interview preparation, and anyone building a solid systems-level programming foundation.

C is the language closest to how computers actually work. Understanding DSA in C means understanding DSA at its deepest level — no abstractions, no hidden memory management, just raw logic and performance.

---

## 🗂️ Repository Structure & Coverage
```
data-structures-and-algorithms-in-c/
│
├── 01. Searching Techniques/
│   ├── 1_linear_search.c          ← Sequential search — O(n)
│   └── 2_binary_search.c          ← Divide and conquer search — O(log n)
│
├── 02. Sorting Algorithms/
│   ├── 1_selection_sort.c         ← O(n²) — repeated minimum selection
│   ├── 2_bubble_sort.c            ← O(n²) — adjacent swapping
│   ├── 3_insertion_sort.c         ← O(n²) — build sorted array one item at a time
│   ├── 4_merge_sort.c             ← O(n log n) — divide and conquer
│   ├── 5_quick_sort.c             ← O(n log n) avg — pivot-based partitioning
│   └── 6_count_sort.c             ← O(n+k) — non-comparison integer sort
│
├── 03. Stacks & Queues/
│   ├── 1_stack.c                  ← Push, pop, peek — LIFO structure
│   ├── 2_balanced_parenthesis.c   ← Classic stack application
│   ├── 3_balanced_parenthesis.c   ← Extended variant
│   └── 4_queue.c                  ← Enqueue, dequeue — FIFO structure
│
├── 04. Linked List/
│   ├── 1_linked_list.c            ← Singly linked list — insert, delete, traverse
│   └── 2_doubly_linked_list.c     ← Doubly linked list — bidirectional traversal
│
├── 05. Tree Data Structure/
│   ├── 1_treeDS.c                 ← Binary tree — construction and traversals
│   └── 2_BST.c                    ← Binary Search Tree — insert, search, delete
│
├── heap.c                         ← Binary heap — heapify and heap sort
└── priority_queue.c               ← Priority queue using binary heap
```
---

## 📊 Topics Covered At a Glance

| # | Topic | Implementations | Key Concepts |
|---|---|---|---|
| 01 | Searching Techniques | 2 | Linear Search, Binary Search |
| 02 | Sorting Algorithms | 6 | Selection, Bubble, Insertion, Merge, Quick, Count Sort |
| 03 | Stacks & Queues | 4 | LIFO, FIFO, Balanced Parenthesis |
| 04 | Linked List | 2 | Singly LL, Doubly LL |
| 05 | Tree Data Structure | 2 | Binary Tree Traversals, BST |
| — | Heap | 1 | Binary Heap, Heap Sort |
| — | Priority Queue | 1 | Heap-based Priority Queue |

**Total: 18 implementations · 7 topic areas · 100% C**

---

## ✨ What Makes This Repository Useful?

- ✅ **Pure C** — no external libraries, no shortcuts — every line is raw, systems-level code
- ✅ **Clearly named files** — file names describe exactly what's inside, no guessing
- ✅ **Beginner-friendly** — well-commented code explaining the logic, not just the syntax
- ✅ **Interview-ready** — covers all the fundamental DSA topics asked in technical interviews
- ✅ **Complexity awareness** — each algorithm implemented with an understanding of time and space trade-offs
- ✅ **Standalone files** — every `.c` file runs independently, no dependencies between files

---

## 🚀 How to Use This Repository

### Clone the Repository

```bash
git clone https://github.com/ualiurrahat/DSA-using-C-programming.git
cd DSA-using-C-programming
```

### Compile and Run Any File

```bash
# Using GCC
gcc filename.c -o output
./output
```

### Recommended Learning Order
```
Step 1 — Searching Techniques   (understand how we find elements)
Step 2 — Sorting Algorithms     (understand how we order elements)
Step 3 — Linked List            (understand dynamic memory and pointers)
Step 4 — Stacks & Queues        (understand linear access-controlled structures)
Step 5 — Tree Data Structure    (understand hierarchical structures and BST)
Step 6 — Heap & Priority Queue  (understand priority-based structures)
```
### Recommended Setup

- **Compiler:** GCC (Linux/macOS) or MinGW (Windows)
- **IDE:** VS Code with C/C++ Extension, or Code::Blocks
- **Standard:** C99 or later (`gcc -std=c99 filename.c -o output`)

---

## 👤 About the Author
```
Md. Ualiur Rahman Rahat
B.Sc. EEE — Gopalganj Science and Technology University
B.Sc. Computer Science (in progress) — University of the People (CGPA: 3.73)
```

I built this repository as part of my journey to master systems-level programming and DSA fundamentals in C — the language that sits closest to the hardware. Combined with my [Complete DSA in C++](https://github.com/ualiurrahat/complete-data-structure-and-algorithms-using-cpp) repository, this forms a comprehensive low-level programming reference I'm proud to share.

[![GitHub](https://img.shields.io/badge/GitHub-ualiurrahat-181717?style=for-the-badge&logo=github)](https://github.com/ualiurrahat)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/ualiurrahat)

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE) — free to use, share, and build upon with attribution.

---

**⭐ Found this helpful? A star takes 2 seconds and means everything — thank you!**

*Written in C, the language that built the modern world.*
