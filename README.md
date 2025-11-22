# SkillCraft Project - Starter Repo

Short description
-----------------
This repository is a starter template for the SkillCraft technology internship projects.
Add your project files (code, reports, screenshots) here and push to GitHub.

Tags: #skillcraft #SkillCraft #internship

How to use
----------
1. Copy these files into your project folder (or keep this repo as your project root).
2. Initialize git and make an initial commit:

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <YOUR_GITHUB_REPO_URL>
   git push -u origin main
   ```

3. Replace this README with your project description, screenshots, and instructions.
# 🎮 Tic-Tac-Toe Game

A modern, interactive Tic-Tac-Toe web application built with HTML5, CSS3, and vanilla JavaScript. Play against a friend or challenge an intelligent AI opponent!

![Tic-Tac-Toe Game](https://img.shields.io/badge/Game-Tic--Tac--Toe-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

- **Two Game Modes**
  - 👥 **Player vs Player**: Local multiplayer for two players
  - 🤖 **Player vs Computer**: Challenge an intelligent AI opponent

- **Smart AI Opponent**
  - Attempts to win when possible
  - Blocks player winning moves
  - Makes strategic decisions (center, corners, edges)

- **Game Features**
  - ✅ Real-time win detection
  - 🎯 Winning cell highlighting with animations
  - 📊 Score tracking across multiple games
  - 🔄 Easy game reset and mode switching
  - ⚡ Smooth animations and transitions

- **Responsive Design**
  - 📱 Mobile-friendly interface
  - 💻 Works on all screen sizes
  - 🎨 Beautiful gradient UI with modern styling

## 🚀 Demo

[Live Demo Link](#) _(Add your deployed link here)_

## 📸 Screenshots

_(Add screenshots of your game here)_

## 🛠️ Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling, animations, and responsive design
- **JavaScript (ES6+)** - Game logic and interactivity

## 📋 Prerequisites

No dependencies required! Just a modern web browser.

## 💾 Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/tic-tac-toe-game.git
```

2. Navigate to the project directory
```bash
cd tic-tac-toe-game
```

3. Open `index.html` in your web browser
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or simply double-click the `index.html` file!

## 🎯 How to Play

1. **Choose Game Mode**
   - Select "Player vs Player" for local multiplayer
   - Select "Player vs Computer" to play against AI

2. **Make Your Move**
   - Player X always goes first
   - Click on any empty cell to place your mark
   - In computer mode, wait for AI's turn

3. **Win the Game**
   - Get three marks in a row (horizontal, vertical, or diagonal)
   - The game automatically detects winners and draws

4. **Play Again**
   - Click "New Game" to start a fresh round
   - Click "Change Mode" to switch between game modes
   - Scores persist across multiple games

## 🧠 Game Logic

### Win Detection Algorithm
The game checks for winners after each move by evaluating:
- 3 horizontal rows
- 3 vertical columns
- 2 diagonal lines

### AI Strategy
The computer opponent uses the following decision tree:
1. **Win**: Take winning move if available
2. **Block**: Block player's winning move
3. **Center**: Take center square if available
4. **Corner**: Take a corner square
5. **Edge**: Take any remaining square

## 📁 Project Structure

```
tic-tac-toe-game/
│
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # Project documentation
└── screenshots/        # Screenshots folder (optional)
```

## 🎨 Customization

You can easily customize the game by modifying the CSS variables in the `<style>` section:

- **Colors**: Change gradient colors for different themes
- **Animations**: Adjust animation duration and effects
- **Board Size**: Modify cell dimensions in the `.cell` class
- **Fonts**: Update font-family for different typography

## 🐛 Known Issues

- None at the moment! Report issues [here](https://github.com/yourusername/tic-tac-toe-game/issues)

## 🔮 Future Enhancements

- [ ] Add difficulty levels for AI (Easy, Medium, Hard)
- [ ] Implement minimax algorithm for unbeatable AI
- [ ] Add sound effects and background music
- [ ] Include online multiplayer with WebSocket
- [ ] Add animations for X and O placement
- [ ] Theme customization (light/dark mode)
- [ ] Save game history and statistics
- [ ] Add timer for each move
- [ ] Implement undo/redo functionality

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [Hemanth](https://github.com/Hemanthps007)
- LinkedIn: [Hemanth](https://www.linkedin.com/in/hemanth-ps-37b970309/)

## 🙏 Acknowledgments

- Inspired by the classic Tic-Tac-Toe game
- Icons and design inspiration from modern UI/UX trends
- Thanks to the open-source community

## 📞 Contact

Have questions or suggestions? Feel free to reach out!

- Email: pshemanth2@gmail.com

---

⭐ **If you found this project helpful, please give it a star!** ⭐

Made with ❤️ and JavaScript
