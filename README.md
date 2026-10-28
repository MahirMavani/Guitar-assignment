# 🎸 Java Guitar Inventory Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Java](https://img.shields.io/badge/Java-17%2B-orange.svg)](https://www.oracle.com/java/)

> **A classic Object-Oriented Analysis & Design (OOAD) inventory search and specification matching system implemented in Java.**

---

## 📌 Features

- **Domain Model Encapsulation**: Implements `Guitar` model with serial number, builder, model name, wood type (back/top), and pricing.
- **Parametric Inventory Search**: `Inventory` class maintains the collection and performs client-spec query filtering to locate matching instruments.
- **Interactive CLI Harness**: `GuitarInventorySystem` provides a driver program demonstrating item cataloging and search queries.

---

## 📁 Repository Structure

```text
Guitar-assignment/
├── Guitar.java                # Entity model representing individual guitars
├── Inventory.java             # Repository holding the inventory list & search algorithm
├── GuitarInventorySystem.java # CLI driver with test catalog and search demonstration
├── LICENSE                    # MIT License
└── README.md                  # Project documentation
```

---

## 🚀 How to Run

```bash
# Compile all source files
javac *.java

# Execute main inventory system
java GuitarInventorySystem
```

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
