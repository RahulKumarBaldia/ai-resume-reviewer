# 🤖 AI Resume Reviewer

An AI-powered full stack web application that analyzes your resume and provides instant ATS compatibility score, strengths, weaknesses, and improvement suggestions.

![AI Powered](https://img.shields.io/badge/AI-Groq%20LLaMA%203.3-blue)
![Stack](https://img.shields.io/badge/Stack-Full%20Stack-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## ✨ Features

- 📄 Upload your resume as PDF
- 🎯 ATS Compatibility Score (0-100)
- 💪 Strengths & Weak Areas analysis
- 📊 Section-wise Score breakdown
- 🔑 ATS Keywords found & missing
- 💡 Actionable improvement suggestions
- ⚡ Powered by Groq LLaMA 3.3 70B

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Vite
- CSS3

**Backend:**
- Node.js
- Express.js
- Groq AI SDK (LLaMA 3.3 70B)
- Multer (PDF upload)
- PDF Parse

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- Groq API Key — get it from [groq.com](https://groq.com)

### Installation

**Clone the repo:**
```bash
git clone https://github.com/RahulKumarBaldia/ai-resume-reviewer.git
cd ai-resume-reviewer
```

**Setup Backend:**
```bash
cd Backend
npm install
```

Create `.env` file in Backend folder:
```
GROQ_API_KEY=your_groq_api_key_here
```

```bash
npm start
```

**Setup Frontend:**
```bash
cd ../Frontend
npm install
npm run dev
```

## 📸 Screenshots

### Home Page
![Home Page](./screenshots/home.png)

### Analysis Result
![Analysis Result](./screenshots/result.png)

## 🤝 Author

**Rahul Kumar Baldia**
- GitHub: [@RahulKumarBaldia](https://github.com/RahulKumarBaldia)  