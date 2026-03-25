# ♟️ ChessSync –  Real-Time Multiplayer Chess

> Play chess in real-time with seamless synchronization using WebSockets ⚡

🚀 **ChessSync** is a real-time multiplayer chess application where two players can play live while others can join as spectators. Built with **Node.js, Express, Socket.IO, and chess.js**, it ensures smooth gameplay, move validation, and instant board updates.

---

## 🎯 Features

* ♟️ **Real-Time Multiplayer Gameplay**
* 🔄 **Live Move Synchronization using WebSockets**
* 👥 **Automatic Role Assignment**

  * First player → White
  * Second player → Black
  * Others → Spectators
* ✅ **Move Validation using chess.js**
* 📡 **Instant Board State Updates (FEN)**
* 👀 **Spectator Mode**
* ⚡ **Lightweight & Fast Backend**

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Realtime Communication:** Socket.IO
* **Game Logic:** chess.js
* **Templating:** EJS
* **Other Tools:** Nodemon

---

## 📂 Project Structure

```
ChessSync/
│── public/           # Static assets
│── views/            # EJS templates
│── index.js          # Main server file
│── package.json
```

---

## ⚙️ How It Works

1. User connects to server via Socket.IO
2. Server assigns:

   * `w` → White player
   * `b` → Black player
   * Others → Spectators
3. Moves are:

   * Validated using chess.js
   * Broadcasted to all clients
4. Board state is synced using **FEN notation**

---

## 🧪 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/mishra-pankaj/ChessSync.git

# Navigate into project
cd ChessSync

# Install dependencies
npm install

# Run the server
node index.js
```

Server will start at:
👉 http://localhost:3000

---

## 🎥 Demo

📹 Demo video included in the project


https://github.com/user-attachments/assets/964be800-a3c9-4693-8ebe-72aa0e5bb22a



---

## 🚧 Future Improvements

* ♟️ Matchmaking system
* ⏱️ Timer / Clock support
* 🧠 AI opponent mode
* 💬 In-game chat
* 📱 Responsive UI improvements
* 🏆 Game history & leaderboard

---

## 💼 Why This Project Matters

This project demonstrates:

* Real-time communication using **WebSockets**
* Backend system design with **Node.js & Express**
* Game state management
* Event-driven architecture
* Clean handling of multiplayer roles

Perfect for showcasing **backend + real-time app skills** in interviews 🚀

---

## 🔗 Repository

Check out the full code here:
👉 [ChessSync GitHub Repository](https://github.com/mishra-pankaj/ChessSync?utm_source=chatgpt.com)

---

## 👨‍💻 Author

**Pankaj Mishra**

---

⭐ If you like this project, consider giving it a star!




