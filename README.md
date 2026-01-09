# 🧪 TDD-BDD Final Project

This repository is the final project for the **Introduction to Test-Driven Development (TDD) and Behavior-Driven Development (BDD)** course.  
It demonstrates how to build a REST API service using TDD and BDD techniques, writing tests before the code and defining behavior with feature scenarios.:contentReference[oaicite:1]{index=1}

---

## 📘 Overview

This project contains:

- A **Flask REST API** for managing products
- **Unit tests** implemented using Pytest (TDD)
- **Behavior-driven tests** written in Gherkin syntax (BDD) using `behave`
- **Selenium** based UI tests to simulate user behavior
- Docker and setup scripts for development and testing

The primary goal is to practice *test first* development and to ensure proper test coverage through TDD and BDD approaches.:contentReference[oaicite:2]{index=2}

---

## 🚀 Features

✔️ Create, Read, Update, Delete (CRUD) endpoints for products  
✔️ Pytest test suites for models and routes  
✔️ Gherkin feature files describing behavior scenarios  
✔️ Automated BDD steps to test behavior through the UI  
✔️ Test automation integrated with Docker  

---

## 📁 Repository Structure
├── bin/
├── features/
│ ├── products.feature
│ └── steps/
├── service/
│ ├── models.py
│ └── routes.py
├── tests/
│ ├── test_models.py
│ └── test_routes.py
├── Dockerfile
├── Makefile
├── requirements.txt
├── .gitignore
└── README.md
