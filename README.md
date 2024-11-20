House Renting Web Application
A MERN (MongoDB, Express.js, React.js, Node.js) web application designed to facilitate the process of searching, inquiring, and renting properties. This app includes user roles for renters and owners, property management features, and admin oversight to ensure a safe and secure platform.

Features
User Registration & Authentication: Supports two roles: Renter and Owner.
Property Listings: Allows owners to add, update, and delete property listings.
Property Search & Filters: Renters can browse listings using filters like location, rent range, and property type.
Booking System: Renters can inquire about properties, and owners can confirm bookings.
Admin Role: Admin reviews and approves owner registrations, manages platform governance, and monitors activity.
Real-Time Status Updates: Booking and property status changes are displayed instantly to users.
Project structure
This project follows a client-server architecture:

Frontend: Built with React and styled using Bootstrap, Material UI, and Ant Design for a responsive UI.
Backend: Developed with Express.js, connected to MongoDB for data storage.
Database: MongoDB manages user accounts, property listings, and booking information.
Folder structure
house-rent-app/ │ ├── frontend/ # React frontend │ ├── src/ │ └── public/ │ ├── backend/ # Express backend │ ├── config/ # Database and environment configuration │ ├── controllers/ # Route controllers │ ├── models/ # MongoDB models │ ├── routes/ # API route definitions │ └── middleware/ # Authentication and validation │ └── README.md

Env. variables
Environment Variables Create an .env file in the backend directory and configure the following environment variables:

PORT=8000 MONGO_URI=your_mongodb_connection_string JWT_KEY= cVjH7n6M4pZ1jK2dN8oX1bXrQw2+Jk8Gx5zS1R3iZ+fVjFcQ0AhVFnQYmK5e25a

PORT: Port number for backend server (default is 8000). MONGO_URI: MongoDB connection string. JWT_KEY: Secret key for JSON Web Token (JWT) authentication.# House-renting-website-using-MERN-stack
