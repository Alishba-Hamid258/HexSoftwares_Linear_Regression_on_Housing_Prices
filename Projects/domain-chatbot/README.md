# 🤖 HabitBot v5.0: Your AI Mastery Workstation

**HabitBot** is a high-performance, multi-user productivity platform that combines **Behavioral Science** with **Multimodal AI**. It doesn't just track your habits—it coaches you through them using Vision, Data Analytics, and deep contextual memory.

> **Live Demo**: [https://habitbot.streamlit.app](https://habitbot.streamlit.app) *(Deploying soon!)*

---

## 🌟 Key Features

### 🧠 Multimodal AI Coach
- **Vision Support**: Upload photos of your desk or handwritten notes for instant AI analysis and task generation.
- **Document Intelligence**: Upload PDFs of habit books or research for the coach to summarize and integrate into your routine.
- **Domain-Locked**: Specialized strictly in productivity, routines, and habit-building science.

### 📊 Advanced Analytics & Visualization
- **Consistency Heatmap**: A GitHub-style 365-day grid that visualizes your daily intensity. Never break the chain!
- **AI Weekly Mastery Report**: Get a personalized, data-driven audit of your week's wins and points of friction.
- **Life Audit (Excel Export)**: Download your entire journey (Habits, Focus Sessions, Tasks, Reflections) in a professionally formatted workbook.

### ⚡ Mastery Toolset
- **Adaptive Pomodoro Engine**: Customizable focus/break timers with OS-level notifications and audio chimes.
- **The Daily Matrix**: A high-speed interface for logging habits and managing deep work sessions.
- **Session Archive**: Start new chats anytime; your old conversations are automatically preserved in a searchable archive.

### 📱 Mobile-First PWA
- **App-Like Experience**: Optimized for mobile with thumb-friendly controls and standalone mode (no browser bars).
- **Persistent Sessions**: Log in once and stay logged in for 30 days across all your devices.

### 🔐 Security & Privacy
- **Industrial-Grade Auth**: Secure login/signup using `bcrypt` password hashing.
- **Data Isolation**: Multi-user database architecture ensuring your habits and logs are strictly private.

---

## 🛠 Tech Stack

| Component | Technology |
|---------|------------|
| **Frontend** | Streamlit + Custom Glassmorphism CSS |
| **Backend** | Python 3.11 |
| **Intelligence** | Groq (Llama 3.2 Vision & 3.1 70B) |
| **Database** | SQLite (Multi-user optimized) |
| **Visualization** | Plotly Express |
| **Auth** | Bcrypt + Browser Cookies (stx) |

---

## 🚀 Getting Started

### 1. Clone & Setup
```bash
git clone https://github.com/Alishba-Hamid258/Habitbot.git
cd Habitbot
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 2. Environment Configuration
Create a `.env` file:
```env
GROQ_API_KEY=your_key_here
```

### 3. Launch
```bash
streamlit run app.py
```

---

## 👨‍💻 Author
**Alishba Hamid**
[GitHub](https://github.com/Alishba-Hamid258) | [LinkedIn](https://linkedin.com/in/alishbahamid)

---

## 📄 License
MIT License - See [LICENSE](LICENSE) for details.