# Chess Game - Multiplayer Online

Welcome to the **Chess Game** repository! This is a multiplayer online chess game built using **Express.js**, **Node.js**, **Socket.IO**, and the **chess.js** library. The game allows two players to connect and play chess in real-time over the internet.

## Features

- **Real-time multiplayer gameplay**: Two players can connect and play chess in real-time.
- **Chess rules enforcement**: The game uses the `chess.js` library to enforce standard chess rules, including moves, captures, check, checkmate, and stalemate.
- **Interactive UI**: A simple and intuitive user interface for playing chess.
- **Socket.IO for real-time communication**: Enables seamless communication between the server and clients.
- **Express.js backend**: Handles server-side logic and routing.
- **Responsive design**: The game is designed to work on both desktop and mobile devices.

---

## Technologies Used

- **Node.js**: Backend runtime environment.
- **Express.js**: Web framework for handling HTTP requests and routing.
- **Socket.IO**: Enables real-time, bidirectional communication between the server and clients.
- **chess.js**: A JavaScript chess library for move generation, validation, and game state management.
- **HTML/CSS/JavaScript**: Frontend for the game interface.
- **Bootstrap (optional)**: For styling and responsive design.

---

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/chess-game.git
   cd chess-game
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the server**:
   ```bash
   npm start
   ```

4. **Access the game**:
   - Open your browser and navigate to `http://localhost:3000`.
   - Share the link with a friend to start a game!

---

## Project Structure

```
chess-game/
├── public/               # Static files (HTML, CSS, JS)
│   ├── index.html        # Main game interface
│   ├── styles.css        # CSS styles
│   └── script.js        # Frontend logic
├── src/                  # Server-side code
│   ├── server.js         # Express server and Socket.IO setup
│   └── game.js           # Chess game logic (using chess.js)
├── package.json          # Project dependencies and scripts
├── README.md             # This file
└── .gitignore            # Files and directories to ignore
```

---

## How It Works

1. **Server Setup**:
   - The Express server serves the static files (HTML, CSS, JS) to the client.
   - Socket.IO is used to handle real-time communication between players.

2. **Game Initialization**:
   - When two players connect, a new chess game is initialized using the `chess.js` library.
   - Players take turns making moves, and the game state is updated in real-time.

3. **Move Validation**:
   - Each move is validated using the `chess.js` library to ensure it follows standard chess rules.

4. **Game Over**:
   - The game ends when a player is checkmated, stalemated, or resigns.

---

## Snapshots
  - **Initial Board Setup** :
  
![chess_clone_2](https://github.com/user-attachments/assets/5c0a9822-cd82-4bfa-80b8-655e81c08127)



  - **When both players join** :
    
![chess_clone ](https://github.com/user-attachments/assets/349ee6e9-16d0-4c7a-841a-d665e3fa6352)


## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your branch.
4. Submit a pull request with a detailed description of your changes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [chess.js](https://github.com/jhlywa/chess.js) for providing the chess logic.
- [Socket.IO](https://socket.io/) for enabling real-time communication.
- [Express.js](https://expressjs.com/) for the backend framework.

---

## Contact

If you have any questions or suggestions, feel free to reach out:

- Vishwas Charan : (mailto:vishwascharan11@gmail.com)
- LinkedIn: (www.linkedin.com/in/vishwas-charan)

---

Enjoy playing chess! ♟️
