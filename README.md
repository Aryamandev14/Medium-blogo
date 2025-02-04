# Blogging App

## 📌 Overview
The Blogging App is a full-stack web application that enables users to create, edit, and manage their blog posts. The app provides features like user authentication, post categorization, commenting, and real-time updates.

## 🚀 Features
- User authentication (Sign Up, Login, Logout)
- Create, read, update, and delete (CRUD) blog posts
- Commenting system
- Like & dislike functionality
- Profile management
- Categories & tags for blog posts
- Rich text editor for writing posts
- Search and filtering options
- Responsive design

## 🛠️ Tech Stack
### **Frontend:**
- React.js
- TailwindCSS
- Redux (for state management)
- React Router

### **Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose ODM)
- JWT Authentication
- Cloudinary (for image uploads)

### **Other Tools & Libraries:**
- Zod (for validation)
- bcrypt.js (for password hashing)
- Multer (for file uploads)

## 🏗️ Installation & Setup
### **Prerequisites:**
Ensure you have the following installed:
- Node.js (>= 16.x)
- MongoDB
- Git

### **Clone the repository:**
```bash
git clone https://github.com/yourusername/blogging-app.git
cd blogging-app
```

### **Backend Setup:**
```bash
cd server
npm install
```

Create a `.env` file inside the `server` directory and add the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Run the backend:
```bash
npm start
```

### **Frontend Setup:**
```bash
cd client
npm install
npm start
```

The application will be running at `http://localhost:3000/`

## 🎯 API Endpoints
### **Auth Routes**
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - User login

### **User Routes**
- `GET /api/users/:id` - Get user details
- `PUT /api/users/:id` - Update user profile

### **Blog Routes**
- `GET /api/posts` - Fetch all blog posts
- `POST /api/posts` - Create a new blog post
- `GET /api/posts/:id` - Fetch a specific blog post
- `PUT /api/posts/:id` - Update a blog post
- `DELETE /api/posts/:id` - Delete a blog post

## 📷 Screenshots
(Include relevant screenshots of the app here)

## 🎯 Future Enhancements
- Implement notifications
- Add social media sharing
- Implement role-based access control
- Enhance UI/UX

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📝 License
This project is licensed under the MIT License.

## 📞 Contact
For any queries, reach out to:
- **Your Name:** Aryaman Dev Kumar
- **Email:** your.email@example.com
- **GitHub:** [your-github-profile](https://github.com/yourusername)

