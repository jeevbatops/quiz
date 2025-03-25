# React Quiz App

This is a simple quiz application built using React. It allows users to answer multiple-choice questions, track their correct answers, and navigate through a series of quiz questions.

## Features

- Dynamic quiz setup with a form
- Randomized multiple-choice answers
- Tracks correct answers
- Displays a loading screen while fetching questions
- Modal for showing results or messages

## Technologies Used

- React
- Context API for state management
- HTML & CSS

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/react-quiz-app.git
   ```
2. Navigate to the project folder:
   ```sh
   cd react-quiz-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```

## Project Structure

```
.
├── src
│   ├── App.js        # Main application component
│   ├── context.js    # Context API for global state management
│   ├── SetupForm.js  # Quiz setup form
│   ├── Loading.js    # Loading screen component
│   ├── Modal.js      # Modal for quiz results
│   ├── index.js      # Entry point for React
│   ├── styles.css    # Styling for the application
│
├── package.json      # Project dependencies and scripts
├── README.md         # Project documentation
```

## Usage

1. Start the app and configure the quiz through `SetupForm`.
2. Answer the multiple-choice questions presented.
3. Check results and continue to the next question.
4. The app dynamically updates the correct answer count.



