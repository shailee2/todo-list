# React To-Do List Web Application

A modern and minimalist **To-Do List** app built with **React.js**, featuring clean UI and full task lifecycle management. Users can add tasks, mark them as completed, and delete them—all with real-time updates using React state and props.

---

## Overview

This app demonstrates the use of:

- Functional Components
- React Hooks (`useState`)
- Component-based architecture
- Controlled form inputs
- Dynamic rendering with real-time updates

---

## Demo

> Live Demo Coming Soon 

---

## Technologies Used

- **React.js** (Functional components, hooks)
- **JavaScript (ES6+)**
- **HTML5 & CSS3**
- **npm & Create React App**

---

## Features

Add new tasks  
Delete existing tasks  
Toggle task completion  
Real-time updates with local state  
Modular components  
Clean UI and styling (extendable)

---

## Project Structure

todo-list/

├── public/

├── src/

│ ├── components/

│ │ ├── TodoItem.js # Individual task item

│ │ └── TodoList.js # Manages task state and input

│ ├── App.js

│ ├── index.js

│ └── App.css

├── package.json

└── README.md


---

## Component Architecture

### `TodoList.js`

Handles the application’s core state (`tasks`) and form input. Provides:

- `addTask()` for creating new items
- `deleteTask()` for removing items
- `toggleCompleted()` to toggle completion state


### `TodoItem.js`

- Receives a task prop and renders:
- A checkbox (to toggle completion)
- The task text
- A delete button

##  What I Learned
- How to manage local state with useState
- Building modular, reusable React components
- Handling user input with controlled form elements
- Functional patterns in React development
- Clean UI logic and separation of concerns

## Future Enhancements
- Add persistent storage with localStorage or Firebase
- Add due dates and calendar view
- Improved styling and animations
- Mobile-first responsive design
- Task statistics or progress bar

## Author
Shailee Patel <br>
Email: shaileepatel05@gmail.com <br>
LinkedIn: linkedin.com/in/shailee-patel-04481b285<br>
GitHub: github.com/shailee2

