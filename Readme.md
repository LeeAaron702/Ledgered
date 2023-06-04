# Ledgered
![Ledgered (online-video-cutter com)](https://github.com/LeeAaron702/Ledgered/assets/112150883/b328c8b4-a1c0-4e21-8f7f-e787217e7cdb)

Ledgered is a financial tracking application that provides an intuitive interface for tracking transactions, products, and key performance indicators (KPIs). This application is built with a robust technology stack known as MERN: MongoDB, Express, React, and Node.

## Features
Ledgered provides a range of features to support your financial tracking needs:

-Transaction Tracking: Keep track of all your financial transactions in one place. Ledgered provides a comprehensive interface for recording and viewing transactions.
-Product Tracking: Manage your products with ease. Ledgered allows you to record product details and monitor their status over time.
-KPI Tracking: Stay on top of your financial health. With Ledgered, you can define and track key performance indicators that matter to your business or personal finance.
-Predictive Analytics: Ledgered comes with predictive analytics capabilities that allow you to forecast future trends based on past data (if applicable).

## Directory Structure
### Frontend (/src)
The frontend of the application is built with React and Vite. The main files and directories in the frontend include:

- App.tsx: This is the main application component where the core functionality of the frontend is implemented.
- main.tsx: This is the entry point of the application. It initializes the React app and mounts it to the HTML document.
- index.css: This file contains global styles that are applied throughout the application.
- theme.ts and expanded-theme.ts: These files define the visual theme of the application, including colors, fonts, and other styling properties.
- /components: This directory contains reusable React components that are used across different parts of the application.
- /scenes: This directory contains the main scenes or pages of the application, each represented by a separate React component.
- /state: This directory contains files related to state management in the application.

### Backend (/server)
The backend of the application is built with Node.js and Express. The main files and directories in the backend include:

- index.js: This is the entry point of the server. It sets up the Express application and starts the server.
- data.js: This file contains static data that the server uses to process requests.
- /models: This directory contains Mongoose models, which define the structure of the data in the MongoDB database.
- /routes: This directory contains route handlers, which define how the server responds to different HTTP requests.

## Technologies Used
### Frontend (client/package.json):

- React: A JavaScript library for building user interfaces.
- ReactDOM: A package that provides DOM-specific methods for React.
- React Router: A library for declarative routing in React applications.
- React Redux: Official Redux bindings for React.
- Redux Toolkit: A set of tools to simplify Redux development.
- @reduxjs/toolkit: A package that provides utilities and helpers for Redux.
- react-router-dom: A package that provides DOM bindings for React Router.
- recharts: A composable charting library built on React components.
- @mui/material: The Material-UI component library for React.
- @mui/icons-material: A package that provides Material-UI icons.
- @mui/x-data-grid: A powerful data grid component from Material-UI.
- @emotion/react: A library for CSS-in-JS styling in React.
- @emotion/styled: A package that provides styled components for Emotion.
- regresion: A JavaScript module for least-squares fitting.
### Backend (server/package.json):

- Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- Express: A minimalist web application framework for Node.js.
- Mongoose: A MongoDB object modeling tool designed to work in an asynchronous environment.
- mongodb: The official MongoDB driver for Node.js.
- dotenv: A module for loading environment variables from a .env file.
- body-parser: A package for parsing HTTP request bodies.
- cors: A package for enabling CORS (Cross-Origin Resource Sharing).
- helmet: A package that helps secure Express applications by setting various HTTP headers.
- morgan: A package for logging HTTP requests.
