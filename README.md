# **TIC-TAC-TOE-Game**

🎮 **Tic Tac Toe Game**  
A simple Tic Tac Toe game built with **HTML, CSS, and JavaScript**. This project allows two players to play the classic "X and O" game in the browser.  

---

## **📌 Features**
- ✅ Two-player mode (Player O and Player X)  
- ✅ Highlights winner with a congratulatory message  
- ✅ Handles draw conditions  
- ✅ Option to reset or start a new game  
- ✅ Responsive design – works on desktop and mobile screens  

---

## **🖼️ Preview**
The game board is a **3x3 grid** where players take turns clicking boxes to place their mark (O or X).  
- Player O starts first  
- A message appears declaring the **winner** or **draw** when the game ends  
- Buttons available:  
  - **Reset Game** → Clears the board and continues  
  - **New Game** → Starts a fresh match with reset state  

---

## **🚀 Getting Started**

### 1. Clone the Repository  
```bash
git clone https://github.com/your-username/tic-tac-toe.git
cd tic-tac-toe
2. Open in Browser
Simply open index.html in your browser:

bash
Copy code
open index.html
(or just double-click the file).

No server setup or dependencies required.

📂 Project Structure
bash
Copy code
tic-tac-toe/
│── index.html      # Main game structure
│── style.css       # Styling for layout and design
│── app.js          # Game logic and interactivity
│── README.md       # Documentation
🛠️ Technologies Used
HTML5 – Structure of the game

CSS3 – Styling and responsive layout

JavaScript (ES6) – Game logic (player turns, winner detection, reset functionality)

🎯 How It Works
The board has 9 clickable boxes (.box)

Players take turns placing "O" and "X"

The script checks winning combinations (winPatterns) after each move

If all boxes are filled and no winner → game ends in a draw

Winner or draw message is displayed in .msg-container

Players can reset or start a new game anytime

📸 Screenshots
<table> <tr> <td align="center"> <img src="https://github.com/user-attachments/assets/fc4fefc3-012d-40be-9903-1645b9c6bc1d" width="350" alt="Game Board Screenshot" /> <br/><sub>Game Board</sub> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/794422f6-6caa-45c8-b80a-00b5261d91e7" width="350" alt="Game In Progress Screenshot" /> <br/><sub>Game in Progress</sub> </td> </tr> <tr> <td align="center"> <img src="https://github.com/user-attachments/assets/dfa6d2cd-7b9b-4ecd-9020-1f2088bd021b" width="350" alt="Winner Message Screenshot" /> <br/><sub>Winner Announcement</sub> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/df723b8d-6376-46ee-9822-a776a7a2a252" width="350" alt="Reset and New Game Screenshot" /> <br/><sub>Reset/New Game Options</sub> </td> </tr> </table>
🔮 Future Improvements
🎨 Add animations for winning lines

🖥️ Add AI opponent (single-player mode)

🔊 Add sound effects for moves and win/draw events

📱 Enhance UI for better mobile experience

👨‍💻 Author
Developed by Priyanshu ✨
