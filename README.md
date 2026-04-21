<img width="1283" height="645" alt="image" src="https://github.com/user-attachments/assets/f0dc970a-ad92-4c7f-9207-d378e1ca2463" />
<img width="1187" height="628" alt="image" src="https://github.com/user-attachments/assets/839a2f2b-f195-4810-8270-b8649eb62ab0" />
<img width="1123" height="382" alt="image" src="https://github.com/user-attachments/assets/5f8fba8c-919a-4353-8b14-a4a11856414b" />


📝 Blogify – MERN Blogging Website

Blogify is a full-stack blogging platform built using the MERN stack. It allows users to create, edit, and share blog posts, interact with content, and manage their profiles through a modern and responsive interface.

🚀 Features
✍️ Create, edit, and delete blog posts
📰 View all blogs with pagination
🔍 Search blogs by title or keywords
❤️ Like and comment on posts
👤 User authentication (JWT-based login/signup)
🧑‍💻 User profiles with personal posts
🛠️ Admin controls for content moderation
⚡ Responsive design for all devices
🛠️ Tech Stack

Frontend:

React.js
Redux / Context API
HTML5, CSS3, JavaScript

Backend:

Node.js
Express.js

Database:

MongoDB

Authentication & Tools:

JWT
bcrypt
Mongoose
📂 Project Structure
Blogify/
│── client/                 # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── App.js
│
│── server/                 # Node + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
│── .env
│── package.json
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/blogify.git
cd blogify
2️⃣ Install dependencies

Frontend:

cd client
npm install

Backend:

cd server
npm install
3️⃣ Setup Environment Variables

Create a .env file in the server folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
4️⃣ Run the application

Backend:

cd server
npm run server

Frontend:

cd client
npm start
🌐 Open in Browser
http://localhost:3000
🔐 Authentication Flow
Users register/login
Passwords are hashed using bcrypt
JWT tokens are generated for secure sessions
Protected routes require authentication
📸 Screenshots
🏠 Home Page
📝 Create Blog Page
📄 Blog Details Page
👤 User Profile
🛠️ Admin Dashboard

(Add screenshots here after uploading images)

📌 Future Enhancements
🖼️ Image upload for blog posts
🌐 SEO optimization
🔔 Notifications system
📱 Progressive Web App (PWA)
🤖 AI-powered content suggestions
🤝 Contributing

Contributions are welcome!
Fork the repository and submit a pull request.

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Aditya

GitHub: https://github.com/Adi8454/Blogging-websites
