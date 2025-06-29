# To-Do App with React

This is a classic "To-Do App" web application built with the React library. This project demonstrates core React concepts such as state management, component-based architecture, event handling, and interaction with LocalStorage.

## Live Demo

Experience the live website: [To-Do App](https://manch0ffline.github.io/todo-app-react-project/)

# Project Description

This is an intuitive Single Page Application (SPA) that helps users keep track of their tasks. Users can add, edit, delete, and mark tasks as complete. All changes are saved in the browser's local storage, allowing users to access their to-do list even after closing the tab.


## Technologies Used

- React: The core library for building the user interface.
  - React Hooks (useState, useEffect): For managing component state and handling side effects (like syncing with LocalStorage).
- HTML5: For the basic structure of the application.
- SCSS3: For styling components and creating a clean, minimalist interface.
- FLEXBOX
- JS
- Web API: LocalStorage: To ensure data persistence on the client side.

## Features

1. Full CRUD Functionality: All essential operations are implemented:
  - Create: Add new tasks via an input field.
  - Read: Display the list of all tasks.
  - Update: Edit the text of existing tasks and mark them as complete.
  - Delete: Remove individual tasks.
2. Task Filtering: Users can filter tasks by three categories: "All," "Active," and "Completed."
3. Task Counter: The footer displays a count of the remaining active (uncompleted) tasks.
4. Clear Completed: A "Clear completed" button allows for the removal of all finished tasks at once.
5. Local Storage Persistence: The application's state (the list of tasks) is saved in LocalStorage, ensuring data persistence between sessions.
5. Component-Based Architecture: The application is built with reusable React components (TodoItem, Header, etc.).

## How to Run the Project Locally

To launch this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/manch0ffline/todo-app-react-project.git
    ```
2.  **Navigate into the project folder:**
    ```bash
    cd todo-app-react-project
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
4.  **Start the development server:**
    ```bash
    npm start
    ```
5.  **Open in browser:**
    The application will usually open automatically in your browser at `http://localhost:8080/`. If it doesn't, you can open it manually.
