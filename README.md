My E-Commerce App
Welcome to my e-commerce app built with Node.js and React! This app allows users to browse products, view details, read and write reviews, and manage their shopping carts. It also includes a new feature to show related products. Here’s a guide to get started and understand how the app works.

What This App Does
Shows Products: View a list of products available for purchase.
Product Details: Click on a product to see more details about it, including a new "Related Products" section.
User Reviews: Read and write reviews for products.
Shopping Cart: Add products to your cart and proceed to checkout.
User Accounts: Sign in to manage your account and write reviews.
Features Added
Related Products: On the product detail page, you can now see a list of related products that you might also like. This helps you find similar items quickly.
What You Need
Node.js: Required to run the backend server. Download from nodejs.org.
MongoDB: The database used to store product and user information. You can use a local MongoDB instance or a cloud service like MongoDB Atlas.
How to Set It Up
Clone the Code

Get the code from GitHub by running:

bash
Copy code
git clone https://github.com/your-username/your-repository.git
cd your-repository
Install Backend Packages

Navigate to the backend folder and install the necessary packages:

bash
Copy code
cd backend
npm install
Install Frontend Packages

Navigate to the frontend folder and install the packages:

bash
Copy code
cd ../frontend
npm install
Set Up Environment Variables

Create a file named .env in the backend folder with the following content:

env
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Replace your_mongodb_connection_string with your MongoDB connection string and your_jwt_secret with a secret password for securing user sessions.

Run the App

Start the Backend Server

Go to the backend folder and run:

bash
Copy code
npm start
Start the Frontend

Open a new terminal window, go to the frontend folder, and run:

bash
Copy code
cd ../frontend
npm start
Your app should now be running! Open your web browser and go to http://localhost:3000 to view the frontend. The backend will be available at http://localhost:5000.

Using the App
Visit the Website

Open your browser and navigate to http://localhost:3000.

Browse Products

Look through the list of products and click on any product to view more details.

View Related Products

On the product detail page, check out the "Related Products" section to find similar items you might like.

Add to Cart

Choose the quantity and click "Add to Cart" to add items to your shopping cart.

Write Reviews

If you are logged in, you can write reviews for products you’ve purchased.

Sign In

To write reviews or manage your account, sign in first.

How to Contribute
If you want to contribute to this project:

Fork the Repository: Make a copy of the repository on GitHub.
Create a Branch: Create a new branch for your changes.
Make Changes: Modify the code as needed.
Submit a Pull Request: Share your changes with us on GitHub.
License
This project is licensed under the MIT License. Check the LICENSE file for more details.

Acknowledgments
React: A library for building user interfaces.
Node.js: A runtime for executing JavaScript on the server.
Express.js: A web framework for Node.js.
MongoDB: A database for storing data.
