# Programming Course

This repository contains exercises and projects from a programming course, organized into three modules.

## Structure

```
.
├── Module I/           # JavaScript fundamentals
│   ├── HOF, Callback and Object/
│   ├── String and Set/
│   ├── Date, Multiple Files/
│   ├── Conditional Structure/
│   ├── Loop Structure/
│   ├── Functions/
│   ├── Arithmetic Operations/
│   ├── Recursion/
│   ├── Arrays/
│   └── Arrays and Matrices/
├── Module II/          # Web development (HTML, CSS, API)
│   ├── HTML Exercise 1/
│   ├── HTML Exercise 2/
│   ├── CSS Exercise/
│   └── API Notebook Manager/
├── Module III/         # Object-Oriented Programming
│   └── POO Application Exercise/
└── WormGame/           # JavaScript game project
```

## Module I - JavaScript Fundamentals

Covers core JavaScript concepts:
- Higher-order functions, callbacks, and objects
- String and Set manipulation
- Date handling and multi-file modules
- Conditional and loop structures
- Functions and recursion
- Arrays and matrices operations

## Module II - Web Development

- **HTML exercises**: Semantic markup, forms, accessibility
- **CSS exercise**: Styling, layout, responsive design
- **API Notebook Manager**: REST API implementation with JavaScript modules

## Module III - Object-Oriented Programming

- Practical application of OOP concepts in JavaScript
- Classes, inheritance, encapsulation
- Design patterns

## WormGame

A classic Snake/Worm game implemented in vanilla JavaScript with:
- Game loop and rendering
- Collision detection
- Score tracking
- Modular architecture (Board, Food, Worm, Position classes)

## Getting Started

Open the HTML files in a browser to run the exercises. For the API Notebook Manager and WormGame, serve the directory with a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then navigate to `http://localhost:8000` in your browser.

## Author

Yann Carvalho <yanncarvalho@outlook.com>