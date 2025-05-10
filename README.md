---
# 🧠 Quiz Game (Python)

A simple **True or False** quiz game built using Python OOP concepts. This project loads a list of trivia questions and checks your answers while keeping track of your score. Great for beginners practicing classes and loops!

## 📂 Project Structure

    quiz-game-start/
      ├── data.py
      ├── main.py
      ├── question_model.py
      └── quiz_brain.py

---
## 📝 Files Explained
### 1. data.py

This file contains a list called question_data which holds the quiz questions in a dictionary format.
Each question has:

    type

    difficulty

    category

    question

    correct_answer

    incorrect_answers

Example:

    {
      "type": "boolean",
      "difficulty": "easy",
      "category": "History",
      "question": "Kublai Khan is the grandchild of Genghis Khan?",
      "correct_answer": "True",
      "incorrect_answers": ["False"]
    }

### 2. question_model.py

This file defines the Question class. Each Question object stores:

    text: The question itself.

    answer: The correct answer.

    class Question:
        def __init__(self, text, answer):
            self.text = text
            self.answer = answer

### 3. quiz_brain.py

This file controls the quiz logic! It contains the QuizBrain class, which:

    Tracks the current question number.

    Keeps the score.

    Shows the next question.

    Checks if the answer is correct.

Key methods:

    still_has_questions() ➡️ Checks if more questions are left.

    next_question() ➡️ Asks the user and checks the answer.

    check_answer() ➡️ Compares user input with the correct answer.

### 4. main.py

This is the main driver file. It:

    Loads the questions from data.py.

    Creates Question objects.

    Starts the quiz loop.

- At the end, it prints your final score.

---
## 💪 What You Learn From This Project

- How to use classes and objects in Python.

- Looping through data (for loop).

- Working with lists and dictionaries.

- Simple user input validation.

- Keeping track of state (score, question number).

---

## 👤 Author

[![GitHub: bhagirathsinhp](https://img.shields.io/github/followers/bhagirathsinhp?label=Follow&style=social)](https://github.com/bhagirathsinhp)
[![LinkedIn: Bhagirath Parmar](https://img.shields.io/badge/-Bhagirath%20Parmar-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/bhagirath-parmar-385865269/)](https://www.linkedin.com/in/bhagirath-parmar-385865269/)


