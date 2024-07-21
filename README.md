# React Quiz App

A quiz application built with React. It fetches questions from a server and allows users to answer them within a time limit. The app tracks the user's score and high score.

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
