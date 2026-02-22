Crystals.USA Store
A fully functional e-commerce web app built with HTML, JavaScript, Bootstrap 5, and Firebase. Users can register, log in, manage products, add to cart, place orders, and view order history.
Features
User Authentication: Email/password registration and login with Firebase Authentication.
Product Management: CRUD operations for products stored in Firestore.
Cart & Orders: Users can add products to cart, place orders, and view order history.
Responsive UI: Built with Bootstrap 5 for mobile and desktop support.
Default Products: Automatically populates the store with sample crystals if empty.
Technologies
HTML, CSS, JavaScript
Bootstrap 5�
Firebase�: Firestore & Authentication
Setup Instructions
Clone or download this repository.
Create a Firebase Project:
Go to Firebase Console� → “Add project”.
Enable Email/Password Authentication under Authentication → Sign-in methods.
Create Firestore Database (Start in test mode).
Configure Firebase:
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
Open the HTML file in a browser.
Users will see the login/register screen first.
After login, users can view/add/edit/delete products, manage their cart, and place orders.
Firestore Collections:
products: Stores product information.
orders: Stores orders with userId, products, and createdAt.
Usage
Home: Welcome page with a button to view products.
Products: Browse products, view details, add to cart, and manage products (if logged in).
Add Product: Admin-style product creation.
Cart: Add products and place orders.
Orders: View order history with full details.
Login/Register: Create a new account or log in.
Logout: Sign out of the app.
