📚 BookStore App

A full-stack BookStore web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.
It allows users to browse, search, and manage books, while providing admin features for inventory and order management.

🚀 Features

🛒 Book Management – Add, edit, delete, and view books

👤 User Authentication – Secure login and signup using JWT

💳 Order System – Users can place and manage orders easily

📦 Admin Dashboard – Manage books, users, and sales

🎨 Responsive UI – Built with modern frontend tools (React + Tailwind CSS)

⚙️ RESTful APIs – Efficient backend API architecture

🏗️ Tech Stack

Frontend: React.js, Vite, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB (Mongoose ORM

Tools & Libraries: Axios, JWT, Nodemon, bcrypt, dotenv

📁 Project Structure

bookStoreApp/
│

├── Backend/

│   ├── index.js

│   ├── models/

│   ├── routes/

│   └── controllers/

├── Frontend/

│   ├── src/

│   ├── components/

│   └── pages/

└── README.md

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/Rahul70079/bookStore-App
cd bookStoreApp


Install dependencies

cd Backend
npm install
cd ../Frontend
npm install


Set environment variables
Create a .env file inside the Backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Run the app

# Start backend
cd Backend
npm run dev

# Start frontend
cd ../Frontend
npm run dev

🧠 Future Enhancements

📖 Wishlist & Favorites

💬 User Reviews and Ratings

💰 Payment Gateway Integration

📊 Advanced Analytics Dashboard

🤝 Contributing

Contributions are welcome!
Please fork the repository and create a pull request for any improvements.

📜 License

This project is licensed under the MIT License.
