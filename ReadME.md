# Product Management App

## Overview
This project is a simple MERN stack  application designed for managing a list of products. Users can add new products and view them in a list. The app interacts with a backend server for data fetching and posting.
I did not use mongodb cause it is simple little project.

## Features

- **Retrieve Products**: Get a list of all products.
- **Product List Display**: Shows a list of products fetched from an API.
- **Add New Products**: Users can add a new product with a title and price.
- **Loading State**: Displays a loader while data is being fetched from the server.
- **Error Handling**: Alerts users if there are any issues when adding new products.

## Project Structure
### Frontend Files
- **App.js**: The core component that manages the product list, handles data fetching, and provides functionality to add new products. Contains state management using `useState` and `useEffect` hooks.
- **index.js**: The entry point of the app that renders the `App` component inside the root DOM node.
- **index.css**: Contains basic styling for the app, including global reset and basic font setup.

### Backend Files 
- **server.js**:  a simple Node.js and Express.js application that provides an API for managing products. The application uses in-memory storage (not a database) to store product data.

## Prerequisites

- Node.js (v12 or higher)
- npm (Node Package Manager)

## How to Run the Project
1. **Clone the repository** to your local machine.
2. **Install dependencies** by running:
   ```bash
   npm install
3. **start server** by running:
      ```bash
      npm start
