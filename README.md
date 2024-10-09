# Quiz App

### Description

This Quiz App is a simple and interactive web-based application built using HTML, CSS, and JavaScript. It allows users to take quizzes, track their progress, and manage their accounts with a secure login and sign-up system. The app utilizes Chrome local storage to store user data, including quiz scores and account details, providing a seamless experience without the need for a backend database.

##  Features
- **Sign Up & Login**: Users can create an account and log in securely to access personalized quiz data.
- **Quiz Functionality**: The app presents multiple-choice questions with immediate feedback on answers.
- **Local Data Storage**: User information and quiz scores are stored using Chrome local storage, ensuring data persistence across sessions.
- **Responsive Design**: The app is fully responsive, providing an optimal experience across devices.

## Technologies  Used
- **HTML**: For structuring the app's interface.
- **CSS**: For styling and responsive design.
- **JavaScript**: For quiz functionality, login/sign-up, and handling local storage.
- **Chrome Local Storage**: To store user data and quiz scores locally in the browser.

# Setup Instructions:
1 *Clone the repository*.
```bash
git clone https://github.com/yourusername/Quiz
```
2 *Navigate to the Project Directory:*.
```bash
cd quiz-app
```
3 *Open the Application: Open `index.html` in any web browser:*.
```bash
open index.html
```
Alternatively, right-click the `index.html` file and choose "Open with" to select your browser.

4 *Start Using the App*:

- Sign up or log in to begin taking quizzes.  
- Your data, including quiz results, will be stored locally in Chrome's local storage.

## Frontend Implementation

 **HTML & CSS**:
 
- The user interface is built with HTML for structure and CSS for styling. The layout is responsive, ensuring usability across various screen sizes.
- *Key components include*:
  - A sign-up and login form for user authentication is needed.
  - A Quiz Interface where users can answer multiple-choice questions.
  - A Scoreboard that shows users their progress and scores.
 
**JavaScript**:

- *JavaScript handles all the core functionality*:
  - User Authentication: Users can sign up and log in with credentials stored locally in the browser.
  - Quiz Logic: The app dynamically loads questions, tracks user answers, and provides immediate feedback.
  - Local Storage: The app saves user data (e.g., quiz scores and account details) using Chrome local storage, ensuring that the data is accessible even after refreshing the page or closing the browser.

## Backend Implementation

Since this is a frontend-only application, no backend server is involved. All user data and quiz scores are stored locally within the browser using Chrome's local storage.

- **Chrome Local Storage**:
   - User data (e.g., login credentials, quiz scores) is securely stored in the browser.
   - Data is persistent across sessions, meaning users can return to the app later and still access their information.
   - No external server or database is required, making the app lightweight and easy to run on any browser.

## How to Use
- **Sign Up**: Create a new account to use the app.
- **Login**: Log in to access your quiz dashboard.
- **Take Quiz**: Answer questions and receive feedback on your performance.
- **Track Progress**: Review your scores and quiz history from the local storage data.

# Deployed Version:
  Deployed Link: [Quiz](https://athul64.github.io/Quiz/)
