# 😃 Sentiment_FER: Facial Emotion & Sentiment Recognition

This project combines **Facial Emotion Recognition (FER)** with **Sentiment Analysis** using deep learning and NLP techniques to understand human expressions from both facial images and textual data.

---
![Screen Recording 2025-06-06 013100](https://github.com/user-attachments/assets/7ae840aa-6c8d-4928-8b4f-23a5b5a42d80)

## 🔍 Project Objective

To build a dual-mode sentiment analysis system:
- 🎭 **Facial Emotion Recognition** – Identify emotions such as happy, sad, angry, etc., from human facial expressions.

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
- Flask 

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
python app.py 
