# TJ-Tasks-2025-Shruti_Yadav

## Project: Tic-Tac-Toe Game in HTML/CSS/JS

---

## Task Prompt

See detailed requirements in the attached [prompt.txt](prompt.txt) file.

> *Summary of requirements:*
>
> - Self-contained HTML/CSS/JS file with pastel-modern UI
> - Scoreboard for X Wins, O Wins, Draws
> - Responsive, animated pastel-styled 3x3 game board
> - Real-time status and win/draw detection (8-patterns)
> - Replay and Reset buttons (score management)
> - Keyboard accessibility (focus styles, tab navigation)
> - No external dependencies; ready to run in browser
> - Modern UI with gradients, shadows, hover/focus states
> - Scales gracefully on mobile
> - Clear code comments

---

## Approach and Algorithm

This project implements the above requirements using plain HTML, CSS, and vanilla JavaScript with a modern pastel theme and responsive UI.

*Algorithm Steps:*
- Initialize a 3x3 board state array to track moves.
- Alternate turns between Player X and Player O.
- After each move, check for a winner using all standard win patterns.
- Detect a draw if all cells are filled, with no winner.
- Display real-time game status and update the scoreboard (X wins, O wins, draws).
- Provide replay (continue with scores) and reset (clear scores and restart) buttons.
- Offer a theme toggle for switching between pastel color schemes.
- Ensure full keyboard accessibility and support for users with assistive technologies.

---

## Challenges and Learnings

Building an accessible, keyboard-friendly interface was rewarding. Using CSS gradients and pastel palettes achieved a soft, modern look. DOM state management and live updates in vanilla JS improved my logic and event-handling skills. AI tools like Perplexity and ChatGPT supported and refined my coding approach.

---

## Screenshots of Final Output

![Game screenshot](Screenshot (182).png)

---

## How to Run

- Clone or download this repository.
- Open index.html in a modern web browser.
- Enjoy playing the Tic-Tac-Toe game with live status and scoreboard.

---

## Technologies Used

- HTML5
- CSS3 (gradients, flexbox, grid)
- JavaScript (ES6)
- Accessibility features (ARIA roles, tab navigation)
- AI tools (Perplexity, ChatGPT for guidance and best practices)

---

## Attached Files

- [prompt.txt](prompt.txt): Exact requirements and conditions for this task

---

This README was prepared by Shruti Yadav.
