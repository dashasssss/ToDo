# ToDo App — React + TypeScript

This is a Todo Application built with React, TypeScript, and Vite, following best practices in component structure, code style, and UI logic.
The project allows users to create, edit, filter, and manage their tasks, and synchronizes data with a remote API.

## 🚀 Demo

Live Demo: https://dashasssss.github.io/ToDo/

## 📌 Features
- Add new todos
- Delete todos
- Edit todo titles
- Mark todos as completed
- Filter by:
  - All
  - Active
  - Completed
- Clear completed tasks
- Toggle all tasks at once
- Smooth UI transitions
- Error notifications for API issues
- Fully responsive layout
- Data sync with remote API (`/todos` endpoint)


## 🛠️ Tech Stack
- React
- TypeScript
- Vite
- React Transition Group
- Classnames
- ESLint + Prettier
- REST API integration


## 🌐 API Information

This project uses the Mate Academy Todos API:

GET /todos
POST /todos
PATCH /todos/:id
DELETE /todos/:id


The `fetchClient.ts` utility handles:
- base URL
- request methods
- error response handling


## 📦 Installation and Setup

Clone the repository:
git clone https://github.com/dashasssss/ToDo.git
cd ToDo


Install dependencies:
npm install


Start the development server:
npm start


## 📘 Notes

- Project was rebuilt cleanly using the React + TypeScript Starter template.
- All unnecessary comments and Mate Academy instructions were removed.
- The project includes:
  - Type safety
  - Centralized API helpers
  - Consistent naming conventions
  - SCSS structure split into logical files
- Error handling and UI transitions are implemented for a smoother user experience.
