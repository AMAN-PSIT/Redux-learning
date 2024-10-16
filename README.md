# Redux-learning
# Redux Counter with React and Vite

This project is a simple **Redux-based counter application** built with **React** and bundled using **Vite**. The application demonstrates the basic usage of Redux for state management, with actions to increment, decrement, and reset the counter.

## Features

- Increment, Decrement, and Reset counter functionality.
- Centralized state management using Redux.
- Easy to extend and maintain.
- Hot module replacement with Vite for fast development.

## Project Structure

├── src │ ├── actions │ │ └── counterActions.js # Action types and action creators │ ├── components │ │ └── Counter.jsx # Counter component (main UI) │ ├── reducers │ │ └── counterReducer.js # Reducer handling state updates │ ├── store.js # Redux store configuration │ ├── App.jsx # Main App component │ ├── main.jsx # Entry point, connects Redux store to app │ └── index.css # Global styles └── ...


## Getting Started

### Prerequisites

Ensure you have **Node.js** and **npm** installed. You can check if they are installed by running:

```bash
node -v
npm -v

**Technologies Used**
  React: A JavaScript library for building user interfaces.
  Redux: A predictable state container for JavaScript applications.
  Vite: A fast development build tool and bundler.
  JavaScript/JSX: Core language for building the application.

**How Redux Works in This Project**
  Actions: User interactions (e.g., clicking increment or decrement buttons) dispatch actions such as INCREMENT, DECREMENT, and RESET.
  Reducer: The counterReducer updates the state based on the dispatched action.
  Store: Redux maintains the state in a central store, allowing any component to access or update the counter's value.
  DevTools Integration
For debugging, the project supports the Redux DevTools Extension. You can inspect state changes and actions dispatched to the store by enabling the DevTools in your browser.
