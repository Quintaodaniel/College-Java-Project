# 📚 College Java Project: Library Management System

> **Status:** Completed (4 Evolutionary Stages)

This repository documents the development of a **Library Management System**, created as a progressive academic project.

The code is organized into 4 distinct folders (`P1n` to `P4n`), demonstrating the **technical evolution** from basic syntax to a full Graphical User Interface (GUI) application with custom exception handling.

---

## 📂 Evolution Roadmap

Here is how the project evolved through the semesters/stages:

### 🔹 P1n - Foundations & Validation
**Focus:** Basic Logic, Inheritance & Validation.
* Creation of the base `Pessoa` (Person) class and its subclasses `Homem` (Man) and `Mulher` (Woman).
* Implementation of static validation utilities:
  * `ValidaCPF`: Algorithms to verify Brazilian ID format.
  * `ValidaData`: Logic to handle and validate dates.

### 🔶 P2n - Abstraction & Sorting
**Focus:** Interfaces, Abstract Classes & Algorithms.
* Introduction of **Abstract Classes** and **Polymorphism**.
* **Key Feature:** Implementation of `PessoaIMC` to calculate Body Mass Index.
* **Data Structures:** Custom sorting logic using Interfaces (`MinhaListaOrdenavel`) to organize objects in memory.

### 🔷 P3n - Library System (Backend)
**Focus:** Object Association & Business Logic.
* The complete backend logic for the Library System.
* Organization of code into packages (`lp2g04`).
* Management of core entities: Books, Users, and Loans.

### ✅ P4n - Final Version (GUI & Exceptions)
**Focus:** User Interface & Robustness.
* **Graphical User Interface (GUI):** Visual layer for the system developed in `P3n`.
* **Custom Exceptions:** Handling specific business errors (e.g., `CopiaNaoDisponivelEx`, `UsuarioNaoCadastradoEx`).
* Full integration of lending logic (`Emprest.java`).

---

## 🛠️ Project Structure

```text
Repo Root
│
├── P1n/  (Basic Logic & Validation)
├── P2n/  (Sorting & Abstract Classes - IMC)
├── P3n/  (Library Core Logic)
└── P4n/  (Final App with GUI)  