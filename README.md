# Quiz Application

This is a simple quiz application built in Python. The application allows users to answer a series of questions, and at the end, it displays their final score. The questions are stored in a separate data file, and the application uses Object-Oriented Programming (OOP) to manage the quiz flow.

## Files and Directories

### `question_model.py`
This file contains the `Question` class that models the questions for the quiz. It stores the question text and the correct answer.

### `data.py`
This file contains the `question_data` list, which is a collection of questions and their corresponding correct answers. The data is structured as a list of dictionaries.

### `quiz_brain.py`
This file contains the `QuizBrain` class. It is responsible for managing the quiz, tracking the score, and checking the answers. It controls the quiz flow, including question display and answering logic.

### `ui.py`
This file contains the `QuizInterface` class, which manages the user interface for the quiz. It displays the questions and collects user input.

### `main.py`
This is the main file where the quiz is run. It initializes the quiz by creating a list of `Question` objects from the data, then it starts the quiz and displays the results at the end.

## Features

- Multiple choice-style quiz.
- Tracks the user's score as they answer each question.
- Displays the final score at the end of the quiz.
- Easy to extend by adding new questions to the `question_data` in `data.py`.

## How to Run

1. Clone or download the repository.
2. Ensure you have Python 3.7+ installed on your machine.
3. Install any necessary dependencies (if applicable).
4. Run the quiz application by executing the `main.py` file:

```bash
python main.py
