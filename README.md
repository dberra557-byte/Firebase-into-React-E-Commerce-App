Crystals.USA Store

A fully functional Firebase-powered e-commerce web app where users can register, log in, manage products, add items to their cart, place orders, and view order history. Built with HTML, JavaScript, Bootstrap 5, and Firebase.

Features:

User Authentication:

Register and log in with email and password using Firebase Authentication.

Product Management:

View, add, edit, and delete products stored in Firestore.

Cart & Orders:

Add products to a cart, place orders, and see order history.

Responsive Design:

Works on both desktop and mobile screens via Bootstrap 5.

Default Products:

Preloaded crystal products automatically appear if the store is empty.

Technologies Used:

HTML, CSS, JavaScript
Bootstrap 5�
Firebase�
Firestore Database
Firebase Authentication

Setup Instructions:

Clone or Download the Repository
Create a Firebase Project
Go to Firebase Console� → Click Add project.
Enable Email/Password Authentication (Authentication → Sign-in methods).
Create a Firestore Database (Start in test mode).
Add Firebase Config
In the HTML file, replace the firebaseConfig object with your project credentials:
JavaScript
Copy code
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
Open the HTML File in a Browser
The login/register screen appears first.
Once logged in, users can access products, cart, and orders.

Firestore Collections:

Products: Stores product information (title, price, description, category, image).
orders: Stores orders with userId, list of products, and createdAt.

Usage Overview:

Home: Welcome page with a button to view products.
Products: Browse products, view details, add to cart, and manage products.
Add Product: Add new products to the store.
Cart: View cart and place orders.
Orders: See previous orders with detailed items and total.
Login/Register: Create a new account or log in.
Logout: Sign out from the app.
