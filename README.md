# 📝 QuickBlog - Full Stack AI-Powered Blogging Platform

## 📌 Overview

**QuickBlog** is a full-featured blog platform built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. It allows admins to create, manage, and delete blogs while leveraging **AI-powered content generation** using the Gemini API. The platform includes media management, an admin dashboard, and is fully deployed and ready for production.

🚀 **Live Demo**: [https://quick-blog-full-stack-puce.vercel.app/](https://quick-blog-full-stack-puce.vercel.app/)  
📂 **GitHub Repo**: [QuickBlog Repository](https://github.com/balmukund18/QuickBlog-FullStack)

---

## 🎯 Key Features

### ✍️ Blogging Platform
- **AI-Generated Content** using Google Gemini API
- **Add, Edit, Delete Blogs** from Admin Dashboard
- **Comment Management** for user interaction
- **Responsive Design** for all screen sizes

### ⚙️ Admin Features
- Secure admin access
- Post new blogs with image upload
- View and manage all blogs and user comments
- Real-time update on blog listing

### 🖼️ Media & AI Integration
- **Image Uploads** via **ImageKit**
- **Content Generator** using **Gemini API** (Google AI Studio)

---

## 🧪 Tech Stack

| Layer             | Technology                             |
|------------------|-----------------------------------------|
| **Frontend**      | React.js, Tailwind CSS                  |
| **Backend**       | Node.js, Express.js                    |
| **Database**      | MongoDB (with Atlas)                   |
| **Authentication**| Admin-only access                      |
| **Image Hosting** | ImageKit                                |
| **AI Integration**| Gemini API (Google AI Studio)           |
| **Hosting**       | Vercel (Frontend), Render/Other (Backend) |

---

## 🛠️ Installation Guide

### 🔧 Backend Setup (Server)

```bash
# Clone the repository
git clone https://github.com/balmukund18/QuickBlog-FullStack.git

# Navigate to the server directory
cd QuickBlog-FullStack/server

# Install backend dependencies
npm install

# Create a .env file in the /server folder and add the following:
# - MONGODB_URI
# - IMAGEKIT_PUBLIC_KEY
# - IMAGEKIT_PRIVATE_KEY
# - IMAGEKIT_URL_ENDPOINT
# - GEMINI_API_KEY

# Start the backend server
npm run server
```

### 🎨 Frontend Setup (Client)

```bash
# Navigate to the client directory
cd QuickBlog-FullStack/client

# Install frontend dependencies
npm install

# Start the React development server
npm run dev
```
## 👥 Contributors

Feel free to contribute! Open a pull request or report issues to help improve the project.

## 📜 License

This project is open-source under the [MIT License](LICENSE).

## 📞 Contact

For queries, suggestions, or collaborations, feel free to reach out:

- 📧 Email: [sm1370530@gmail.com](mailto:sm1370530@gmail.com)
- 🔗 GitHub: [@balmukund18](https://github.com/balmukund18)

Open to feedback, issues, or contributions! 🤝
