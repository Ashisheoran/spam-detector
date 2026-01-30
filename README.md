# 📩 Email / SMS Spam Classifier

A machine learning–based Email and SMS Spam Detection system that classifies messages as **Spam** or **Not Spam** using **Natural Language Processing (NLP)** and supervised learning.  
The trained model is deployed as an interactive **Streamlit web application**.

---

## 🚀 Live Demo
🔗 **Streamlit App:**  
https://spam-detector-3bf5n5zh4k5sh5lbm4pdgd.streamlit.app

---

## 📌 Project Overview
Spam messages are a major problem in digital communication. This project automatically detects spam messages by analyzing text content using NLP techniques and machine learning models. The system preprocesses text, extracts features using TF-IDF, and predicts whether a message is spam or not.

---

## ✨ Features
- Real-time Email/SMS spam prediction
- Text preprocessing using NLP techniques
- TF-IDF vectorization for feature extraction
- Supervised machine learning classification
- Interactive web interface using Streamlit
- Deployed and accessible online

---

## 🧠 Analysis Techniques Used
- Text Analysis / Text Mining
- Natural Language Processing (NLP)
- TF-IDF Feature Extraction
- Supervised Machine Learning
- Binary Classification

---

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK
- **Web Framework:** Streamlit
- **Model Serialization:** Pickle

---

## 📁 Project Structure
```
sms-spam-classifier/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── data/
│   └── spam.csv
│
├── models/
│   ├── model.pkl
│   └── vectorizer.pkl
│
├── notebooks/
│   └── spam_detector.ipynb
│
└── image.png
```

---

## ⚙️ How the System Works
1. User enters an Email or SMS message
2. Text is cleaned and preprocessed
3. TF-IDF vectorizer converts text into numerical features
4. Trained machine learning model predicts the class
5. Result (Spam / Not Spam) is displayed on the screen

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/sms-spam-classifier.git
cd sms-spam-classifier
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app
```bash
streamlit run app.py
```

---

## 📊 Dataset
- SMS Spam dataset stored in `data/spam.csv`
- Contains labeled messages (`spam` / `ham`)
- Used for training and evaluation

---

## ✅ Output
- **Spam** → Message is classified as spam
- **Not Spam** → Message is safe

---

## 🔮 Future Enhancements
- Multilingual spam detection
- Deep learning models (LSTM / BERT)
- Email inbox integration
- Model performance monitoring

---

## 👨‍💻 Author
**Ashish Sheoran**  
Aspiring Data Scientist | Machine Learning Enthusiast

---

## 📄 License
This project is for educational and learning purposes.
