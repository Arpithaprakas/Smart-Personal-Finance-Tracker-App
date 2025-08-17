# Smart-Personal-Finance-Tracker-App
Android Mobile Application developed using java

A personal finance management Android app that helps users track income, expenses, and savings, analyze spending habits with graphs and reports, and automatically categorize transactions using a Python NLP backend.

🚀 Features

🔑 User Authentication – Registration, Login, Change Password, and Logout.

💰 Add Transactions – Record income, expenses, and savings with custom date picker.

🏦 Automatic Categorization – Transaction descriptions are sent to a Python backend (Flask + NLP/ML) for category prediction.

📊 Graphical Analytics – Line & Pie charts (using MPAndroidChart) for income, expenses, and savings trends.

📂 User-Specific Data – Each logged-in user only sees their own transactions.

🎨 Modern UI/UX – Splash screen, bottom navigation, settings (dark/light theme), and history view.

🔒 Secure Storage – SQLite database for offline transaction and user data.

Tech Stack
Frontend (Android App)

Language: Java

IDE: Android Studio

Database: SQLite

Libraries: MPAndroidChart, SharedPreferences

Backend (Categorization Service)

Framework: Python Flask

NLP/ML: Rule-based + ML model for transaction categorization
