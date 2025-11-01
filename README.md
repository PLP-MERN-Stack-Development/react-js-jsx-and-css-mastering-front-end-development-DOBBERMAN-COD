# React Task Manager

A modern React application built with Vite and Tailwind CSS for managing tasks. This project demonstrates the use of React hooks, context API, and external API integration.

## Features

- ✅ Task listing with pagination
- ✅ Add new tasks
- ✅ Mark tasks as completed/incomplete
- ✅ Delete tasks
- ✅ Filter tasks (All, Pending, Completed)
- ✅ Search tasks by title
- ✅ Responsive design with Tailwind CSS
- ✅ Loading states and error handling

## Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **JSONPlaceholder API** - Mock API for tasks

## Project Structure

```
src/
├── components/       # Reusable UI components
│   ├── Button.jsx    # Reusable button component
│   └── TaskManager.jsx # Main task management component
├── pages/           # Page components
│   └── Home.jsx     # Home page
├── hooks/           # Custom React hooks
│   └── useTasks.js  # Task management hook
├── context/         # React context providers
│   └── TaskContext.jsx # Global task state
├── api/             # API integration functions
│   └── tasks.js     # Task API functions
├── utils/           # Utility functions
│   └── helpers.js   # Helper functions
├── App.jsx          # Main application component
├── main.jsx         # Application entry point
└── index.css        # Global styles
```

## Getting Started

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd react-task-manager
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## API Integration

The app integrates with [JSONPlaceholder](https://jsonplaceholder.typicode.com/) API for task data:

- `GET /todos` - Fetch tasks
- `POST /todos` - Add new task
- `PATCH /todos/:id` - Update task
- `DELETE /todos/:id` - Delete task

## Component Architecture

### Button Component

A flexible button component with variants (primary, secondary, danger) and sizes (small, medium, large).

### TaskManager Component

The main component handling task display, filtering, searching, and CRUD operations.

### useTasks Hook

Custom hook managing task state, API calls, and error handling.

### TaskContext

React context for global task state management.

## Styling

The application uses Tailwind CSS for styling with:

- Responsive design
- Hover states and transitions
- Consistent color scheme
- Accessible focus states

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License.
