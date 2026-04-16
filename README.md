# Emotion Detector Application

## 📌 Project Overview

This project is an AI-based Emotion Detection web application developed using the IBM Watson NLP library. The application analyzes user input text and detects emotions such as **joy, anger, sadness, fear, and disgust**, along with the dominant emotion.

---

## 🚀 Features

* Detects multiple emotions from input text
* Identifies the dominant emotion
* REST API built using Flask
* Error handling for invalid inputs
* Unit testing included
* Static code analysis performed

---

## 🛠️ Technologies Used

* Python
* Flask
* IBM Watson NLP API
* Requests Library
* Unittest (for testing)
* Flake8 (for static analysis)

---

## 📂 Project Structure

EmotionDetection/

* **init**.py
* emotion_detection.py

server.py
test_emotion_detection.py

---

## ⚙️ Installation & Setup

1. Clone the repository:

```
git clone https://github.com/shrutiyl/emotion-detector.git
```

2. Navigate to the project directory:

```
cd emotion-detector
```

3. Install dependencies:

```
pip install flask requests
```

---

## ▶️ How to Run the Application

Run the Flask server:

```
python server.py
```

Open browser:

```
http://127.0.0.1:5000/emotionDetector?textToAnalyze=I am happy
```

---

## 🧪 Running Tests

Run unit tests:

```
python test_emotion_detection.py
```

---

## 📊 Example Output

```
{
  "anger": 0.01,
  "disgust": 0.01,
  "fear": 0.02,
  "joy": 0.92,
  "sadness": 0.04,
  "dominant_emotion": "joy"
}
```

---

## ⚠️ Error Handling

* Returns error message for empty input
* Handles invalid API responses

---

## 📈 Static Code Analysis

This project uses **flake8** for code quality checks:

```
flake8 server.py
```

---

## 🤝 Contribution

All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.

---

## 📄 License

This project is licensed under the Apache 2.0 License.

---

## 👩‍💻 Author

Shruti Yeole
