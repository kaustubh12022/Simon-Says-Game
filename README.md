🎮 Simon Says – Neon Edition

A modern neon-themed Simon Says memory game built using HTML, CSS, and JavaScript.
The game challenges players to remember and repeat an ever-growing sequence of colors, inspired by the classic Simon electronic game with a cyber-neon UI.

✨ Features

🎯 Progressive Levels – Each level adds a new color to the sequence

🌈 Neon Visual Effects – Glowing buttons, flashes, and smooth animations

⚡ Instant Feedback – Button flashes for system and user actions

🔁 Restart on Game Over – Press any key to restart after losing

🧠 Memory-Based Gameplay – Tests focus, memory, and reaction time

🖥️ Fully Responsive & Lightweight – Runs directly in the browser

🧩 How the Game Works

Press any key to start the game

Watch the board carefully as a color flashes

Click the buttons in the same order

Each correct round increases the level and sequence length

A wrong move ends the game and shows your score

🛠️ Tech Stack

HTML5 – Structure and layout 

index

CSS3 – Styling, neon effects, animations 

style

JavaScript (Vanilla) – Game logic and interactions 

script

No external libraries or frameworks are used.

📂 Project Structure
Simon-Says-Neon-Edition/
│
├── index.html        # Game layout and structure
├── style.css         # Styling and neon UI effects
├── script.js         # Game logic and interactions
├── logo.png          # Project logo / banner
├── .gitignore        # Git ignore rules
└── README.md         # Project documentation


.gitignore ensures system files, logs, editor configs, and images are excluded from version control 

.gitignore

🚀 How to Run Locally

Clone the repository

git clone https://github.com/your-username/simon-says-neon.git


Navigate into the folder

cd simon-says-neon


Open index.html in your browser
(No server or setup required)

🎨 UI Highlights

Circular classic Simon board

Central hub with level counter

Neon glow on button flash

Smooth press & error animations

Minimal dark cyberpunk background

🧠 Game Logic Overview

gameseq[] stores the generated color pattern

userseq[] tracks user input

On each level:

A random color is appended

User input is validated step-by-step

Incorrect input triggers Game Over + reset

🔮 Possible Improvements

🔊 Sound effects for each color

🏆 High-score tracking using localStorage

📱 Mobile touch optimizations

⏱️ Speed increase at higher levels

🎮 Strict / Hardcore mode

📸 Preview

📄 License

This project is open-source and free to use for learning and personal projects.
