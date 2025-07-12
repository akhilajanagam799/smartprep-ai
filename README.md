# 🚀 SmartPrep AI – Smart Interview Preparation Simulator

**SmartPrep AI** is an AI-powered mock interview platform designed to simulate real-world technical, behavioral, and communication interviews across diverse domains. It helps students and professionals enhance their preparation through intelligent question generation, real-time feedback, voice-based interaction, and performance analytics.

---

## ✨ Key Features

- 📚 **Subject-wise AI Interview Questions**  
  Automatically generates domain-specific questions for DSA, DBMS, OS, and OOPs using Google Gemini API.

- 🧠 **Real-Time Answer Evaluation**  
  Uses NLP to evaluate your responses, provide instant feedback, scores, and actionable improvement tips.

- 🗣️ **Voice Interaction Support**  
  Integrated with the Web Speech API to simulate a real conversation-style interview experience.

- 📊 **Interactive Performance Analytics**  
  Track your progress over sessions using rich data visualizations powered by Recharts.

- 👤 **Secure User Authentication**  
  Auth system with JWT and MongoDB to handle user login, session storage, and data protection.

- 📁 **Session History & Review**  
  Stores all previous interview sessions for review, feedback, and performance analysis.

- 🧩 **Responsive UI & Smooth UX**  
  Sleek, modern design using React.js and Tailwind CSS for a seamless and intuitive experience.

---

## 🛠️ Tech Stack

| Layer       | Technologies                             |
|-------------|-------------------------------------------|
| Frontend    | React.js, Tailwind CSS, Vite              |
| Backend     | Node.js, Express.js                       |
| Database    | MongoDB                                   |
| AI Engine   | Google Gemini API                         |
| Authentication | JSON Web Token (JWT)                  |
| Voice API   | Web Speech API                            |
| Charts      | Recharts                                  |

---

## 📦 Project Structure
smartprep-ai/

├── frontend/ # React frontend with Tailwind CSS

├── backend/ # Node.js + Express backend

├── README.md # Project documentation

└── ...

## ⚙️ Getting Started



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


 ##  🌐 Live Deployment 

 | Service  | URL                       |
| -------- | ------------------------- |
| Frontend | [Netlify – coming soon]() |
| Backend  | [Render – coming soon]()  |


## 👩‍💻 Author

Akhila Janagam

🎓 B.Tech in Mathematics and Computing

💼 Passionate about building impactful AI tools

🔗 GitHub: @akhilajanagam799

***Thank you for visiting our project! Feel free to contribute or reach out via GitHub if you have any questions or suggestions.***

