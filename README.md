# 🃏 War Card Game (Async JavaScript Practice)

A fully functional, browser-based "War" card game built with Vanilla JavaScript, HTML, and CSS. This project focuses on mastering **Asynchronous JavaScript**, **REST API integration**, and **DOM Manipulation**.

## 🚀 Live Demo
[Insert your GitHub Pages link here]

## 🧠 Key Features & Technical Learnings

### 1. Asynchronous API Integration
- Utilized the **Deck of Cards API** to manage deck creation, shuffling, and card drawing.
- Implemented **Async/Await** patterns to handle network requests, ensuring a non-blocking UI experience.
- Managed **State** globally to track `deckId`, `remainingCards`, and player scores.

### 2. Game Logic & "Face Card" Mapping
- Developed a custom winner-determination algorithm that handles numerical values vs. face cards (Jack, Queen, King, Ace).
- Used **Array Methods** and objects to map card strings to numeric values for comparison.

### 3. Professional UI/UX
- Real-time scoreboard updates using DOM manipulation.
- Dynamic button states: "Draw" button automatically disables when the deck is empty.
- Responsive design for card layouts using **CSS Flexbox**.

## 🛠️ Tech Stack
- **Languages:** HTML5, CSS3, JavaScript (ES6+)
- **APIs:** [Deck of Cards API](https://deckofcardsapi.com/)
- **Concepts:** Promises, Async/Await, Method Chaining, Error Handling.

## 📈 Evolution of the Project (Commits)
This project was built over multiple iterations focusing on:
1. **Initial Setup:** UI layout and basic API fetch.
2. **Async Refactor:** Moving from `.then()` chains to clean `async/await` syntax.
3. **Logic Implementation:** Calculating winners and tracking scores.
4. **Game Over States:** Handling the end-of-game logic and final winner announcements.
5. **Polishing:** Enhancing UI feedback and code readability.

## 📝 How to Run
1. Clone the repository:
   ```bash
   git clone [Your Repo Link]
