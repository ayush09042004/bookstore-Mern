Welcome to the Book Store MERN Application — a full-stack project that demonstrates a complete MERN (MongoDB, Express, React, Node.js) stack implementation with secure user authentication, product management, and a dynamic front-end interface.

🚀 Project Setup Instructions
🔧 Frontend Setup
Clone or Download the Project Repository:

bash
Copy
Edit
git clone https://github.com/your-username/book-store-mern-app.git
cd book-store-mern-app
Navigate to the Frontend Directory:

bash
Copy
Edit
cd frontend
Create a .env.local File:

Inside the frontend directory (same level as package.json), create a .env.local file.

Add the following Firebase configuration (replace with your own Firebase credentials):

env
Copy
Edit
VITE_API_KEY="Your_Firebase_API_Key"
VITE_AUTH_DOMAIN="Your_Firebase_Auth_Domain"
VITE_PROJECT_ID="Your_Firebase_Project_ID"
VITE_STORAGE_BUCKET="Your_Firebase_Storage_Bucket"
VITE_MESSAGING_SENDERID="Your_Firebase_Messaging_SenderID"
VITE_APPID="Your_Firebase_AppID"
Install Dependencies:

bash
Copy
Edit
npm install
Start the Frontend Development Server:

bash
Copy
Edit
npm run dev
🌐 Backend Setup
Navigate to the Backend Directory:

bash
Copy
Edit
cd backend
Create a .env File:

In the backend directory (same level as package.json), create a .env file.

Add the following environment variables:

env
Copy
Edit
DB_URL="Your_MongoDB_Connection_String"
JWT_SECRET_KEY="Your_Secure_JWT_Secret_Key"
Replace MongoDB URL:

Make sure to use your own MongoDB connection string.

Example:

env
Copy
Edit
DB_URL="mongodb+srv://<your-username>:<your-password>@cluster0.mongodb.net/book-store?retryWrites=true&w=majority"
Secure Your JWT Secret Key:

Generate a strong secret key for JWT.

Example:

env
Copy
Edit
JWT_SECRET_KEY="L@pr}RmE{\"xN5xB"
Install Backend Dependencies:

bash
Copy
Edit
npm install
Start the Backend Development Server:

bash
Copy
Edit
npm run start:dev
📌 Features
🔒 Secure User Authentication (JWT-based).

📚 Dynamic Book Management (Add, Update, Delete).

🔍 Real-time Search Functionality.

🛒 Shopping Cart Integration.

📦 Order Management.

🚀 Technology Stack
Frontend: React, Vite, Firebase for authentication and data storage.

Backend: Node.js, Express.js, MongoDB (Atlas) for database.

Authentication: JWT (JSON Web Token) for secure access.

✅ Tips
Make sure your .env and .env.local files are listed in .gitignore to keep them secure.

Customize the Firebase and MongoDB credentials for your own project.

