# Paceo
📱 Paceo – Energy-Aware Study Planner for Students
A minimalist iOS app that helps students plan their coursework based on energy levels, not just deadlines.
Paceo is a productivity app designed for college and university students who struggle with overwhelming workloads, poor time allocation, and burnout during exam season. Instead of traditional to-do lists, Paceo uses your personal energy profile to generate realistic, balanced study sessions throughout the week — so you stay consistent without burning out.

🌟 Key Features
🧠 Energy-Based Planning
Set your daily energy levels across three blocks (Morning / Afternoon / Evening).
Paceo intelligently prioritizes high-focus periods for your hardest tasks.
Reduces the cognitive load of planning by doing it for you.
📘 Course & Assignment Manager
Add courses with custom colors.
Create assignments with:
Title
Due date
Estimated completion time
Task type (Reading, Coding, Writing, Studying)
⏱️ Smart Study Session Generator
Automatically splits assignments into manageable study blocks.
Uses a greedy scheduling algorithm to place sessions in optimal time slots.
Reschedules skipped sessions while keeping deadlines in mind.
Flags “at-risk” tasks when there isn’t enough time left to complete them.
📅 Daily & Weekly Planner
Today View: shows your exact sessions for the day with start/end times.
Planner View: a clean weekly layout showing your upcoming study load.
Mark sessions as Done or Skip, with automatic adjustments.
🔔 Local Notifications
Smart reminders before each planned study session.
Daily briefing: “Here’s your study load for today.”
💾 Offline-First Storage (SwiftData)
Everything is stored locally on-device for privacy.
No login required. No cloud complexity. No third-party data storage.
🎨 Minimalist UI
Calming color palette
Course color chips
Clean typography
Zero clutter, zero overload
🔧 Tech Stack
SwiftUI
SwiftData
MVVM architecture
Charts framework (for statistics in later versions)
UNUserNotificationCenter for notifications

✍️ How It Works (Short Explanation)
Add your classes and upcoming assignments.
Set your energy levels for each day/time block (Morning/Afternoon/Evening).
Paceo automatically:
breaks assignments into smaller sessions
slots them into high-energy time blocks first
spreads work evenly before deadlines
Every day, you’ll see a personalized study plan you can actually follow.
If you skip a session, Paceo dynamically reschedules it based on remaining availability.

📈 Future Roadmap (Optional for GitHub)
Focus Timer (Pomodoro mode)
Statistics dashboard (study hours per course, streaks, trends)
iCloud sync
Widgets
AI-powered task breakdowns
