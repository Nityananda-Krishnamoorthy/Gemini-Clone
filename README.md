# 🔮 Gemini Clone – AI Chat App with Google Generative AI

A full-featured Gemini (ChatGPT-style) clone built using **React + Vite**, powered by **Google's Generative AI (Gemini Pro)** API. It supports prompt-based chat, response streaming, and smart interface features like clickable prompt cards, input handling, and loading states.

---

## 🚀 Features

- ⚛️ Modern React app with Vite for lightning-fast builds
- 🧠 Integration with `@google/generative-ai` for Gemini Pro API
- 🎨 Responsive UI with predefined prompt cards
- 🗨️ Simulated response streaming with typewriter effect
- 💬 Context-based state management using React Context API
- 🌐 Deployed on [Vercel](https://vercel.com/)

---

## 📁 Project Structure

gemini-clone/
├── public/                   # Static assets (favicon, etc.)
├── src/
│   ├── assets/               # Icons and images
│   ├── components/
│   │   ├── Sidebar/          # Optional Sidebar (can be expanded)
│   │   └── Main/             # Main chat UI component
│   ├── config/
│   │   └── gemini.js         # Gemini API integration
│   ├── context/
│   │   └── Context.jsx       # Global state using React Context
│   ├── App.jsx               # Root app component
│   ├── main.jsx              # React entry point
│   └── index.css             # Global styles
├── .env                      # Environment variable for API key
├── .gitignore
├── package.json
├── README.md
├── vite.config.js

---

## 🧪 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/gemini-clone.git
cd gemini-clone
```

### 2. Install dependencies

```bash
npm install
```
### 3. Update your API key in `gemini.js`

```bash
GEMINI_API_KEY=your_google_generative_ai_key
```
### 4. Run to App Locally

```bash
npm run dev
```
## 🌐 Deploy to Vercel

You can deploy this project in one click using Vercel:

### 🔧 Step-by-step:
	1.	Go to https://vercel.com
	2.	Click “New Project”
	3.	Import your GitHub/GitLab project
	4.	Set the Environment Variable:
	•	GEMINI_API_KEY=your_key_here
	5.	Set the Build Command: npm run build
	6.	Set the Output Directory: dist
	7.	Click Deploy

## That’s it! 🎉 Your Gemini clone is now live.
