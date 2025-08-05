# 🧠 AI Resume Analyzer (ResuMatch)

Welcome to the AI Resume Analyzer — **ResuMatch**!  
This is a modern, fully frontend resume scoring app powered by **React**, **TypeScript**, **Tailwind CSS**, **Zustand**, **Puter.js**, and the **OpenAI API**.  
It gives your resume a score based on a job description and provides **smart, AI-generated suggestions** to help you improve it for applicant tracking systems (ATS).

---

### 🔗 Live Demo  
👉 [https://your-resume-analyzer.vercel.app](https://your-resume-analyzer.vercel.app)

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

| Tool              | Purpose                                 |
|-------------------|------------------------------------------|
| **React 19**       | UI and component logic                   |
| **TypeScript**     | Type safety and better debugging         |
| **Vite**           | Lightning-fast dev and build tool        |
| **Tailwind CSS**   | Utility-first responsive styling         |
| **Zustand**        | Simple and fast global state management  |
| **React Router v7**| Routing and navigation                   |
| **Puter.js SDK**   | Auth, file storage, and AI API access    |
| **pdfjs-dist**     | Display and parse PDF resumes            |

---

## ▶️ How to Run Locally

### ✅ Prerequisites:
- Node.js 20+ and npm installed

### 🧪 Steps:
```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
npm install
npm run dev


📌 How It Works

    Sign in with your Puter account (via puter.js)

    Upload your resume (PDF only) – preview and store it

    Paste a job description from LinkedIn, Indeed, etc.

    Click “Analyze” – the app sends both to the AI model

    You’ll receive:

        ATS Score (% match)

        Strengths and weaknesses

        Clear suggestions to improve

    Optionally wipe data and upload new resumes or jobs
