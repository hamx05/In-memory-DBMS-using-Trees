# DS-Assignment-02: Tree-Based In-Memory Database

This mini-project was developed for the **Data Structures** course in Fall 2024 (3rd semester at FAST-NUCES).  
It implements a memory-only database using three tree structures: **BST**, **AVL Tree**, and **B-Tree**.

---

## 📌 Overview

Each tree acts as a separate table supporting CRUD operations.

---

## ⚙️ Features

- **Insert**, **Search**, **Update**, and **Delete** in:
  - Binary Search Tree (BST)
  - AVL Tree
  - B-Tree

- **Performance Analysis**:
  - Compare average times on datasets of 1K, 10K, 50K records
  - Output in table/graph with observed vs expected complexity

- **Data Generator**:
  - Creates dummy datasets for benchmarking

---

## 🚀 How to Run
```bash
g++ inmemory_dbms.cpp bst.cpp avl.cpp btree.cpp -o inmemory_dbms
```
