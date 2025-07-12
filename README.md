# 🚀 SmartPrep AI – Smart Interview Preparation Simulator

**SmartPrep AI** is a full-stack AI-powered platform designed to simulate technical, behavioral, and communication interviews across various domains. The system uses modern AI tools like Google Gemini API, voice recognition, and NLP to create a realistic and interactive mock interview experience with performance analytics.

> 📅 Developed in June–July 2024 under Acmegrade, IIT Bombay  
> 👤 Author: [Akhila Janagam]  (https://github.com/akhilajanagam799)

---

## 🎯 Key Features

### 🤖 AI-Based Question Generation
- Generate subject-wise questions dynamically (DSA, DBMS, OS, OOPs).
- Powered by Google Gemini API for intelligent, real-time question generation.

### 🧠 NLP-Based Answer Evaluation
- User responses are analyzed using NLP to provide improvement tips.
- Includes follow-up questions and guidance to improve technical clarity and communication.

### 🎤 Voice Interaction (Web Speech API)
- Users can speak their answers instead of typing.
- Great for practicing communication-based interviews with ease and realism.

### 📊 Performance Analytics Dashboard
- Visual analytics using Recharts (bar/line graphs).
- Tracks scores, progress, and historical interview performance.

### 🔐 User Authentication & Session History
- Secure authentication with JWT.
- Tracks user-specific interview sessions and stores history for future analysis.

---

## 🧰 Tech Stack

| Layer           | Technologies Used                                        |
|------------------|----------------------------------------------------------|
| Frontend         | React.js, Tailwind CSS, Vite, Web Speech API             |
| Backend          | Node.js, Express.js                                      |
| Database         | MongoDB, Mongoose ORM                                    |
| AI Integration   | Google Gemini API                                        |
| Auth & Security  | JSON Web Tokens (JWT), CORS, bcrypt                      |
| Data Visualization | Recharts                                                |


---

## 📦 Project Structure

smartprep-ai/
├── frontend/ # React frontend with Tailwind CSS
├── backend/ # Node.js + Express backend
├── README.md # Project documentation
└── ...

yaml

---

## ⚙️ Getting Started

### 🔹 Clone the Repository


git clone https://github.com/akhilajanagam799/smartprep-ai.git
<pre> ```bash cd smartprep-ai ``` </pre>



### 🔹 Frontend Setup

```bash
cd frontend
npm install
npm run dev

