# 🤖 TaskPilot AI

**Plan smarter. Focus better. Track your progress.**

TaskPilot AI is a Streamlit-based productivity assistant that helps users organize tasks, create daily schedules, break large tasks into manageable steps, and generate personalized learning plans with Google Gemini.

## ✨ Features

- **📊 Productivity Dashboard** — View total, pending, and completed tasks with progress statistics.
- **✅ Task Management** — Create, prioritize, complete, filter, sort, and delete tasks.
- **📅 AI Daily Scheduler** — Generate a daily timetable using Gemini-powered ordering or priority-based scheduling.
- **🔄 Smart Rescheduling** — Preview a new schedule for unfinished activities when your availability changes.
- **🧠 AI Learning Planner** — Generate focused learning plans based on your topic, skill level, goals, and available time.
- **🧩 Task Breakdown** — Turn large tasks into actionable subtasks and choose which ones to add.
- **📚 Daily History** — Review saved daily schedule completion records.
- **📈 Monthly Insights** — Analyze saved activity completion trends and export reports as CSV.

## 🛠️ Tech Stack

- Python
- Streamlit
- Google Gemini API
- Pandas
- python-dotenv

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
cd TaskPilot-AI
```

Replace `YOUR_REPOSITORY_URL` with your GitHub repository URL.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure your Gemini API key

Create a `.env` file in the project directory:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Obtain your API key through Google AI Studio. Never commit your actual API key to GitHub.

### 4. Run the application

```bash
streamlit run app.py
```

The app will open in your browser.

## 📁 Project Structure

```text
TaskPilot-AI/
├── app.py
├── task_manager.py
├── .gitignore
├── README.md
└── .env                 # Local only; do not upload
```

The application uses `task_manager.py` for task storage and `schedule_history.json` for saved schedule activity history. These local data files should be kept private unless you intentionally prepare sanitized sample data.

## 🔐 Security

- Store API keys in environment variables.
- Keep `.env` out of version control.
- Do not publish private task data or personal schedule history.
- Review files before making the repository public.

## 🎯 Project Goal

TaskPilot AI brings task management, AI-assisted planning, scheduling, and productivity tracking into one workspace.

## 👨‍💻 Author

**Kyathi Venkat Vardhan**

B.Tech CSE (AI & ML) student interested in Artificial Intelligence, Machine Learning, Generative AI, and AI-powered applications.

---

⭐ If you find this project useful, consider starring the repository!

