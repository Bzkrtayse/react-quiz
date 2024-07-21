# React Quiz App

The React Quiz App is a simple React application that allows users to take a quiz with multiple-choice questions.
The app fetches quiz questions from a local server, tracks the user's progress, calculates their score,
and displays the results at the end of the quiz.

![react-quiz-1](https://github.com/user-attachments/assets/023d33c0-bb75-416f-a875-4b5f41db0403)

![react-quiz-2](https://github.com/user-attachments/assets/ff406dcc-065f-4b96-8d32-fb47abe64272)

![react-quiz-3](https://github.com/user-attachments/assets/19469a09-cabd-42e2-b0b1-f5a5af121d00)

![react-quiz-4](https://github.com/user-attachments/assets/a5383a08-a527-40fe-9cca-1cadcb2d8970)


## Features

- **Loader:** Displays a loading spinner while the data is being fetched.
- **Error:** Displays an error message if there is an issue fetching the data.
- **StartScreen:** Initial screen prompting the user to start the quiz.
- **Question:** Displays the current question and possible answers.
- **NextButton:** Button to move to the next question.
- **Progress:** Shows the user's progress through the quiz.
- **FinishScreen:** Displays the user's final score and high score.
- **Timer:** Countdown timer for each question.
- **Footer:** Contains the timer and next button.

## Installation

1. Clone the repository:

   `git clone https://github.com/your-username/quiz-app.git`

2. Navigate to the project directory:

   `cd react-quiz`

3. Install dependencies:

   `npm install`

## Usage

1. Start the server to fetch questions

   `npm run server`

2. Start the development server:

   `npm start`

3. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

- `src/`: Contains all the source code.
- `components/`: Contains React components `Header`, `Main`, `Loader`, `Error`, `StartScreen`, `Question`, `NextButton`, `Progress`, `FinishScreen`, `Footer`, `Timer`,`DateCounter`.
- `contexts/`: Contains context file `QuizContext.js`.
- `index.js`: Main entry point.
- `index.css`: Global styles.
