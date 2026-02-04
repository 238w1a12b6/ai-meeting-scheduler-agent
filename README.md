## 🗓️ AI-Based Meeting Scheduler

The AI-Based Meeting Scheduler is a web application that intelligently schedules meetings by analyzing user availability and avoiding time conflicts.
It uses rule-based AI decision logic to recommend the most optimal meeting time and maintains a record of all booked meetings with options to manage them.

This project demonstrates the practical application of Artificial Intelligence concepts such as decision-making, optimization, and automation in a real-world scheduling problem.

## Objectives

- Automate the process of scheduling meetings
- Avoid time conflicts between meetings
- Recommend the best available time slot
- Display all booked meetings clearly
- Allow deletion of booked meetings
- Provide a clean, user-friendly interface

## 🧠 AI Concept Used

- This project uses Rule-Based Artificial Intelligence, where:
- User-provided time slots are analyzed
- Already booked slots are filtered out
- A Smart Time Preference Engine selects the most suitable slot based on priority rules
- Morning slots are preferred over afternoon and evening slots to mimic human decision-making.

## 🛠️ Tech Stack

Frontend : HTML,CSS
Backend : Python,Flask

## ⚙️ System Architecture
User Interface
      ↓
Flask Backend
      ↓
AI Decision Logic
      ↓
JSON Data Storage

## 🚀 Features

- 📅 Intelligent meeting scheduling

- ❌ Conflict detection and avoidance

- ⭐ Smart time preference selection

- 📋 Display of all booked meetings

- 🗑️ Delete booked meetings

- 🎨 Clean, centered, professional UI

- 🧩 Smart Time Preference Engine (Unique Feature)

Instead of choosing a random available slot, the system:

- Gives high priority to morning slots (09:00–11:00)
- Gives medium priority to afternoon slots
- Avoids late hours where possible
- This makes the scheduler behave more like a human assistant.

##▶️ How to Run the Project
1️⃣ Clone the Repository:
git clone https://github.com/your-username/ai-meeting-scheduler-agent.git
cd ai-meeting-scheduler-agent

2️⃣ Install Dependencies:
python -m pip install flask

3️⃣ Run the Application
python app.py

4️⃣ Open in Browser
http://127.0.0.1:5000

AI-Based Meeting Scheduler UI:
<img width="1581" height="767" alt="image" src="https://github.com/user-attachments/assets/58171716-da20-4293-981a-0578795c56dd" />

User selects available time slots:
<img width="1524" height="764" alt="image" src="https://github.com/user-attachments/assets/6cdc102c-1008-4c1c-a276-ab4deab8a38f" />

System checks for conflicts:
<img width="1516" height="767" alt="image" src="https://github.com/user-attachments/assets/06b63609-1a79-4629-8dec-7da39ad3f1dd" />

##Author
Pothabattula Ambha Ramya Sri
B.Tech – Information Technology


