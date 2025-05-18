# 🏥 Multiple Disease Prediction App

This is a **Streamlit-based Web Application** that allows users to predict the likelihood of **heart disease, diabetes, and Parkinson’s disease** based on medical parameters. The app uses **machine learning models** to provide predictions.

---

## 🚀 Features
✅ **Predicts multiple diseases:** Heart Disease, Diabetes, and Parkinson’s Disease  
✅ **User-friendly interface** built using **Streamlit**  
✅ **AI-powered symptom checker** integrated with **Google Gemini API**  
✅ **Machine Learning models** trained on medical datasets  
✅ **Deployed on Streamlit Cloud** for easy access  

---

## 🛠️ Tech Stack
- **Python** (Scikit-Learn, Pandas, NumPy)
- **Streamlit** (for Web UI)
- **Google Gemini API** (for AI-powered symptom checking)
- **Machine Learning** (Logistic Regression, SVM, etc.)
- **GitHub** (Version Control)

---

## 📂 Project Structure
```
📦 multiple-disease-prediction-app
│-- app.py                 # Main Streamlit app
│-- model_loader.py        # Loads ML models
│-- requirements.txt       # Dependencies
│-- .env                   # Stores API keys (not committed)
│-- datasets/              # Contains datasets (if applicable)
│-- models/                # Pretrained models
│-- README.md              # Project documentation
```

---

## 🔧 Setup & Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/realakshatkumar/multiple-disease-prediction-app.git
cd multiple-disease-prediction-app
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up API Key (Google Gemini)
- Create a `.env` file in the project directory
- Add the following line:
```bash
GEMINI_API_KEY=your_api_key_here
```

### 4️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

---

## 🎯 Usage
1️⃣ Open the web app in your browser.
2️⃣ Enter the required medical parameters.
3️⃣ Click **Predict** to get the result.
4️⃣ Use the **AI-powered chatbot** for symptom checking.

---
Live App:
https://multiple-disease-prediction-app-01234.streamlit.app/

For redeployment:
```bash
git add .
git commit -m "Updated app"
git push origin main
```

---

## 🤝 Contributing
Feel free to **fork** the repository and submit a **pull request**. If you find any bugs, please open an issue.

---

### ✨ Created by [Akshat Kumar](https://github.com/realakshatkumar) 🚀

