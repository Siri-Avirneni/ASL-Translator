# 🎧 Audio to Sign Language Translator

## 📌 Project Overview

This project is a Django-based web application that converts **spoken audio into sign language output**. It is designed to bridge the communication gap between hearing individuals and deaf-mute people.

The system captures voice input through a microphone, converts it into text, processes the text, and displays corresponding **sign language videos**.

---

## 👥 Team Members

* A. Prianka
* A. Siri 
* A. Niranjan 

---

## 🚀 Features

* 🎤 Speech-to-Text using microphone input
* 🔐 User Registration and Login system
* 🧠 Text processing and keyword extraction
* 🎥 Sign language output using pre-recorded videos
* 🌐 Simple and user-friendly web interface

---

## 🛠️ Technologies Used

* Python
* Django
* SpeechRecognition
* PyAudio
* OpenCV
* NumPy
* HTML, CSS, JavaScript

---

## ⚙️ Working Process

1. User logs into the system
2. Provides audio input through microphone
3. Speech is converted into text using SpeechRecognition
4. Text is processed to extract keywords
5. Each keyword is mapped to a corresponding sign language video from the assets folder
6. Videos are displayed sequentially as output

---

## 📂 Project Structure

```bash
ASL-Translator/
│── manage.py
│── db.sqlite3
│── requirements.txt
│── README.md
│
├── A2SL/        # Django project files
├── assets/      # Sign language videos
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Siri5ct/ASL-Translator.git
cd ASL-Translator
```

### 2. Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Run the Server

```bash
python manage.py runserver
```

### 6. Open in Browser

http://127.0.0.1:8000/

---

## 📸 Screenshots

(Add screenshots from your project here)

---

## ⚠️ Limitations

* Limited vocabulary based on available video dataset
* Accuracy depends on clarity of speech input
* Uses predefined videos instead of real-time gesture generation

---

## 🔮 Future Improvements

* Expand sign language dataset
* Improve speech recognition accuracy
* Add real-time gesture animation
* Support multiple languages

---

## 📄 License

This project is developed for academic purposes only.
