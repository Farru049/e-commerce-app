# E-Commerce Web Application

A dynamic e-commerce platform built using **React.js** for the front-end, **Node.js** with **Express** for the back-end, and **MongoDB** for database management. This application provides real-time product management, a persistent shopping cart, and user authentication.

## Features

- **User Authentication**: Secure login and logout functionality for users to manage their accounts and cart.
- **Product Management**: Display a list of products with real-time inventory management.
- **Shopping Cart**: Add, remove, and modify the quantity of products in the cart.
- **Persistent Cart**: Cart items persist across sessions using **localStorage**.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Global State Management**: Handled using **React Context API** for global state (e.g., user data, cart items).
- **Offline Support**: Service workers are implemented to cache the app for offline functionality.

## Tech Stack

- **Frontend**: 
  - React.js
  - React Router
  - Context API for state management
  - CSS (Styled Components or plain CSS)

- **Backend** (Optional, for full-stack implementation):
  - Node.js
  - Express.js
  - MongoDB (for product inventory and user data)
  
- **Local Storage**: 
  - For persisting user data and cart information across sessions.

- **Offline Support**:
  - Service Workers for caching and offline functionality.

## Setup Instructions

### Prerequisites

Make sure you have the following installed on your machine:

- **Node.js** (Recommended version: 16+)
- **npm** or **yarn**

### Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/farru049/e-commerce-app.git
