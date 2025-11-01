# Week 3 Assignment: React Task Manager with Vite and Tailwind CSS

## Objective

Build a React application that manages tasks using modern React patterns, including hooks, context, and external API integration. The app should be styled with Tailwind CSS and built with Vite for fast development.

## Requirements

### 1. Project Setup

- Set up a React project using Vite
- Configure Tailwind CSS for styling
- Ensure the project structure matches the provided layout

### 2. Reusable UI Components

- Create a `Button` component that accepts props for variant, size, and onClick handler
- Create a `TaskManager` component that displays and manages tasks

### 3. State Management

- Implement a custom hook `useTasks` for managing task state
- Use React Context (`TaskContext`) for global state management
- Handle loading states and errors

### 4. API Integration

- Integrate with JSONPlaceholder API to fetch tasks: `https://jsonplaceholder.typicode.com/todos`
- Implement functions to fetch, add, update, and delete tasks
- Handle API errors gracefully

### 5. Styling

- Use Tailwind CSS for all styling
- Ensure responsive design
- Implement hover states and transitions

## Project Structure

```
src/
├── components/       # Reusable UI components
├── pages/           # Page components
├── hooks/           # Custom React hooks
├── context/         # React context providers
├── api/             # API integration functions
├── utils/           # Utility functions
└── App.jsx          # Main application component
```

## Features to Implement

- Display a list of tasks fetched from the API
- Add new tasks
- Mark tasks as completed
- Delete tasks
- Filter tasks by status (all, completed, pending)
- Search tasks by title

## Bonus Features

- Pagination for large task lists
- Task categories/tags
- Due dates for tasks
- Local storage persistence

## Submission

- Ensure all code is well-commented
- Follow React best practices
- Test the application thoroughly
- Provide a README with setup instructions
