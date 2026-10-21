# 🐦 Flappy Bird Game in C++

A console-based implementation of the classic **Flappy Bird** game using C++. The project features username registration, interactive gameplay, obstacle avoidance, score tracking, and a menu-driven interface.

## 📑 Table of Contents

- [Introduction](#-introduction)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [How to Play](#-how-to-play)
- [Game Menu](#-game-menu)
- [Gameplay Mechanics](#-gameplay-mechanics)
- [Game Output](#-game-output)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

## 🎮 Introduction

This project recreates the core mechanics of Flappy Bird in a C++ console environment. Players control a bird, navigate through obstacles, and try to achieve the highest possible score.

A simple menu allows users to register their names, start the game, view instructions, and access registered users.

## ✨ Features

- **User Registration:** Enter a username before playing.
- **Interactive Gameplay:** Control the bird using the keyboard.
- **Obstacle Generation:** Navigate through pipes with gaps.
- **Score Tracking:** Earn points by passing obstacles.
- **Collision Detection:** End the game when the bird hits an obstacle.
- **Game Instructions:** View controls and gameplay guidance.
- **Registered Users:** Access previously registered usernames.
- **Console Interface:** Navigate through a simple text-based menu.

## 🛠️ Technologies Used

- **Programming Language:** C++
- **Interface:** Console-based UI
- **Compiler:** GCC (`g++`) or another compatible C++ compiler
- **Concepts:** Loops, conditional statements, functions, keyboard input, collision detection, and score management

## 🚀 Installation

### Prerequisites

Install a C++ compiler such as GCC and ensure `g++` is available in your terminal.

### 1. Clone the Repository

```bash
git clone https://github.com/usmana0820/FlappyBirdGame.git
```

### 2. Navigate to the Project Directory

```bash
cd FlappyBirdGame
```

### 3. Compile the Program

If the main source file is named `main.cpp`, compile it using:

```bash
g++ main.cpp -o flappybird
```

If the project contains multiple `.cpp` files, include the required source files in the compilation command.

### 4. Run the Game

On Linux or macOS:

```bash
./flappybird
```

On Windows Command Prompt:

```bash
flappybird.exe
```

**Note:** The compilation command assumes the source file is named `main.cpp`. Adjust it if your repository uses a different filename.

## 🕹️ How to Play

1. Launch the executable.
2. Select an option from the main menu.
3. Register your username if required.
4. Start the game.
5. Press the **Spacebar** to make the bird fly upward.
6. Avoid the pipes and pass through their gaps.
7. Earn points by successfully passing obstacles.
8. After a game over, press a key to return to the menu.

Use the **Esc** key to exit during gameplay only if that behavior is supported by the implementation.

## 📋 Game Menu

The console menu provides the following options:

```text
--------------------------
|      Flappy Bird       |
--------------------------
1. Register your User Name
2. Start Game
3. Instructions
4. Registered Users
5. Exit

Select option:
```

### User Registration

When the registration option is selected, the program prompts the player to enter a username.

```text
--------------------------
|      Flappy Bird       |
--------------------------
Please Register your Name:
```

After registration, the player can return to the main menu.

## ⚙️ Gameplay Mechanics

### Bird Movement

The bird starts at a designated position in the console. Pressing the Spacebar moves it upward, while the game's movement logic controls its position over time.

### Obstacles

Pipes appear from the right side of the playing area and move toward the left. Each pair contains a gap through which the bird must pass.

### Scoring

The score starts at zero and increases when the bird successfully passes an obstacle pair.

### Collision Detection

If the bird collides with a pipe or another defined boundary, the game ends.

## 🖥️ Game Output

### Gameplay Screen

The console displays the playing area, obstacles, bird position, and current score. A simplified illustration is shown below:

```text
--------------------------
|                        |
|              ***       |
|                        |
|                        |
|      o                 |
|                        |
|              ***       |
|                        |
--------------------------
Score: 0
```

*Illustrative output only; the actual console layout may differ.*

### Game Over Screen

After a collision, the game displays a game-over message and the final score.

```text
--------------------------
|       Game Over        |
--------------------------
Score: 5

Press any key to go back to menu.
```

## 📈 Expected Outcomes

- Understand fundamental C++ programming concepts.
- Practice keyboard input and console-based interaction.
- Implement basic game loops and obstacle movement.
- Apply collision detection and score tracking.
- Develop a simple menu-driven application.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork this repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature-branch
   ```

3. Commit your changes:

   ```bash
   git commit -m "Improve gameplay"
   ```

4. Push your branch:

   ```bash
   git push origin feature-branch
   ```

5. Open a pull request.

## 📄 License

This project is intended to use the MIT License. See the [`LICENSE`](LICENSE) file for details if it is included in the repository.

## 👩‍💻 Contact

**Usmana Zulfiqar**

- GitHub: [@usmana0820](https://github.com/usmana0820)
- Email: [usmanazulfiqar20@gmail.com](mailto:usmanazulfiqar20@gmail.com)

Feel free to reach out with questions, feedback, or suggestions.
