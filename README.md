# 😃 Sentiment_FER: Facial Emotion & Sentiment Recognition

This project combines **Facial Emotion Recognition (FER)** with **Sentiment Analysis** using deep learning and NLP techniques to understand human expressions from both facial images and textual data.

---

## 🔍 Project Objective

To build a dual-mode sentiment analysis system:
- 🎭 **Facial Emotion Recognition** – Identify emotions such as happy, sad, angry, etc., from human facial expressions.
- 🗣️ **Textual Sentiment Analysis** – Detect the sentiment behind user comments or messages using NLP.

---

## 🛠️ Features

- 🔍 CNN-based facial emotion detection using real-time webcam input
- 🧠 Trained on facial datasets like FER-2013
- 💬 Supports analysis of both image and text input
- 🖥️ Interactive interface for real-time demo and testing

---

## 💻 Technologies Used

### 🧠 Machine Learning & Deep Learning
- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn


### 🛠️ Tools
- NumPy, Pandas, Matplotlib
- Flask / Streamlit (for demo if applicable)

---

## 🗃️ Dataset

- **Facial Emotion Dataset**: [FER-2013](https://www.kaggle.com/datasets/msambare/fer2013)
- **Sentiment Dataset**: IMDb / Twitter / Custom scraped data (as per implementation)

---

## 🚀 Installation & Usage

```bash
# 1. Clone the repository
git clone https://github.com/aman1290/sentiment_FER.git
cd sentiment_FER

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the application
python app.py  # or main.py or streamlit run app.py depending on interface
