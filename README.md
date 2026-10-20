# ✈️ Aviator Visual Clone

A high-fidelity visual clone of the "Aviator" crash game, focusing on performance, animation, and real-time state synchronization.

**⚠️ Note:** This repository focuses strictly on the **Visual Engine (PixiJS)** and **WebSocket Synchronization**.
For the comprehensive **Betting Logic Engine** (Auto-bet, Cash out, Balance handling), please view my logic demonstration here:
👉 **[Live Logic Demo (Socket Practice)](https://socketpractice.netlify.app/)**

---

## ✨ Features

- **High-Performance Rendering**: Smooth 60FPS airplane flight trajectory using **PixiJS**.
- **Real-Time Sockets**: Synchronized multiplier updates pushed from the server to the client.
- **State Management**: Handles complex game states visually:
  - **Loading**: Splash screen with partner assets.
  - **Flying**: Dynamic curve generation as the multiplier increases.
  - **Crashed**: "Flew Away" state synchronization.
- **Responsive Canvas**: Adapts the game container to different screen sizes.

---

## 🛠 Tech Stack

- **Frontend**: React
- **Graphics Engine**: PixiJS
- **Communication**: WebSockets (Socket.io)
- **Styling**: CSS Modules

---

## 🖼 App Screenshots

### 🚀 Gameplay (Flying State)
<img src="./docs/image/flyingScreen.png" width="350" alt="Flying State">

### 💥 Flew Away (Game Ended)
<img src="./docs/image/gameEnded.png" width="350" alt="Crashed State">

### 🏁 Loading / Splash Screen
<img src="./docs/image/startingScreen.png" width="350" alt="Loading Screen">

---

## 👤 Author

**Dato Sebiskveradze**
Frontend Developer

