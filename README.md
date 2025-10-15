Spanish Practice Game
This is a simple, web-based quiz game designed to help users practice their Spanish language skills. The game is built as a single-page application using HTML, Tailwind CSS, and vanilla JavaScript. It's fully responsive and works on both desktop and mobile browsers.

Features
The quiz covers three key areas of Spanish vocabulary and grammar:

Acciones Habituales (Common Verbs): Users are tested on translating common Spanish verbs to English and vice-versa. The verb data is loaded dynamically from a CSV file.

Telling Time: Questions challenge the user to match the Spanish written form of a time (e.g., "Son las dos y cuarto") with its digital representation (e.g., "2:15").

Verbos Reflexivos (Reflexive Verbs): Users must complete sentences by choosing the correct reflexive pronoun (me, te, se, etc.) or the correct reflexive verb infinitive.

Core Gameplay Mechanics:

Multiple-Choice Format: Each question presents four possible answers.

Instant Feedback: After selecting an answer, the interface immediately shows whether the choice was correct or incorrect, along with a brief explanation.

Quiz Structure: Each session consists of 20 randomly selected questions (10 common verbs, 5 time questions, and 5 reflexive verb questions).

Summary Screen: At the end of the quiz, a summary screen displays the final score and a detailed review of all questions, showing the user's answer and the correct answer.

Replayability: Users can easily start a new quiz with a fresh set of questions from the summary screen.

How to Run the Game
This project is self-contained and does not require a web server or complex setup.

Prerequisites:

A modern web browser (like Chrome, Firefox, Safari, or Edge).

The Acciones Habituales - Sheet1.csv file must be in the same directory as the main HTML file.

Steps:

Clone or download the repository to your local machine.

Ensure the file Acciones Habituales - Sheet1.csv is present in the root directory.

Open the spanish_game.html file directly in your web browser.

The game will load, and you can start playing immediately.

File Structure
.
├── spanish_game.html               # The main application file containing all HTML, CSS, and JS.
├── Acciones Habituales - Sheet1.csv  # Data file containing Spanish verbs and their English translations.
└── README.md                       # This README file.

Technologies Used
HTML5

CSS3 with Tailwind CSS (loaded via CDN)

Vanilla JavaScript (ES6)

No external JavaScript libraries or frameworks (like React, Vue, etc.) are used, making the project lightweight and easy to understand.

