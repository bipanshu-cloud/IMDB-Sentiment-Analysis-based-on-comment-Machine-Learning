# 🎬 IMDB Sentiment Analysis Web App

A **Flask-based web application** that performs sentiment analysis on **IMDB movie reviews** using machine learning.

---

## 🚀 Features

- Real-time **positive/negative** sentiment classification  
- Clean and simple **Flask web interface**  
- Uses a **pre-trained ML model** for predictions  
- Lightweight and easy to run locally

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask  
- **Frontend**: HTML, CSS  
- **Libraries**: Scikit-learn, Pandas, Numpy  
- **ML Model**: Trained on IMDB dataset

---

## 🧠 How It Works

1. User submits a movie review  
2. The review is **vectorized and preprocessed**  
3. The ML model predicts the **sentiment**  
4. Output is shown: ✅ **Positive** / ❌ **Negative**

---

## 📁 Project Structure

Imdb-Sentiment-Analysis-Flask/
│
├── static/                 # Static files (CSS, images)
├── templates/              # HTML templates
├── model/                  # Pre-trained model and vectorizer
├── app.py                  # Main Flask app
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation (you're here!)


---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Imdb-Sentiment-Analysis-Flask.git
cd Imdb-Sentiment-Analysis-Flask

###2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
### 4. Run the app
bash
Copy
Edit
python app.py

## 📦 Requirements
Python 3.x

Flask

Scikit-learn

Pandas

Numpy

## 📄 License
This project is open-source and available under the MIT License.



