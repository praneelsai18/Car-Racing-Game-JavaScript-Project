Car Racing Game – JavaScript Project

A simple and interactive Car Racing Game developed using HTML, CSS, and JavaScript.
The player controls a car using keyboard arrow keys and avoids collisions with randomly generated opponent cars while the score increases over time.

Features

Smooth car movement using keyboard controls
Randomly generated opponent cars
Moving road animation for realistic effect
Collision detection and game over logic
Live score and high score display
Responsive and lightweight design
Real-time updates using requestAnimationFrame

Technologies Used

HTML5 – Game structure
CSS3 – Styling and layout
JavaScript (ES6) – Game logic and interactivity
VS Code + Live Server – Development and testing

Project Structure
Car-Racing-Game/
│
├── index.html
├── style.css
├── game.js
├── car.png
├── opponent car.png
└── README.md

How to Run the Project

Method 1: Using Live Server (Recommended)
Open the project folder in Visual Studio Code
Install Live Server extension (by Ritwick Dey)
Right-click on index.html
Select Open with Live Server
The game will open in your browser at:
http://127.0.0.1:5500/index.html

Method 2: Without Live Server
Open the project folder
Double-click index.html
The game will run in your default browser
(Live Server is recommended for auto-refresh while editing)

Controls
Key	Action
↑ Arrow Up	Move forward
↓ Arrow Down	Move backward
← Arrow Left	Move left
→ Arrow Right	Move right
Game Logic Overview

DOM elements are selected using document.querySelector()
Keyboard events track user input
Road lines and opponent cars are generated dynamically
Collision detection ends the game
Score increases continuously during gameplay

Demo

Start the game by clicking "Click here to start the game"
Avoid opponent cars and survive as long as possible to score high.

Future Enhancements

Add background music and sound effects
Multiple difficulty levels
Mobile touch controls
Improved graphics and animations
High score storage using localStorage

Author

G.SAI PRANEEL
Computer Science Engineering Student
Beginner Front-End & JavaScript Developer

License
This project is open-source and free to use for educational purposes.

If you like this project, don’t forget to star the repository!
