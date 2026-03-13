# 📩 SMS / Email Spam Classifier

A **Machine Learning powered web application** that classifies SMS or Email messages as **Spam** or **Not Spam** using Natural Language Processing (NLP).

The application is built using **Python, Streamlit, and Scikit-learn** and provides a simple interface where users can enter a message and instantly get predictions.

---

## 🚀 Features

- Machine Learning based spam detection
- Text preprocessing using **NLTK**
- **TF-IDF Vectorization**
- Trained classification model
- Interactive UI using **Streamlit**
- Real-time prediction

---

## 🛠 Tech Stack

- Python
- Streamlit
- Scikit-learn
- NLTK
- Pickle
- TF-IDF Vectorizer

---

## 📂 Project Structure

```
sms-spam-checker
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── spam-dataset.csv
├── requirements.txt
├── setup.sh
├── nltk.txt
├── README.md
```

---

## 📊 Dataset

The model was trained using the **SMS Spam Collection Dataset**.

Dataset Link:  
https://www.kaggle.com/datasets/shravan3273/sms-spam

---

## ⚙️ Installation

### 1 Clone the Repository

```bash
git clone https://github.com/Vivekkjhaa/sms-spam-checker.git
cd sms-spam-checker
```

### 2 Install Dependencies

```bash
pip install -r requirements.txt
```

### 3 Download NLTK Resources

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## ▶️ Run the Application

Start the Streamlit app:

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🧪 Usage

1. Enter an **SMS or Email message** in the text area.
2. Click the **Predict** button.
3. The model will classify the message as:

- 🚫 **Spam**
- ✅ **Not Spam**

---

## 🧠 How It Works

The system follows these steps:

1. **Text Preprocessing**
   - Lowercasing
   - Tokenization
   - Removing stopwords
   - Removing punctuation
   - Stemming using Porter Stemmer

2. **Feature Extraction**
   - TF-IDF Vectorization converts text into numerical vectors.

3. **Prediction**
   - The trained machine learning model predicts whether the message is spam or not.

---

## 💡 Example

**Input Message**

```
Congratulations! You have won a free lottery ticket. Claim now!
```

**Prediction**

```
Spam
```

---

## 🤝 Contributing

Contributions are welcome.

You can help by:

- Reporting bugs
- Suggesting new features
- Creating pull requests

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**Vivek Kumar**

If you found this project useful, please consider giving it a ⭐ on GitHub.
