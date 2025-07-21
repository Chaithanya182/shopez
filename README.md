ShopEZ: E-commerce Application 🛒 An efficient and user-friendly e-commerce platform

📋 Introduction Project Title: ShopEZ: E-commerce ApplicationTeam Members:

C Chaithanya Prasad
T Harshitha
Yaswanth Palapati

🎯 Project Overview Purpose ShopEZ is designed to meet the growing demand for intuitive e-commerce platforms. It simplifies online shopping with seamless navigation, secure transactions, and AI-driven personalized recommendations. Sellers benefit from a robust dashboard for inventory management, order processing, and performance analytics. Key Features

Seamless Checkout: Secure payments with instant order confirmations and email notifications.
Effortless Product Discovery: Advanced search, intuitive category navigation, and powerful filters.
Personalized Recommendations: AI-driven suggestions based on user behavior.
Seller Dashboard: Tools for inventory tracking, order processing, and analytics.
Real-time Analytics: Insights into sales trends, customer preferences, and product performance.

🏗️ Architecture Frontend

Framework: React.js for component-based architecture and efficient state management.
Components:
Product Listings: Dynamic displays with sorting and filtering options.
Cart Management: Add, update, or remove items in the cart.
User Authentication: Secure login and registration pages.
Admin Panel: Tools for sellers to manage inventory and view analytics.

Backend

Technologies: Node.js and Express.js for scalability and performance.
API Endpoints:
/products: Fetch product data.
/orders: Process customer orders.
/users: Manage user authentication.

Middleware: JWT-based authentication and error handling.

Database

Database: MongoDB
Collections:
Users: Stores authentication credentials, profiles, and purchase history.
Products: Manages inventory, prices, categories, and descriptions.
Orders: Tracks order details, delivery status, and payments.

This modular architecture ensures scalability and efficient data management.

⚙️ Setup Instructions Prerequisites

Node.js: v14 or later
MongoDB: Local installation or cloud-based (e.g., MongoDB Atlas)
npm: Package manager for dependencies

Installation

Clone the repository:git clone https://github.com/Chaithanya182/shopez.git

Navigate to the project directory:cd shopEZ

Install dependencies:
Backend:cd server npm install

Frontend:cd client npm install

Running the Servers

Backend:cd server node index.js

Frontend:cd client npm start

📂 Folder Structure Client

src/components: Reusable components (e.g., Navbar, ProductCard, CartItem).
src/pages: Page components (e.g., Home, Cart, Checkout, AdminPanel).
src/services: API interactions for fetching and posting data.
src/redux: State management for cart, authentication, and order status.

Server

routes: RESTful API routes for users, products, and orders.
controllers: Logic for handling API requests and responses.
models: Database schemas for Users, Products, and Orders.
middleware: Authentication (JWT) and error handling.

🚀 Running the Application

Frontend: cd client npm start

Opens the React app in your default browser (default: http://localhost:3000).

Backend: cd server node index.js

Starts the Node.js server (default: http://localhost:5000).

📜 API Documentation Endpoints

Method Endpoint Description Parameters Response Example

GET /products Fetches all products Optional: category, price filters json
[{ "id": "123", "name": "Gold Bracelet", "price": 50, "category": "Accessories" }]

POST /orders Places a new order userId, productDetails, quantity json
{ "message": "Order placed successfully", "orderId": "456" }

🔐 Authentication

JWT-based Authentication:
Login: Issues a JWT token upon successful authentication.
Token Validation: Secures private routes like /orders and /admin.
Logout: Invalidates the token client-side.

🖼️ User Interface Screens

Home: Showcases trending products and categories.
Product Details: Displays detailed product information.
Cart: Summarizes selected products and quantities.
Admin Dashboard: Provides order status updates and analytics for sellers.

🧪 Testing

Unit Testing: Jest for testing components and backend logic.
API Testing: Postman for validating API endpoints.

📸 Screenshots or Demo

Demo Video: https://drive.google.com/file/d/1q2JTe-wZF3z3VwF3tskKyXwohq0hn3jL/view?usp=sharing

⚠️ Known Issues

Slow Search Performance: Requires optimization for large product datasets.
UI Bugs: Minor alignment issues on smaller screens.

🚀 Future Enhancements

Voice Search: Enable voice-activated product searches.
Mobile App: Develop a cross-platform app using React Native.
Multi-language Support: Expand accessibility for global users.

📬 Contact For questions or contributions, reach out via GitHub Issues or contact the team directly.

ShopEZ: Simplifying online shopping, one click at a time!
