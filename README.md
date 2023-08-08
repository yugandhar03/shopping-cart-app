
# Shopping Cart App
This is a simple shopping cart application built using React for the frontend and Node.js for the backend. The application allows users to browse a product catalog, add products to their shopping cart, and view their cart contents.

# Getting Started

Follow these steps to set up and run the project on your local machine.

# Prerequisites

- Node.js and npm (Node Package Manager) must be installed on your machine. You can download them from the official Node.js website: [https://nodejs.org/](https://nodejs.org/)

# Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yugandhar03/shopping-cart-app.git
2. Navigate to the project directory:
   ```bash
   cd shopping-cart-app
3. Install dependencies for both the frontend:
    ```bash
        cd client
        npm install
4. Install dependencies for both the backend:
    ```bash
        cd server
        npm install
# Database Setup
1. This project uses MongoDB for data storage. Make sure you have MongoDB installed and running on your machine.
2. Create a .env file in the backend directory and add your MongoDB connection string:
      ```bash
       MONGODB_URI=your-mongodb-connection-string
# Stripe Setup
1. This project uses Stripe payment gate way. Make sure you have Stripe installed and running on your machine.
2. Create a .env file in the backend directory and add your stripe connection string:
      ```bash
       STRIPE_KEY=your-stripe-connection-string
3. Payment sucess navigate to http://localhost:3000/checkout-success.
4. Payment fail navigate to http://localhost:3000/cart.

# Running the Application
1. Start the backend server:
   ```bash
   cd server
   npm start
   The backend server will run on http://localhost:5000.
2. In a new terminal, start the frontend development server:
   ```bash
      cd client
      npm start
      The frontend development server will run on http://localhost:3000.
3. Open your web browser and navigate to http://localhost:3000 to access the application.

# Features
1. Create a product catalog with images, names, and prices.
2. Allow users to add products to their shopping cart and update quantities.
3. (Bonus) Implement a checkout process with payment integration (e.g., Stripe).
4. (Bonus) Add coupon code support for discounts.


