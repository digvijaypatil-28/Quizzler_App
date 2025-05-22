# 🧠 Quiz App

This is a simple **GUI-based quiz application** built using Python. The app tests your general knowledge using a series of True/False questions. 
It uses **OOP (Object-Oriented Programming)** principles to manage questions, quiz logic, and user interface.

## 📂 Project Structure
quiz-app/
├── main.py # Main driver code
├── question_model.py # Contains the Question class
├── data.py # Contains quiz question data (dictionary format)
├── quiz_brain.py # Logic to handle quiz flow
└── ui.py # GUI using tkinter

## 🛠️ Requirements

-  Python 3.8+
- `tkinter` (usually comes pre-installed with Python)



## 🚀 How to Run

1. **Clone the repository** (or download the files):
   ```bash
   git clone https://github.com/your-username/quiz-app.git
   cd quiz-app

## 📘 How It Works

The questions are stored in data.py as a list of dictionaries.

question_model.py defines the Question class, each instance representing a question and its correct answer.

quiz_brain.py manages the quiz logic: tracking the score, checking answers, and going to the next question.

ui.py builds a GUI using tkinter, displaying questions and handling user input via buttons.

## 🎮 Features

✅ Clean and interactive GUI

✅ Real-time score tracking

✅ Immediate feedback on each answer

✅ Easily customizable questions via data.py

## 👨‍💻 Author

Made with ❤️ by Digvijay Patil
