# 🤖 HabitBot v5.0: The AI Mastery Workstation

**HabitBot** is a high-performance, multi-user productivity platform designed to turn your long-term goals into daily discipline. Powered by **Groq + Llama 3.2**, it combines advanced AI coaching with industrial-grade habit tracking.

---

## 🚀 Key Features

### 🧠 Multimodal AI Coach
- **Vision Support**: Upload photos of your workspace for real-time productivity audits.
- **Document Analysis**: Upload PDFs/Docs for the AI to analyze your goals and schedules.
- **Domain-Locked**: 100% focused on habits, discipline, and performance.

### 📈 Advanced Analytics
- **GitHub-Style Heatmap**: Visualize 365 days of consistency in a beautiful, interactive grid.
- **AI Weekly Report**: Get a data-driven "Performance Audit" based on your actual logs.
- **Mastery Scoring**: Real-time consistency scores and progression badges.

### 🛡️ Enterprise Security
- **Multi-User Isolation**: Secure Login/Signup system with `bcrypt` password hashing.
- **Persistent Sessions**: Cookie-based "Remember Me" logic so you stay logged in.
- **Private Database**: Every user’s habits, tasks, and reflections are strictly isolated.

### 📱 Mobile PWA
- **Installable**: Add HabitBot to your iPhone/Android home screen for a native app experience.
- **Thumb-Friendly**: Optimized UI for tapping and logging on the go.
- **Standalone Mode**: Hides browser UI for full-screen focus.

### ⚙️ Automation & Data
- **AI Task Architect**: Generate complete to-do lists based on your goals.
- **Pomodoro Engine**: Integrated focus timer with OS-level notifications and audio alerts.
- **Life Audit (Export)**: Download your entire journey into a multi-sheet Excel file.

---

## 🛠 Tech Stack

- **Frontend**: Streamlit (Premium Custom CSS)
- **AI Models**: Groq Llama 3.2 (Vision/Text)
- **Backend**: Python 3.11
- **Database**: SQLite (Relational Schema)
- **Visualization**: Plotly Express
- **Security**: Bcrypt + stx-CookieManager

---

## 📂 Project Structure

```bash
domain-chatbot/
├── app.py              # Main PWA Application & UI
├── auth.py             # Security & Encrypted Authentication
├── db.py               # Database Initialization & Schema
├── utils.py            # Analytics, Exports & AI Logic
├── api.py              # Multimodal Groq LLM Interface
├── config.py           # Global System Prompts
├── requirements.txt    # Production Dependencies
└── runtime.txt         # Python 3.11 Specification
```

---

## 🚀 Quick Start (Local)

1. **Clone & Enter**
   ```bash
   git clone <your-repo-url>
   cd domain-chatbot
   ```

2. **Environment Setup**
   ```bash
   python -m venv venv
   source venv/bin/activate  # venv\Scripts\activate on Windows
   pip install -r requirements.txt
   ```

3. **Configure API**
   Create a `.env` file:
   ```env
   GROQ_API_KEY=your_groq_key
   ```

4. **Launch**
   ```bash
   streamlit run app.py
   ```

---

## 🌍 Cloud Deployment (Streamlit Cloud)

1. Connect your GitHub Repo to **Streamlit Community Cloud**.
2. Go to **Advanced Settings -> Secrets**.
3. Paste your keys: `GROQ_API_KEY = "gsk_..."`.
4. Hit **Deploy** and start your journey to mastery!

---

**Developed for high-agency individuals who value discipline and data.** 🚀🦾✨