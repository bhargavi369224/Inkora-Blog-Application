
# ✦ INKORA – Full Stack Blog Application

## 📌 Project Overview

Inkora is a responsive full stack blogging application developed using HTML, CSS, JavaScript, Node.js, and Express.js.

It provides a platform where users can register, log in, create blog posts, publish articles, save drafts, and manage their content.

The application uses REST APIs to connect the frontend with the backend.

## 🎯 Key Features

- User Registration
- User Login and Logout
- Secure Password Hashing
- JWT Authentication
- Create Blog Posts
- Publish and Save Drafts
- Edit and Delete Blogs
- View Published Blogs
- Personal Dashboard
- Search Blogs
- Category Filtering
- Like Blog Posts
- Responsive Design

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Frontend Structure |
| CSS3 | Website Styling |
| JavaScript | Functionality |
| Node.js | Backend |
| Express.js | REST APIs |
| JSON | Data Storage |
| bcryptjs | Password Hashing |
| JWT | Authentication |
| GitHub | Version Control |

## 📂 Project Structure

```text
Inkora/
│
├── public/
│   └── index.html
│
├── data/
│   └── db.json
│
├── server.js
├── package.json
├── .env
├── .gitignore
└── README.md
```

## 🚀 Installation and Setup

### Step 1: Clone Repository

```bash
git clone https://github.com/bhargavi369224/Inkora-Blog-Application.git
```

### Step 2: Open Project Folder

```bash
cd Inkora
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Configure Environment Variables

Create a `.env` file:

```env
PORT=5000
JWT_SECRET=your_long_random_secret_key
```

### Step 5: Start the Backend Server

```bash
npm run dev
```

### Step 6: Open the Application

Visit:

http://localhost:5000

## 🔗 REST API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | /api/register | Register user |
| POST | /api/login | Login user |
| GET | /api/blogs | View published blogs |
| GET | /api/myblogs | View personal blogs |
| POST | /api/blogs | Create blog |
| PUT | /api/blogs/:id | Update blog |
| DELETE | /api/blogs/:id | Delete blog |
| PATCH | /api/blogs/:id/like | Like blog |
| GET | /api/health | Check server status |

## 🔐 Authentication

- Passwords are hashed using bcryptjs.
- JWT tokens are generated after successful login.
- Protected APIs require authentication.
- Users can edit and delete only their own blogs.

## 💡 Future Enhancements

- MongoDB Database Integration
- User Profile Management
- Blog Comments
- Image Upload
- Forgot Password
- Admin Dashboard

## 👩‍💻 Developed By

**Bhargavi C**

## 📄 License

This project is developed for educational purposes.
