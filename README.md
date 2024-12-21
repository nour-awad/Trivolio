# Trivolio

## Overview
Trivolio is a Trivia Quiz Website, a fun and educational web application that allows users to test their knowledge on various topics through engaging quizzes. Users can select categories, answer timed questions, track their scores, and compare their performance on a leaderboard. This app is built with React and integrates with a trivia API to fetch dynamic questions.

---

## Features

- **Home Page:** Welcome page introducing the app with a "Play" button.
- **Category Selection:** Choose a quiz category from a dropdown or button interface.
- **Dynamic Quiz Flow:** Answer trivia questions with real-time score tracking.
- **Timer:** Countdown timer for each question to increase the challenge.
- **Leaderboard:** View top scores from local storage or API.
- **Performance Insights:** Visualize performance analytics using charts.
- **Answer Feedback:** Instant feedback on whether answers are correct or incorrect.
- **Customizable Settings:** Adjust app settings, including difficulty levels and themes.
- **About Page:** Information about the app and the development team.

---

## Tech Stack

- **Frontend:** React, React Router, CSS Modules
- **API Integration:** [Open Trivia Database](https://opentdb.com/)
- **Data Visualization:** Chart.js
- **State Management:** React Hooks (useState, useEffect)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nour-awad/Trivolio.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Trivolio
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

---

## Usage

1. Launch the app by visiting `http://localhost:5173` in your web browser.
2. Choose a quiz category and start answering questions.
3. Track your score and view performance insights after completing the quiz.
4. Check the leaderboard to compare scores.

---

## Components Overview

### **Nour**
- `App.jsx`: Main app structure and routing.
- `TriviaQuestion.jsx`: Dynamic question rendering.
- `Footer.jsx`: Static footer with navigation links.

### **Leila**
- `CategorySelector.jsx`: Dropdown or buttons for selecting categories.
- `Timer.jsx`: Countdown timer for questions.
- `Home.jsx`: Welcome page with app description.

### **Ahmed**
- `ScoreTracker.jsx`: Displays the user's current score.
- `Leaderboard.jsx`: Shows top scores from storage/API.
- `LoadingSpinner.jsx`: Displays while data is being fetched.

### **Faris**
- `Analytics.jsx`: Displays performance insights with visual charts.
- `AnswerFeedback.jsx`: Shows feedback for correct/incorrect answers.
- `About.jsx`: Static page with app and team information.

---

## API Integration
The app fetches trivia questions from the [Open Trivia Database](https://opentdb.com/). The API provides a variety of categories and difficulty levels to ensure a dynamic quiz experience.

---

## Future Enhancements

- Add user authentication for personalized experiences.
- Allow users to create custom quizzes.
- Enable sharing scores on social media.
- Implement more themes for enhanced UI customization.

---

## License
This project is licensed under the MIT License.

---

## Contact
For questions or suggestions, please contact the development team at nour.awad094@gmail.com
