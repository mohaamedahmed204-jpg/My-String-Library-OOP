# 📌 Project 8: String Library (OOP)

##🚀 Project Overview

This project was implemented as part of Course 10 in the Programming Advices Track by Dr. Mohamed Abouhadhood.  

The main idea is to reuse all the string-related functions we built earlier in Course 7 – Algorithms & Problem Solving Level 3, but instead of rewriting them, we collected them inside a separate header file (clsString.h) and wrapped them in a class to apply Object-Oriented Programming (OOP) principles.

## 📖 Table of Contents
- [Project Overview]
- [Features]
- [Concepts Applied]
- [Project Structure]
- [Example Usage]
- [Example Output]
- [Future Improvements]
- [Learning Source]

---

## 🚀 Project Overview
This project was implemented as part of **Course 10** in the [Programming Advices](https://www.programmingadvices.com) Track by Dr. Mohamed Abouhadhood.

The main idea is to reuse all the string-related functions we built earlier in **Course 7 – Algorithms & Problem Solving Level 3**, but instead of rewriting them, we collected them inside a separate header file (`clsString.h`) and wrapped them in a class to apply Object-Oriented Programming (OOP) principles.

---

## ✨ Features
- ✅ **Reusability:** No need to rewrite string functions; they are all encapsulated in one class.
- ✅ **Encapsulation:** The internal implementation of each function is hidden, so we can call methods directly on the object without worrying about their internal logic.
- ✅ **Static Functions:** Functions can be used directly without creating an object.
- ✅ **Overloading:** We created overloaded functions – one that takes parameters and another that works directly on the object's value. This makes updates easy: if we modify a function, all dependent functions benefit automatically.
- ✅ **Flexibility:** Developers can either use class objects or call the static functions directly.

---

## 🧠 Concepts Applied
- Code Reusability
- Clean Code Practices
- Algorithm Implementation

---

## 📁 Project Structure

```text
Project-8-String-Library-OOP
|
├── clsString.h
|   String utility class containing all string operations
|
└── main.cpp
    Example program demonstrating how to use the library
```
---

## 🛠️ Future Improvements

Add more advanced string manipulation algorithms.
Integrate with file handling for real-world string processing.

## 🎓 Learning Source

This project was implemented while following the Programming Advices Roadmap.

Instructor:
Dr. Mohammed Abu-Hadhoud

The project demonstrates how to convert algorithm-based code into clean and reusable object-oriented libraries.
