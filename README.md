# Login Page using React Context API

🚀 Live Demo: [https://login-page-contextapi.netlify.app](https://login-page-contextapi.netlify.app)

This is a simple React project built to demonstrate and practice the **Context API**. The app accepts a username and password via a form and displays a personalized welcome message using global state.

---

## ✨ Features

- 🔐 Accepts **username** and **password** input.
- 🌍 Uses **React Context API** to manage global state (no prop drilling).
- 👋 Displays a personalized **welcome message** after login.
- 💻 Responsive and beginner-friendly layout.
- 📦 Built with **React** and **Vite** (or CRA, if applicable).

---

## 🧠 What I Learned

- How to create and provide a custom `Context`
- Using `useContext` and `useState` for global state management
- Structuring a clean and minimal app with shared state across components


---

## 🛠 Tech Stack

- ⚛️ React
- 🧠 Context API
- 🎨 Tailwind CSS / CSS Modules (if used)
- ⚡ Vite (or Create React App)

---

## 📁 Folder Structure

src/
├── components/
│ └── LoginForm.jsx
│ └── Welcome.jsx
├── contexts/
│ └── AuthContext.jsx
├── App.jsx
└── main.jsx


---

## 🚀 Getting Started

To run this project locally:

```bash
git clone https://github.com/harshsinghpujari/learning-context-api.git
cd learning-context-api
npm install
npm run dev   # or npm start if using CRA
```

🧠 Author

Himanshu singh
📫 View my GitHub

🌐 Deployment

This project is deployed on Netlify:
https://login-page-contextapi.netlify.app

To deploy your own version:

    Push your code to GitHub

    Go to Netlify

    Click “Import from GitHub”

    Set:

        Build Command: npm run build

        Publish Directory: dist (for Vite) or build (for CRA)

    Click Deploy

📃 License

This project is for educational purposes and is open to all learners.


---
