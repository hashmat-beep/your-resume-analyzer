# 🧠 AI Resume Analyzer

Welcome to the AI Resume Analyzer!  
This is a modern, fully frontend resume scoring app powered by **React**, **TypeScript**, **Tailwind CSS**, **Zustand**, **Puter.js**, and **OpenAI API**.  
It gives your resume a score based on a job description and provides **smart, AI-generated suggestions** to help you improve it for applicant tracking systems (ATS).

---

## ✨ Features

- 📄 Upload your **PDF resume**
- 📝 Paste any **job description**
- ⚡ Instantly get an **ATS-style match score**
- 💡 AI-generated suggestions: formatting, tone, keywords, missing skills
- ☁️ Fully serverless — no backend needed (powered by Puter.js SDK)
- 🎨 Modern UI with responsive design and clean layout

---

## 🛠 Tech Stack

| Tool        | Purpose                                |
|-------------|----------------------------------------|
| **React 19**       | UI and component logic               |
| **TypeScript**     | Type safety and better debugging     |
| **Vite**           | Lightning-fast dev and build tool    |
| **Tailwind CSS**   | Utility-first responsive styling     |
| **Zustand**        | Simple and fast global state         |
| **React Router v7**| Routing and navigation               |
| **Puter.js SDK**   | Auth, file storage, and AI API access |
| **pdfjs-dist**     | Display and parse PDF resumes        |

---


---

## ▶️ How to Run Locally

### ✅ Prerequisites:
- Node.js 20+ and npm installed

### 🧪 1. Clone the repo:
```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
npm install
npm run dev
Then open http://localhost:5173 in your browser.

📌 How It Works

    Sign in with your Puter account (handled via puter.js)

    Upload your resume (PDF only) – the app previews and stores it

    Paste a job description from LinkedIn, Indeed, or any job board

    Click “Analyze” – the app sends both to the AI model

    You’ll get:

        ATS Score (% match)

        Strengths and weaknesses

        Clear suggestions to improve

    Option to wipe data and upload new resumes/jobs

