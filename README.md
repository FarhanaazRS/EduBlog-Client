# EduBlog 📖✨

A full-stack EduBlog web application built using **React.js** for the frontend and integrated with a RESTful backend API. This platform allows users to explore, read, and write blog posts, primarily focusing on educational content.

---

## 🚀 Features

- 📝 View and read blog posts in an elegant UI
- 🔍 Filter blogs by category
- 👤 User authentication (Login/Register)
- ✍️ Add new blog posts (if backend integrated)
- 📱 Responsive and modern UI using TailwindCSS
- 🌐 Communicates with an external blog API

---

## 💻 Tech Stack

- **React.js** – UI library for building front-end
- **React Router** – Routing between components
- **Axios** – HTTP client for API requests
- **TailwindCSS** – Utility-first CSS framework
- **REST API** – Backend API (assumed from structure)

---

## 📁 Project Structure

```
edublog-master/
│
├── public/
│   └── index.html
│
├── src/
│   ├── assets/              # Static images
│   ├── components/          # Reusable UI components
│   ├── pages/               # Pages like Home, Login, Register
│   ├── App.jsx              # Main app structure
│   ├── main.jsx             # Entry point
│   ├── index.css            # Tailwind styles
│
├── .gitignore
├── package.json
├── tailwind.config.js
├── postcss.config.js
```

---

## 🛠️ Getting Started

### 📦 Prerequisites

- Node.js and npm installed
- Backend server running (optional for blog data)
- Internet access to load external assets and dependencies

### 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/edublog-frontend.git
cd edublog-master
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173`.

---

## 🌐 Environment Setup

Create a `.env` file in the root directory if needed:

```
VITE_API_URL=https://your-api-url.com
```

---

## 🧪 Available Scripts

```bash
npm run dev       # Start dev server
npm run build     # Build for production
npm run preview   # Preview production build
```

---



## 📌 Notes

- Blog content is fetched from an external API, ensure the backend is up and running.
- Ensure proper CORS handling on the backend server.

---


