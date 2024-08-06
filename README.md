# My E-Commerce App

Welcome to my e-commerce app built with Node.js and React! This app lets users browse products, view details, read and write reviews, and manage their shopping carts. A new feature shows related products to help users find similar items. Here's a guide to get started and understand the app's functionality.

## Features

### Core Features
- **Product Listing**: Browse a list of products available for purchase.
- **Product Details**: View detailed information about each product, including a "Related Products" section.
- **User Reviews**: Read and write reviews for products.
- **Shopping Cart**: Add products to your cart and proceed to checkout.
- **User Accounts**: Sign in to manage your account and write reviews.

### New Feature
- **Related Products**: On the product detail page, users can now see a list of related products.

## Prerequisites

- **Node.js**: Required to run the backend server. Download from [nodejs.org](https://nodejs.org/).
- **MongoDB**: Used to store product and user information. You can use a local instance or a cloud service like MongoDB Atlas.

## Setup Guide

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### Configure Environment Variables

Create a file named `.env` in the backend folder with the following content:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Replace `your_mongodb_connection_string` with your MongoDB connection string and `your_jwt_secret` with a secret key for securing user sessions.

### Run the Application

#### Start the Backend Server

```bash
cd backend
npm start
```

#### Start the Frontend

Open a new terminal window and run:

```bash
cd frontend
npm start
```

The app will be available at [http://localhost:3000](http://localhost:3000), and the backend server will run at [http://localhost:5000](http://localhost:5000).

## Using the App

- **Visit the Website**: Go to [http://localhost:3000](http://localhost:3000).
- **Browse Products**: Explore the product listings and click on any product for more details.
- **View Related Products**: Check out the "Related Products" section on product detail pages.
- **Add to Cart**: Choose the quantity and add items to your shopping cart.
- **Write Reviews**: Log in to write reviews for products you've purchased.
- **Sign In**: Sign in to manage your account and access additional features.

## Contributing

To contribute to this project:

1. Fork the repository on GitHub.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Submit a pull request to share your improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **React**: A JavaScript library for building user interfaces.
- **Node.js**: A JavaScript runtime for server-side programming.
- **Express.js**: A web framework for Node.js.
- **MongoDB**: A NoSQL database for storing data.

Feel free to explore, use, and contribute to this project!