Hangman - Months Edition
​This repository contains a dual-implementation of the classic word-guessing game, specifically themed around the 12 months of the year. The project features a modern, feature-rich web application and a classic terminal-based C++ console engine.  
​🚀 Features
​Web Version (HTML/CSS/JS)
​Authentication System: A full login and registration system that persists user accounts using localStorage.  
​Password Security: Includes a visual strength meter with regex-based validation for length and complexity.  
​Dynamic Game Engine: Uses an SVG gallows that reveals body parts (Head → Body → Arms → Legs) upon wrong guesses.  
​Interactive UI: Features an on-screen keyboard, a hint system for each month, and retro-themed typography.  
​Persistent Dashboard: Tracks detailed statistics including win rates, current/best streaks, and a 10-game history log.  
​Data Portability: Allows users to export their statistics as a .txt file or import/reset data via JSON.  
​Console Version (C++)
​Modular Architecture: Built using struct and vector containers for efficient word and hint management.  
​ASCII Graphics: Displays the hangman state using traditional text-based art in the terminal.  
​Session Stats: Provides a "mini dashboard" showing total wins and losses during the current program run.  
​🛠️ Technology Stack
Feature Web Version Console Version
Language HTML5, CSS3, Vanilla JavaScript (ES6+) C++ (Standard Library)
Visuals SVG Graphics & CSS Transitions ASCII Terminal Art
Storage localStorage (Web Storage API) In-memory (Session only)
Logic JSON, Array Methods, Regex Vectors, Structs, Algorithms
💻 Setup and Installation
​Web Version (Recommended)
​Running the game via a local server is recommended to ensure localStorage functions correctly across all browsers.  
​Windows (Automated): Double-click start_server.bat to launch a local Python web server and open the game automatically at http://localhost:8000/hangman.html.  
​Manual Method:
​Navigate to the project folder.  
​Start a server using Python: python -m http.server 8000.  
​Open http://localhost:8000/hangman.html in your browser.
C++ Console Version
​Compile: Use a C++ compiler (like g++) to compile hangman.cpp.  
​Run: Execute the generated file in your terminal or command prompt.  
​📁 File Structure
​hangman.html: The complete web application containing HTML structure, CSS styling, and JavaScript logic.  
​hangman.cpp: The source code for the terminal-based version.  
​start_server.bat: A utility script for Windows users to launch the local environment.  
​⚠️ Known Limitations
​Security: Passwords in the web version are stored as plain text in localStorage, which is suitable for academic demonstration but not for production use.  
​Persistence: Clearing browser cookies or history will wipe all stored player accounts and statistics.  
​Compatibility: The web version requires a modern browser (post-2015) and does not support Internet Explorer.  
​Author: Yashvendra Singh
