# Quiz-Game
A Python-based interactive quiz game that tests your knowledge with True/False questions. Built using object-oriented programming principles with modular design.
Features

Interactive Quiz Interface: Command-line based question and answer system
Score Tracking: Real-time score updates and final score display
Question Bank Management: Easily customizable question database
Answer Validation: Immediate feedback on correct/incorrect answers
Progress Tracking: Shows current question number and remaining questions

Project Structure
quiz-game/
├── main.py           # Main game loop and initialization
├── quiz_brain.py     # QuizBrain class - handles game logic
├── question_model.py # Question class - data model for questions
└── data.py          # Question database
Classes

Question: Data model for individual quiz questions
QuizBrain: Core game engine that manages quiz flow, scoring, and user interaction

How to Play

Run the program
Answer True/False questions by typing "True" or "False"
Get immediate feedback on your answers
View your final score at the end

Usage
bashpython main.py
Sample Output
Q.1: The capital of France is Paris. (True/False): True
You got it right!
Your current score is: 1/1

Q.2: Python was created in 1995. (True/False): False
You got it right!
Your current score is: 2/2
Customization
Add your own questions to data.py in the format:
pythonquestion_data = [
    {"question": "Your question here", "correct_answer": "True"},
    {"question": "Another question", "correct_answer": "False"}
]
Requirements

Python 3.x
No external dependencies required

Perfect for learning object-oriented programming, class interactions, and building interactive console applications in Python.RetryClaude does not have the ability to run the code it generates yet.Claude can make mistakes. Please double-check responses.
