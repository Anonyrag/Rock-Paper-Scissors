Rock–Paper–Scissors Game – Learning Project

A progressively built Rock–Paper–Scissors game developed using HTML, CSS, and JavaScript, starting from basic inline logic and evolving into a fully interactive, modular, and UI-driven web game.

This repository is intended for educational purposes, showcasing how a simple idea grows into a structured frontend application through refactoring, state management, event handling, and UI design.

---

Project Overview

The project demonstrates:

* Core JavaScript logic
* Randomized gameplay
* Score tracking and persistence
* DOM manipulation
* Event-driven programming
* Separation of concerns (HTML, CSS, JS)

Each version represents a **learning milestone**, not just a feature update.

---

Project Versions

🔹 Version 1 – Inline Logic & Alerts

File: `Rock-Paper-Scissors V-01.html`

* Game logic written directly inside button `onclick` handlers
* Random computer move using `Math.random()`
* Results shown using `alert()`
* No score tracking

Concepts learned:

* Conditional logic
* Random number generation
* Basic game rules

---

🔹 Version 2 – Functions & Code Reuse

File: `Rock-Paper-Scissors V-02.html`

* Introduced `playGame(playerMove)`
* Extracted computer logic into `pickComputerMove()`
* Reduced repeated code
* Improved readability

Concepts learned:

* Functions and parameters
* Code reuse
* Cleaner control flow

---

🔹 Version 3 – Persistent Score Tracking

File: `Rock-Paper-Scissors V-03.html`

* Added win / loss / tie tracking
* Stored score using `localStorage`
* Score persists after page refresh
* Reset score functionality

Concepts learned:

* JavaScript objects
* `localStorage` usage
* JSON parsing and stringifying
* Application state management

---

🔹 Version 4 – UI-Based Gameplay

File: `Rock-Paper-Scissors V-04.html`

* Results displayed directly on the page
* Move history shown (player vs computer)
* Live score updates in the UI
* Better separation between logic and rendering

Concepts learned:

* DOM manipulation
* UI synchronization with state
* Cleaner user experience

---

Final Versions (Separated Files)

🔹 Version 5 – Modular HTML, CSS & JS

Files:

* `Rock-Paper-Scissors V-05.html`
* `Rock-Paper-Scissors V-05.css`
* `Rock-Paper-Scissors V-05.js`

This version introduces **proper separation of concerns**:

* HTML handles structure
* CSS handles styling and layout
* JavaScript handles logic and state

Features:

* Styled UI with icons
* Persistent score tracking
* Dynamic DOM updates
* Reset score button

Concepts learned:

* Project structure
* Clean architecture
* Maintainable frontend design

---

🔹 Version 6 – Advanced Interactions & Auto Play (Final)

Files:

* `Rock-Paper-Scissors V-06.html`
* `Rock-Paper-Scissors V-06.css`
* `Rock-Paper-Scissors V-06.js`

The most advanced and complete version.

Additional features:

* Auto-play mode using `setInterval()`
* Start / stop auto-play toggle
* Keyboard controls

  * `R`, `P`, `S` → Play moves
  * `A` → Auto play
  * `Backspace` → Reset confirmation
* Reset confirmation dialog
* Fully event-driven (no inline JS)

Concepts learned:

* Event listeners
* Timers (`setInterval`, `clearInterval`)
* Keyboard events
* UI state management
* Defensive UX patterns

---

Features Across All Versions

* Rock, Paper, Scissors gameplay
* Random computer opponent
* Win / Lose / Tie logic
* Score tracking and persistence
* Reset functionality
* Auto play simulation
* Keyboard and mouse interaction

---

Educational Uses

This repository is ideal for:

* JavaScript beginners learning through games
* Understanding how frontend logic evolves
* Practicing refactoring and clean code
* Learning DOM manipulation and events
* Preparing for frameworks like React or Vue

Because the versions are incremental, this repo works as a learning timeline, not just a finished project.

---

How to Run

1. Clone or download the repository
2. Open any `.html` file in a browser
3. For final versions, ensure CSS, JS, and `icons/` folder remain in the same structure

No libraries, build tools, or setup required.

---
Possible Future Enhancements

* Best-of-N rounds
* Difficulty levels
* Sound effects and animations
* Mobile responsiveness
* Conversion to React using hooks

---

License

This project is free to use for learning, teaching, and personal development.
You are encouraged to fork, modify, and extend it.

---

Final thought

This repository doesn’t just show *what* you built — it shows how you learned.
That’s exactly the kind of signal recruiters and reviewers respect.
