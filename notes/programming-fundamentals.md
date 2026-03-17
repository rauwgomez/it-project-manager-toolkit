# Programming Foundations & Workshop (TI1400 / TI1401) — Technical Portfolio Notes

This documentation serves as a technical portfolio of the programming foundations and computational logic developed at **Tecnológico de Costa Rica (TEC)**. It tracks progression from structured problem-solving to advanced implementation in **Python**, with emphasis on **algorithmic efficiency** and **system-level security**.

## Table of Contents
1. [Logic & Problem-Solving Methodology](#1-logic--problem-solving-methodology)
2. [Software Development (Python)](#2-software-development-python)
3. [Algorithmic Efficiency & Numerical Methods](#3-algorithmic-efficiency--numerical-methods)
4. [Cybersecurity & Systems Architecture](#4-cybersecurity--systems-architecture)
5. [Major Technical Projects](#5-major-technical-projects)
6. [Personal Reflection & Lessons Learned](#6-personal-reflection--lessons-learned)

---

## 1. Logic & Problem-Solving Methodology

Technical solutions are built using the **George Pólya Strategy**, ensuring code is a direct reflection of a well-understood logical model.

### The Pólya Approach
- **Understanding:** Explicit definition of **Inputs** (E), **Outputs** (S), and **Restrictions** (R).
- **Modeling:** Design algorithmic logic via **pseudocode** or **UML** before writing code.
- **Verification:** Use **desk checks** (*corridas manuales*) to validate logic against edge cases (e.g., leap years, boundary values).

### Visual Modeling (UML)
- **Activity diagrams:** Model dynamic system behavior, including complex branching and iterative cycles.
- **Business logic:** Applied UML standards to model real-world scenarios such as:
  - Insurance premium calculators
  - Automated toll systems
  - ATM workflows

---

## 2. Software Development (Python)

Progressed from basic sequential scripts to modular, multi-file applications and automated tools.

### Programming Paradigms
- **Control structures:** Sequential, selection (simple, double, nested), and iterative logic (`while`, `for`).
- **Modular programming:** Separation of responsibilities using user-defined and helper functions.
- **Recursion:** Stack-based recursive logic for sequences (Ulam, Fibonacci) and data operations (Cartesian products).

### Data Structures
- **Linear structures:** Stacks (LIFO) and queues (FIFO).
- **Python collections:**
  - **Dictionaries:** Managed complex datasets for invoicing systems and contact agendas.
  - **Matrices (2D arrays):** Built dynamic grid generators with randomized placement and recursive overlap prevention (e.g., word search / *sopa de letras*).
  - **Tuples & sets:** Used to optimize search performance and improve data integrity.

---

## 3. Algorithmic Efficiency & Numerical Methods

Focused on computational performance and mathematical precision.

- **Search algorithms:** Implemented and compared:
  - Linear search: `O(n)`
  - Binary search: `O(log n)`
- **Numerical methods:**
  - **Newton–Raphson:** Approximated square roots with high precision (tolerance `0.0001`).
  - **Russian peasant multiplication:** Implemented binary-based multiplication logic.

---

## 4. Cybersecurity & Systems Architecture

Applied programming skills to implement cryptographic protocols and study system fundamentals.

### Cryptography
- **Asymmetric encryption (RSA):**
  - Built a functional RSA suite including:
    - prime generation (Sieve of Eratosthenes / *Criba de Eratóstenes*)
    - modular exponentiation
    - key-pair management
- **Symmetric encryption:**
  - Experimental implementations using **AES** and **3DES**.

### Operating Systems (OS)
Research topics included:
- Kernel operations
- Memory management
- File system protection
- Historical evolution of Unix (including governance by **The Open Group**)

---

## 5. Major Technical Projects

| Project | Technology | Core Competency |
|---|---|---|
| RSA Security Suite | Python (Math/RSA) | Cryptographic key management and modular arithmetic |
| Word Search Generator | Python (Matrices/Tkinter) | Recursive matrix manipulation + GUI development |
| Administrative Logic Tools | Python (Logic) | Translating fiscal, tax, and insurance rules into code |
| Email Automation System | Python (SMTP/AES) | Secure reporting with automated communication layers |
| Efficiency Testing Suite | Python (Algorithms) | Comparing search complexity and recursion patterns |

---

## 6. Personal Reflection & Lessons Learned

These courses fundamentally changed how I think about the software I interact with day to day. Struggling to implement early functions built an appreciation for how complex and intentional real systems are.

### Final lessons learned
- **Logic before syntax:** A well-modeled algorithm (UML/pseudocode) makes coding faster and reduces errors.
- **The cost of efficiency:** Understanding `O(n)` vs `O(log n)` showed scalability is a design choice.
- **Security as a foundation:** Implementing RSA and AES reinforced that security is not an add-on—it’s often a mathematical property of the implementation.
- **The power of simplicity:** Mastery of fundamentals enables reliable, complex system integrations.
