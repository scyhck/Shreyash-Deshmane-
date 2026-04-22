# 🚀 360° Feedback for Indian Government News

🧠 AI-Powered News Sentiment Analysis System

A full-stack intelligent system that collects, processes, and analyzes news from multiple sources to provide 360-degree sentiment insights for Indian government-related news.

---

📌 Project Overview

This project automates the extraction, categorization, and sentiment analysis of digital news including:

- 📰 Text-based news articles
- 🖼️ Images (OCR-based extraction)
- 📄 E-newspapers
- 🎥 Video content (metadata-based analysis)

It helps users and authorities understand public sentiment across various government departments in real-time.

---

🔥 Key Features

- 🔍 Automated Web Crawling (BeautifulSoup + Selenium)
- 🌐 Multi-language News Processing (Google Translate API)
- 🤖 AI-based Sentiment Analysis (BERT + Random Forest)
- 🧠 Smart News Categorization by Government Departments
- 📊 Sentiment Score Visualization (Positive / Negative / Neutral)
- 🔔 Real-time Notifications for Negative News
- 🎯 Advanced Filtering (Language, Department, Sentiment)
- ⚡ Scalable Architecture using Redis & PostgreSQL

---

🛠️ Tech Stack

💻 Frontend

- React.js
- Next.js
- Tailwind CSS

⚙️ Backend

- Python (Django / Flask)
- REST APIs

🧠 Machine Learning & NLP

- DistilBERT
- Random Forest
- Natural Language Processing (NLP)

🗄️ Database & Cache

- PostgreSQL
- Redis

🔧 Tools & Libraries

- BeautifulSoup
- Selenium
- Google Translate API

---

🏗️ System Architecture

User Interface (React)
        ↓
Backend API (Django/Flask)
        ↓
Data Processing Layer
        ↓
ML Models (BERT + RF)
        ↓
Database (PostgreSQL) + Cache (Redis)

---

📷 Screenshots

«Add your UI screenshots here»

- Dashboard
- News Feed
- Sentiment Analysis Graphs

---

⚙️ Installation & Setup

🔽 Clone Repository


https://github.com/scyhck/news-senti

📁 Navigate to Project

cd news-sentiment-analysis

---

🔧 Backend Setup (Python)

cd backend
pip install -r requirements.txt
python manage.py runserver

---

🎨 Frontend Setup (React)

cd frontend
npm install
npm run dev

---

🔑 Environment Variables

Create ".env" file in both frontend & backend:

# Backend
SECRET_KEY=your_secret_key
DB_NAME=your_db
DB_USER=your_user
DB_PASSWORD=your_password
TRANSLATE_API_KEY=your_api_key

# Frontend
NEXT_PUBLIC_API_URL=http://localhost:8000

---

📂 Project Structure

news-sentiment-analysis/
│── frontend/        # React / Next.js UI
│── backend/         # Django/Flask APIs
│── ml_models/       # ML & NLP models
│── crawler/         # Web scraping scripts
│── database/        # DB configs
│── README.md

---

🧪 How It Works

1. 🕸️ Crawl news from multiple sources
2. 🌍 Translate into a common language
3. 🧠 Apply NLP preprocessing
4. 🤖 Run ML models for classification
5. 📊 Store and visualize sentiment
6. 🔔 Trigger alerts for negative trends

---

📈 Future Enhancements

- 📱 Mobile Application (Android/iOS)
- 🌎 Support for more regional languages
- 📡 Live News Streaming Analysis
- 🧠 Improved Deep Learning Models
- 🔗 Integration with Government Dashboards

---

🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a branch (git checkout -b feature-name)
3. Commit changes
4. Push to branch
5. Open Pull Request

---

👨‍💻 Author

Shreyash Deshmane (Sunny)
🎓 B.Tech IT | MERN Stack Developer | ML Enthusiast

- 🔗 GitHub: https://github.com/your-username
- 📺 YouTube: Gaming Meme Creator (10K+ Subscribers)

---

⭐ Support

If you like this project, give it a ⭐ and share it!

---

📄 License

This project is licensed under the MIT License.

---
