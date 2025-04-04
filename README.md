# Memory-Game in LWC
A Salesforce-based interactive memory matching game built using Lightning Web Components (LWC) where users flip cards to find matching pairs and get rated based on performance.

# Overview
This project is a Memory Matching Game built using Salesforce Lightning Web Components (LWC). Players flip over pairs of cards to find matches. The game tracks the number of moves, displays a timer, and gives a star rating based on performance. When all matches are found, a modal displays the results with an option to play again.

# Features
- **Card Matching Logic: Users flip cards to find matching pairs. Matched cards stay visible.**
- **Move Counter: Tracks the number of moves (a move is defined as flipping two cards).**
- **Timer: Automatically starts on the first move and tracks how long the user takes to complete the game.**
- **Victory Modal: When all matches are found, a modal appears showing total moves, time taken, and a performance-based star rating.**
- **Reset Functionality: Users can restart the game at any time by clicking the shuffle icon.**
- **Star Rating System: Displays 1 to 3 stars based on how efficiently the user completes the game.**
- **Responsive UI: Built with Salesforce Lightning Design System (SLDS) and styled with FontAwesome icons.**

# How It Works
- **Card Rendering: The app displays 16 cards (8 unique pairs) randomly shuffled.**
- **Matching Logic: When two cards of the same type are selected, they are marked as matched.**
- **Mismatch Handling: If selected cards don't match, they flip back after a brief delay.**
- **Completion Detection: When all cards are matched, the timer stops and a modal appears with the final score.**
- **Reset Function: Clicking the shuffle icon resets all game variables and reshuffles the cards for a new game session.**
