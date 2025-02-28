# AI-Based Fake News Detector

## 📌 Introduction

The **AI-Based Fake News Detector** is a machine-learning-powered web application that classifies news articles as either **Real** or **Fake**. The model is trained using a dataset of real and fake news articles and can help users verify the authenticity of news content.

## 🚀 Features

- **Machine Learning Model:** Uses Natural Language Processing (NLP) techniques to classify news articles.
- **User-Friendly Interface:** A simple and responsive UI built with Flask and Bootstrap.
- **Dark Mode Support:** Toggle between light and dark themes for a better user experience.
- **Fast Predictions:** Enter a news article and get an instant result.
- **Smooth Animations:** UI elements include fade-in effects for a modern look.

## 🛠️ Tech Stack

- **Backend:** Flask (Python)
- **Machine Learning:** Scikit-learn, Pandas, NumPy, TF-IDF Vectorization
- **Frontend:** HTML, CSS, Bootstrap 5, JavaScript
- **Dataset:** Real and fake news articles dataset

## 📂 Project Structure

```
Fake-News-Detector/
│── static/               # CSS, JS, Images
│── templates/            # HTML templates
│   ├── index.html        # Main input page
│   ├── result.html       # Result page
│── model/                # Machine learning model files
│── app.py                # Flask application
│── preprocess.py         # Data preprocessing script
│── train_model.py        # Model training script
│── requirements.txt      # Project dependencies
│── README.md             # Project documentation
```

## 🛠️ Installation & Setup

### 1️⃣ **Clone the Repository**

```sh
git clone https://github.com/yourusername/Fake-News-Detector.git
cd Fake-News-Detector
```

### 2️⃣ **Set Up a Virtual Environment** (Optional but Recommended)

```sh
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate     # For Windows
```

### 3️⃣ **Install Dependencies**

```sh
pip install -r requirements.txt
```

### 4️⃣ **Run the Flask Application**

```sh
python app.py
```

### 5️⃣ **Access the Web Application**

Open your browser and go to:

```
http://127.0.0.1:5000/
```

## 🏗️ How It Works

1. **User enters news text** on the homepage.
2. **Text is processed** and converted into numerical features.
3. **Trained ML model** predicts whether the news is **Real** or **Fake**.
4. **Result is displayed** on the UI with proper highlighting.

## 📌 Example Output

If the news is real:
✅ **REAL NEWS**

> "This news is authentic."

If the news is fake:
❌ **FAKE NEWS**

> "This news is not trustworthy."

## ⚡ Future Improvements

- Improve the **accuracy** with deep learning models (LSTM, BERT, etc.).
- Implement **database storage** for analyzed news articles.
- Add **API support** to allow external apps to use the classifier.
- Allow users to **upload articles** as files for bulk verification.

## 🤝 Contributing

If you'd like to contribute to this project, feel free to submit a pull request or report issues!

## 📝 License

This project is open-source and available under the **MIT License**.

---

### 🌟 Show Some Love

If you like this project, consider giving it a ⭐ on GitHub!

---

💡 **Developed by:** Your Name\
📧 Contact: musabbinnadeem\@gmail.com

