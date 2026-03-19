# 🚢 Battleship Game using PyQt and Raspberry Pi 5

A digital recreation of the classic turn-based strategy Battleship game. This project reimagines the game using modern technologies, combining Python programming, PyQt6 for the sleek user interface, and the Raspberry Pi 5 platform for execution.

***

## 🌟 Abstract
This project outlines the design and development of the Battleship game, focusing on an interactive graphical user interface (GUI) that runs on the Raspberry Pi 5. By blending software engineering with an embedded systems environment, we have built an engaging platform that effectively demonstrates game logic, UI design, and future hardware interactions.

## 🎮 Game Design and Flow
The game is played on a 5x5 grid, where the user and the computer each have a fleet of 3 ships. 
The game consists of two main phases:
1. **Selection:** Users select 3 distinct positions on their board to place their ships.
2. **Attack Phase:** Players alternate firing at the opponent’s grid. A 20-second timer forces quick tactical decisions.
   - **Hit:** Marked in Red ('X')
   - **Miss:** Marked in Gray ('O')

The computer utilizes randomized logic to fire back, and the game concludes when one player successfully sinks all 3 of the opponent's ships.

## 🛠️ Tech Stack & Hardware Implementation
- **Python 3.x:** Core game logic and state management.
- **PyQt6:** Rich, interactive event-driven User Interface.
- **Raspberry Pi 5:** The core embedded platform handling software execution and providing stability for the game logic.

## 🔮 Future Scope
While the current build serves as a powerful standalone software application, it serves as an educational base for several exciting hardware extensions:
- **Hardware Integration:** Utilizing the GPIO pins to add LEDs, buzzers, and physical buttons for haptic feedback.
- **Multiplayer Mode:** Allowing two Raspberry Pi units to battle locally over LAN or Wi-Fi.
- **Advanced AI Ops:** Upgrading the opponent logic with Minimax or probabilistic algorithms.
- **Accessibility:** Implementing Touchscreen Kiosk support and Voice-Controlled commands!
