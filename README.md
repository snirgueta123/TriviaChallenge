# Trivia Game Application

## Overview
This project is a JavaFX-based Trivia Game that challenges players with multiple-choice questions. Each question has four possible answers, where only one is correct. The game awards or deducts points based on the player's selections and provides a comprehensive gameplay experience.

## Features
- **Question Bank:** Questions are read from a text file, where each question is followed by one correct answer and three incorrect options.
- **Interactive Gameplay:** Players answer questions displayed in a graphical interface. Each correct answer earns 10 points, while an incorrect answer deducts 5 points.
- **Randomized Questions:** Questions and their respective answers are displayed in a randomized order.
- **Game Progression:** The game prevents repeated questions within the same session and ends when the question pool is exhausted or the player chooses to quit.
- **Scoring System:** Displays the total score at the end of each game.
- **New Game Option:** Players can restart the game and try again.

## How to Play
1. **Start the Game:** Launch the JavaFX application. The first question will be displayed with four answer options.
2. **Select an Answer:** Choose one option by clicking the corresponding button.
3. **Score Updates:** Receive immediate feedback on whether your choice was correct, and your score will be adjusted.
4. **Progression:** Continue answering until the game ends.
5. **End Game:** View your final score and restart the game if desired.

## File Format
The trivia questions are stored in a text file named `trivia.txt` with the following format:
```
Question 1
Correct Answer
Incorrect Answer 1
Incorrect Answer 2
Incorrect Answer 3
Question 2
Correct Answer
Incorrect Answer 1
Incorrect Answer 2
Incorrect Answer 3
...
```

## Requirements
- Java Development Kit (JDK) 11 or higher.
- JavaFX SDK.

## Setup Instructions
1. Clone the repository or download the project files.
2. Ensure you have the required `trivia.txt` file in the root directory of the project.
3. Compile and run the application using your preferred IDE or command line.

## Example
Here is a simple example of gameplay:
1. **Question Display:**
   - "What is the capital of France?"
   - Options: `Berlin`, `Madrid`, `Paris`, `Rome` (randomized order).
2. **Player Choice:** Select `Paris`.
3. **Feedback:** "Correct! +10 points".
4. **Progression:** The next question appears.

## Class Design
- **Question:** Represents a single trivia question with its possible answers.
- **QuestionBank:** Manages the pool of questions and handles randomization.
- **TriviaGame:** Controls the game flow and scoring.
- **TriviaGUI:** Handles the graphical user interface and user interactions.

## Future Enhancements
- Add timed questions for increased difficulty.
- Include support for multiple players.
- Expand question categories and difficulty levels.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy playing the Trivia Game and test your knowledge!
