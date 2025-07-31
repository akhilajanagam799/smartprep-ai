
# 🚀 SmartPrepAI– AI-Powered Interview Preparation Platform

PrepBuddy is a full-stack AI-driven platform that helps users prepare for technical and behavioral interviews with role-specific questions, intelligent explanations, and personalized session tracking. Powered by Google's Gemini API and a modern web stack, it simulates an interactive and efficient interview preparation experience.

---

## ✨ Features

- 🎯 **AI-Enhanced Practice**  
  Generate smart, role-specific technical questions using Gemini API  
  Get instant AI-generated explanations and feedback

- 📈 **Personalized Learning**  
  Customize sessions by role, topic, and experience level  
  Simulate real interview experiences for DSA, DBMS, OS, OOPs, etc.

- 📚 **Question Management**  
  View, pin, and revisit generated questions  
  Supports difficulty-level and topic-based filtering (extendable)

- 🖥️ **Modern UI & UX**  
  Responsive frontend built with React.js and TailwindCSS  
  Clean dashboard interface and real-time updates

---

## 🛠️ Tech Stack

| Layer         | Technologies                              |
|--------------|-------------------------------------------|
| **Frontend**  | React.js, TailwindCSS, Vite, Axios        |
| **Backend**   | Node.js, Express.js                       |
| **Database**  | MongoDB (Atlas)                           |
| **AI Model**  | Gemini API (Google)                       |
| **Auth**      | JWT (JSON Web Tokens)                     |

---

## 📦 Folder Structure

prepbuddy/
├── frontend/ # React + TailwindCSS

│ ├── src/

│ │ ├── components/

│ │ └── pages/

│ └── .env # VITE_API_URL

├── backend/ # Node + Express

│ ├── routes/

│ ├── controllers/

│ ├── models/

│ └── .env # API keys and Mongo URI'

└── README.md

---


---





### 🔹 Clone the Repository

```bash
git clone https://github.com/akhilajanagam799/smartprep-ai.git
cd smartprep-ai
```

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```
Make sure to configure the VITE_API_URL in frontend/.env file:

```bash
VITE_API_URL=http://localhost:8000
```

## Backend Setup
```bash
cd ../backend
npm install
npm run dev
```
Create a .env file inside the backend directory with the following content:
```bash
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
ALLOWED_ORIGINS=http://localhost:5173
```


##  Environment Variables Summary

| Variable          | Purpose                                 |
| ----------------- | --------------------------------------- |
| `PORT`            | Port for backend server (default: 8000) |
| `MONGO_URI`       | MongoDB Atlas connection string         |
| `JWT_SECRET`      | JWT token encryption key                |
| `GEMINI_API_KEY`  | Google Gemini AI API key                |
| `ALLOWED_ORIGINS` | Frontend domain (CORS policy)           |


 ## 🤖 Gemini API Integration
 
The backend uses Gemini API to generate interview questions dynamically:

API: https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent

Requires: GEMINI_API_KEY from Google AI Studio




## 👩‍💻 Author

Akhila Janagam

🎓 B.Tech in Mathematics and Computing

💼 Passionate about building impactful AI tools

🔗 GitHub: @akhilajanagam799

***Thank you for visiting  my project! Feel free to contribute or reach out via GitHub if you have any questions or suggestions.***

