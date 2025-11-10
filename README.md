# 🎓 EduMind – AI Study Assistant

**EduMind – AI Study Assistant** is a **web-based platform** built to help students organize, manage, and enhance their learning experience.  
It brings together smart tools like **Notes**, **To-Do List**, **Timer**, and **Whiteboard** — all integrated into a single, interactive dashboard to improve focus and productivity.

---

## 🚀 Features

- 📝 **Notes Dashboard** – Create, view, and manage your study notes efficiently.  
- ✅ **To-Do List** – Track your daily study tasks and progress.  
- ⏱️ **Pomodoro Timer** – Stay focused with session-based study timers.  
- 🧠 **Whiteboard** – Practice concepts, draw diagrams, and brainstorm ideas interactively.  
- 📊 **User Dashboard** – Personalized interface showing all tools in one place.  
- ☁️ **Cloud Storage** – Save files securely using **Firebase** and **Cloudinary**.  
- 🔐 **Authentication** – Login and manage your data safely through **Firebase Auth**.  

---

## 🧩 Tech Stack

| Layer | Technology Used |
|-------|-----------------|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend / Database** | Firebase (Firestore, Authentication, Hosting) |
| **Cloud Storage** | Cloudinary |
| **Version Control** | Git & GitHub |
| **Design** | Figma / Canva |
| **(Optional)** | Gemini API for AI-powered study summaries |

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/edumind-ai-assistant.git
   cd edumind-ai-assistant

## 🛠️ Setup Instructions

```bash

# 1️⃣ Clone the repository
   ```bash
   git clone https://github.com/yourusername/edumind-ai-assistant.git
   cd edumind-ai-assistant

# 2️⃣ Open the Project
- Launch `index.html` directly in your browser
- OR use **Live Server** in VS Code for better performance

# 3️⃣ Connect Firebase
- Go to [Firebase Console](https://console.firebase.google.com)
- Create a new Firebase project
- Add your `firebaseConfig` details inside `script.js`
- Enable **Authentication** and **Firestore Database**

# 4️⃣ Cloudinary Setup (Optional)
- Create a free account at [Cloudinary](https://cloudinary.com)
- Go to your Cloudinary Dashboard
- Copy your **API Key**, **Cloud Name**, and **API Secret**
- Add them to the configuration section of your project (e.g., in `config.js` or `script.js`)

