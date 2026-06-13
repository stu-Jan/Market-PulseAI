# 📡 MarketPulse AI

MarketPulse AI is an AI-powered market intelligence platform that analyzes real-time public sentiment, emerging trends, and news signals from multiple online sources. The system combines machine learning, trend analytics, and generative AI to help users identify opportunities, risks, and market movements through an interactive dashboard.

## 🚀 Features

* 🔍 Real-time sentiment analysis using a trained Machine Learning model
* 📈 Google Trends integration for emerging topics and search interest tracking
* 📰 News aggregation from Google News RSS feeds
* 💬 Reddit discussion monitoring and sentiment extraction
* 🤖 AI-generated market insights and recommendations using Gemini AI
* 📊 Interactive dashboards built with React and Streamlit
* 📁 Export analytics reports to CSV and Excel formats
* ⚡ FastAPI backend with live data streaming support

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* Framer Motion
* Recharts

### Backend

* FastAPI
* Python
* Server-Sent Events (SSE)

### AI & Machine Learning

* Scikit-learn
* TF-IDF Vectorizer
* Logistic Regression
* Google Gemini API

### Data Sources

* Reddit Public JSON API
* Google News RSS
* Google Trends (PyTrends)

## 📂 Project Structure

```text
marketpulse-ai/
├── api/
├── frontend/
├── dashboard/
├── agents/
├── sources/
├── models/
├── requirements.txt
└── start.py
```

## ⚙️ Installation

```bash
# Clone repository
git clone <repository-url>

# Install backend dependencies
pip install -r requirements.txt

# Install frontend dependencies
cd frontend
npm install
```

## 🔑 Environment Variables

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

The application will still function without Gemini AI, but AI-generated insights will be disabled.

## ▶️ Run the Application

### FastAPI + React Dashboard

```bash
python start.py
```

Backend:

```text
http://localhost:8000
```

Frontend:

```text
http://localhost:5173
```

### Streamlit Dashboard

```bash
streamlit run dashboard/app.py
```

## 📸 Key Capabilities

* Sentiment Classification
* Trend Discovery
* Market Intelligence
* News Monitoring
* AI-Powered Recommendations
* Data Export & Reporting

## 🎯 Future Enhancements

* Multi-language sentiment analysis
* Social media integrations (X, LinkedIn)
* Advanced forecasting models
* Automated alert notifications
* Cloud deployment support

## 📄 License

This project is licensed under the MIT License.

