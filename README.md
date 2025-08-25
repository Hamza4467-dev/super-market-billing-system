Super Market Billing System
📝 Project Overview
This is a modern and user-friendly Super Market Billing System developed using HTML, CSS, JavaScript, and Bootstrap. Its primary goal is to streamline super market operations such as product management, sales transactions, and sales history tracking. Integrated with Firebase Firestore, this system also offers real-time data persistence.

✨ Features
The system includes the following key functionalities:

Product Management:

Add new products.

Edit and delete existing products.

Search and sort products by name, price, and stock.

Billing Interface:

Add items from the product grid to the shopping cart.

Update quantity and remove items from the cart.

Subtotal, tax, and total amount are calculated in real-time.

A simple checkout process with payment entry and change calculation.

Sales History:

View a complete record of past sales transactions.

See a detailed breakdown of each sale (items purchased, total, payment details).

Search and sort sales records by ID, product, or total amount.

Data Persistence:

Utilizes Firebase Firestore to securely store products and sales history.

Employs onSnapshot listeners for real-time data synchronization.

Includes a fallback mechanism to save data in Local Storage if Firestore is unavailable.

User Authentication:

Users are automatically signed in using Firebase Anonymous Authentication.

🛠️ Technologies Used
HTML5: For the project's structure.

CSS3: For styling and modern UI design.

Bootstrap 5: For responsive design and UI components.

JavaScript (ES6+): For complete functionality and dynamic behavior.

Firebase SDK:

Firestore: Real-time NoSQL database for data storage.

Authentication: Anonymous user sign-in.

🚀 Setup & Installation (Local)
To run this project on your local machine, follow these steps:

Clone the Repository:
First, clone the project from GitHub:

git clone https://github.com/Hamza4467-dev/super-market-billing-system.git

Navigate to Project Directory:
Change into the cloned repository folder:

cd super-market-billing-system

Open index.html:
Open the index.html file in your web browser. You can either double-click it directly or use a Live Server extension (for VS Code users).

☁️ Firebase Setup (Optional, but Recommended for Data Persistence)
If you wish to use Firebase Firestore for data persistence, you'll need to set up a Firebase project:

Create a Firebase Project:

Go to the Firebase Console.

Create a new project.

Register a Web App:

Register a "web app" within your project.

You will receive a firebaseConfig object.

Enable Firestore:

Navigate to the "Firestore Database" section in the Firebase Console.

Create a new database, choosing "Start in production mode" (or "Start in test mode" if you are just practicing).

Update Security Rules:
Set up security rules for Firestore to allow authenticated users to read and write data. In the Canvas environment, global variables like __firebase_config and __initial_auth_token are automatically provided.

Note: Outside the Canvas environment, you would typically include the firebaseConfig object directly in your JavaScript code where the initializeApp function is called.

💡 Usage
Once the project is running, you will find three main sections:

Product Management:

Here you can add products by clicking the Add New Product button.

Manage existing products using the Edit and Delete buttons in the table.

Filter and sort products using the search bar and by clicking on column headers.

Billing:

Product cards are displayed on the left side. Click on any product card to add it to the cart.

The shopping cart is on the right side. Here you can adjust quantities, remove items, or Clear Cart to empty it.

Click the Checkout button to initiate the payment process. Enter the payment amount and calculate the change.

Sales History:

This section lists all your past sales transactions.

Click the View Details button to see a complete breakdown of any sale.

Filter and sort sales records using the search bar and by clicking on column headers.

🤝 Contributing
Contributions are highly welcome! If you'd like to improve this project:

Fork the repository.

Create a feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

📧 Contact
Hamza4467-dev
GitHub: Hamza4467-dev
