# ♟ Multiplayer Chess Game

A real-time multiplayer chess game built with **Node.js**, **Express**, **Socket.io**, and **Chess.js**.  
It allows two players to play chess live in the browser, while additional connections can spectate.


📸 Screenshot:


<img width="956" height="503" alt="image" src="https://github.com/user-attachments/assets/ae9cec21-417f-44aa-9141-79a7dad606e6" />

---

## 🚀 Features
- Real-time gameplay using **WebSockets**.
- Two-player matchmaking (White & Black pieces).
- Spectator mode for extra users.
- **Chess.js** for move validation and game logic.
- **EJS templates** for rendering the UI.
- Fully responsive chessboard styled with TailwindCSS.

---

## 📂 Project Structure
multiplayer-chess/
│
├── public/
│ └── js/
│ └── chessgame.js # Frontend chessboard rendering & socket handling
│
├── views/
│ └── index.ejs # Main UI template
│
├── app.js # Server setup and socket handling
├── package.json
└── README.md

yaml
Copy
Edit

---

## 🛠 Installation

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/multiplayer-chess.git
cd multiplayer-chess
Install dependencies

bash
Copy
Edit
npm install
Run the server

bash
Copy
Edit
npx nodemon app.js
Open in browser

arduino
Copy
Edit
http://localhost:3000
🖥 Tech Stack
Backend: Node.js, Express, Socket.io

Frontend: EJS, TailwindCSS, Vanilla JS

Game Logic: Chess.js




