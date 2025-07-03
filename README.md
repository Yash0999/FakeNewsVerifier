# 🕵️‍♂️ Fake News Verifier

A powerful Fake News Verifier app that uses a hybrid approach: Machine Learning and real-time web verification to detect the authenticity of news articles. 

🌐 Live Demo: [FakeNewsVerifier](https://fakenewsverifier.onrender.com/)

---

## 🚀 Features

✅ Detect fake news from plain text  
✅ Uses ML/NLP for classification  
✅ Verifies information with real-time web scraping  
✅ Summarized debunking explanation  
✅ Clean and modern frontend UI  
✅ Hosted on Render (Free Tier)

---

## 🧠 Tech Stack

**Frontend**:
- HTML5, CSS3, JavaScript

**Backend**:
- Python 3.13+
- Flask
- BeautifulSoup (for web scraping)
- ML Libraries (like scikit-learn, pandas, etc.)

**Deployment**:
- Render (Free Web Service)
- Gunicorn for production WSGI server

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/Yash0999/FakeNewsVerifier.git
cd FakeNewsVerifier

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app locally
python app.py
