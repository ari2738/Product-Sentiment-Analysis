# Product-Sentiment-Analysis
A full-stack Product Sentiment Analyzer that scrapes Amazon &amp; Flipkart reviews, classifies sentiment using TextBlob NLP, and displays insights on an interactive React dashboard. Built with Flask, SQLite, React, and Recharts.

🖥️ Live Features

📦 Add and manage products
🔍 Scrape reviews from Amazon & Flipkart using Selenium
🧠 Analyze sentiment using TextBlob NLP
📊 Interactive charts — Pie, Bar, Area, Keywords
🔤 Live text sentiment analyzer
💾 SQLite database — no installation required

 Tech Stack
LayerTechnologyFrontendReact 18, React Router, Recharts, AxiosBackendPython, Flask, Flask-CORSDatabaseSQLite (built into Python, zero setup)NLPTextBlob (polarity and subjectivity)ScrapingSelenium, BeautifulSoup4

🧠 How Sentiment Analysis Works
Each review is analyzed using TextBlob NLP:
MetricRangeMeaningPolarity-1.0 to +1.0Negative to PositiveSubjectivity0.0 to 1.0Objective to Subjective
Label Classification:

polarity > 0.1 → Positive 😊
polarity < -0.1 → Negative 😠
Between -0.1 and 0.1 → Neutral 😐


📦 Python Dependencies
flask==3.0.3
flask-cors==4.0.1
python-dotenv==1.0.1
textblob==0.18.0
beautifulsoup4==4.12.3
selenium==4.21.0
requests==2.32.3

🔮 Future Improvements

 Deploy to Render + Netlify
 Add user login and authentication
 Support more platforms (Meesho, Myntra)
 Export sentiment reports as PDF
 Email alerts for negative review spikes
 Multilingual sentiment analysis
