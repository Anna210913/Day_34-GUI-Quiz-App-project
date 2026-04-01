# Day_34-GUI-Quiz-App-project
This project is an interactive Quiz App with a Graphical User Interface (GUI) built using Python and tkinter.

The app presents users with multiple-choice questions, tracks their score, and provides immediate feedback all within a clean, responsive interface. This project is structured using multiple Python files and classes, making it cleaner (no repeating code) and closer to real-world application design.


## How the code is arranged:
🧩 data.py:
Contains the raw quiz questions (usually from an API or predefined dataset)

🧩 question_model.py:
- Defines the Question class
- Each question has:
    Question text
    Correct answer

🧩 quiz_brain.py:
- Handles the core logic of the quiz;
    Tracks question number
    Checks answers
    Keeps score
    Determines if there are more questions

🧩 ui.py(QuizInterface):
- Manages the GUI using tkinter
- Displays questions on a canvas
- Handles button clicks (True/False)
- Provides visual feedback (e.g., color changes)
- Updates the score dynamically

## How the project works:
- Once the user runs the code, question data is loaded and converted into Question objects
- A QuizBrain object manages quiz logic
- The QuizInterface:
    Displays each question
    Waits for user input
    Sends answers back to QuizBrain
- The UI updates based on correctness and moves to the next question

## What I learned:
- Structuring GUI code using classes instead of procedural code
- Separating logic from interface
- Cleaning API data (e.g., converting &quot; to ")
- Ensuring questions display correctly
- Python Typing (Type Hints);
    Using type hints to improve code readability and clarity
    Example: def check_answer(answer: str) -> bool:
- Object-Oriented Programming (OOP) in practice
- Breaking a project into multiple classes
- Assigning clear responsibilities to each component
- Providing instant feedback
- Updating scores live


This project marked a big step forward in building structured, scalable applications. By combining multiple classes, GUI design, and clean data handling, it demonstrated how to build a more professional and maintainable Python application.

It’s a great example of moving from small scripts to well-organised software systems.
