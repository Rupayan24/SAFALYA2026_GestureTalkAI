![image alt](https://github.com/Rupayan24/SAFALYA2026_GestureTalkAI/blob/76e3202f2c502ffe91eb5b6f26095a35d4ac0acd/logo.png)



**AI-Powered Sign Language Interpreter, Translator & Learning Platform**

---

## 📌 Project Overview

**GestureTalk AI** is an AI-powered web application designed to bridge communication and education gaps for deaf and hard-of-hearing individuals. The platform performs **real-time sign language interpretation and translation** using computer vision and machine learning, while also providing a **sign-first learning ecosystem**.

Beyond interpretation, GestureTalk AI enables users to **learn sign language fundamentals**, track learning progress, access **mentor-led academic courses**, and receive guidance through an integrated AI chatbot — all through an accessible web interface.

![image alt](https://github.com/Rupayan24/SAFALYA2026_GestureTalkAI/blob/ae8f32245edd401ae2832b9285588125f3d518b4/SIGNLanguageIMG/Prototype_SS/Screenshot%202026-01-26%20082502.png)

---

## 🎯 Key Features

- 🤖 **Real-time Sign Language Interpretation**
  - Interprets hand gesture images using AI
  - Converts sign language gestures into accurate text
  - Works with a standard camera (no special hardware required)

- 📚 **Sign Language Learning Module**
  - Learn **alphabets, words, and numbers**
  - Short visual sign language videos
  - Automatic **progress tracking** for each user

- 🎓 **Inclusive Academic Courses**
  - Maths, English, and Science (Class 5–10)
  - Taught by mentors **entirely through sign language**
  - Accessible learning beyond basic sign language

- 💬 **AI Chatbot Assistance**
  - Guides users across the platform
  - Helps with navigation and sign language-related queries

- 🔐 **Login & Personalization**
  - User authentication
  - Personalized learning progress and experience

- 🎨 **Theme Customization**
  - Light/Dark mode support for better accessibility

---

![image alt](https://github.com/Rupayan24/SAFALYA2026_GestureTalkAI/blob/5bf560ce97859d64565f6ac891bb0ecf5b1ebd48/SIGNLanguageIMG/Prototype_SS/Screenshot%202026-01-28%20051720.png)

![image alt](https://github.com/Rupayan24/SAFALYA2026_GestureTalkAI/blob/b0396b6acfa54f41d28377992be1162e25baed01/SIGNLanguageIMG/Prototype_SS/Screenshot%202026-01-28%20052225.png)

![image alt](https://github.com/Rupayan24/SAFALYA2026_GestureTalkAI/blob/bf20bd8170a7521c9df29ddcea611f1da7e5eebd/SIGNLanguageIMG/Prototype_SS/Screenshot%202026-01-28%20052707.png)

![image alt](https://github.com/Rupayan24/SAFALYA2026_GestureTalkAI/blob/35044e36e8a07a148ce41b352c8aa40f095e024a/SIGNLanguageIMG/Prototype_SS/Screenshot%202026-01-28%20053024.png)

## 🧠 System Architecture

GestureTalk AI follows a **clean, modular, and scalable client–server architecture**:

- **Frontend:**  
  Built using **HTML, CSS, and JavaScript**  
  Handles UI, webcam input, learning modules, chatbot interface, and progress tracking.

- **Backend:**  
  Developed in **Python using FastAPI**  
  Manages API requests, communicates with the AI model, and ensures fast response times.

- **AI / ML Model:**  
  Built using **Python, TensorFlow, and Keras**  
  Performs hand gesture recognition using computer vision techniques and maps gestures to text outputs.

This architecture ensures real-time performance, scalability, and maintainability.


---

## ⚙️ Tech Stack

### 🌐 Frontend
- HTML  
- CSS  
- JavaScript  

### ⚙️ Backend
- Python  
- FastAPI  

### 🤖 AI / ML
- TensorFlow  
- Keras  
- Computer Vision (hand gesture recognition)

---
## ⭐ Unique Selling Points (USP)

- **Sign-first approach:** GestureTalk AI is designed around sign language from the ground up, not adapted later.
- **Beyond translation:** In addition to real-time sign language interpretation, the platform focuses on learning and education.
- **Integrated learning ecosystem:** Users can learn sign language basics with structured modules and progress tracking.
- **Inclusive academic education:** Mentor-led courses in Maths, English, and Science (Classes 5–10) taught entirely through sign language.
- **AI-powered architecture:** Uses a scalable web frontend, FastAPI backend, and TensorFlow–Keras model for real-time performance.
- **No special hardware required:** Works with a standard camera, making it accessible and easy to use.
- **Built-in AI chatbot:** Provides instant guidance, support, and platform navigation assistance.

---

## ▶️ How to Run the Project

### 1️⃣ Backend Setup
bash
-cd Backend
-pip install -r requirements.txt
-uvicorn main:app --reload

### 2️⃣ Frontend Setup
-Navigate to the Frontend folder
-Open index.html (or Landingpage/home.html) in a web browser
-Ensure the backend server is running for API communication

### 3️⃣ Model Testing (Optional)
To test the trained model locally using a webcam:
-cd Model
-python run_model.py

---

## 🏁 Conclusion
GestureTalk AI is not just a sign language interpreter—it is a complete, AI-powered ecosystem for communication, learning, and inclusive education. By combining real-time gesture interpretation, structured sign language learning, mentor-led academic courses, and intelligent user support, GestureTalk AI aims to bridge communication and education gaps and move closer to a future where accessibility is the standard, not an exception.

---

### Demo Video

[![IMAGE ALT TEXT](https://github.com/Rupayan24/SAFALYA2026_GestureTalkAI/blob/9f0ed65c62a1b6d01cd3598e79ab4d67281dd173/SIGNLanguageIMG/Prototype_SS/Screenshot%202026-03-30%20205558.png)](https://youtu.be/V4-FOgXQVWQ?si=zjt-n-1HRn3YOGsp)





