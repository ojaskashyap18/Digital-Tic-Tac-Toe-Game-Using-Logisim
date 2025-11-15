# 🎮 Digital Tic Tac Toe Game Using Logisim

A digital logic implementation of the classic Tic Tac Toe game using **Logisim**.  
Developed for the *Computation Structures* course at **VIT Vellore**.

---

## 📘 Project Overview

This project uses digital logic (AND, OR, NOT gates, multiplexers, and optional flip-flops) to simulate a complete Tic Tac Toe game on a 3×3 grid. Each cell is represented by switches/inputs and the circuit evaluates all winning combinations (rows, columns, diagonals) using Boolean expressions.

**The system detects:**
- Player 1 Win  
- Player 2 Win  
- Draw condition  
- Real-time status via LEDs and outputs

---

## 🧠 How the Circuit Works (short)

- Each of the nine grid cells maps to signal lines representing X or O state.  
- Winning conditions are implemented as Boolean formulas, e.g.:

- The circuit evaluates all 8 winning conditions (3 rows, 3 columns, 2 diagonals) for both players using combinational logic.  
- Outputs are LEDs (or indicators) for Player 1 Win, Player 2 Win, or Draw.  
- Optional flip-flops or latches can be used for turn/state control if implemented.

---

## 🧩 Features

- ✅ Full Tic Tac Toe logic implemented in Logisim  
- ✅ Real-time evaluation of win/draw states  
- ✅ Clean LED indicators for results  
- ✅ Structured project layout (circuit, docs, screenshots)

---

## 📁 Repository Structure

/Digital-Tic-Tac-Toe-Game-Using-Logisim
│
├── Circuit/
│ └── tic_tac_toe.circ
│
├── Documentation/
│ └── Project_Report.pdf
│
├── Presentation/
│ └── Project_Presentation.pptx
│
├── Screenshots/
│ ├── circuit_overview.png
│ └── winner_output.png
│
└── README.md

## 📸 Screenshots

### Tic Tac Toe Circuit (Final)
![Tic Tac Toe Circuit](Screenshots/tic%20tac%20toe%20circuit%20diagram%20final.jpg)

### Winning Combinations Logic
![Winning Combinations](Screenshots/circuit%20diagram%20for%20winning%20combinations.jpg)

### Counter Logic
![Counter Logic](Screenshots/circuit%20diagram%20for%20counter%20.jpg)


## 🎬 Demo Video

👉 [**Click here to watch the demo video**](Screenshots/Video%20demonstration%20of%20digital%20tic%20tac%20toe%20game.mp4)


## 🛠️ Tools & Requirements

- **Logisim** (recommended latest stable)  
- Windows/Screen recorder for demo (Win+Alt+R or OBS)  
- Basic Git/GitHub for repo management

---

## 👥 Team Members

- **Ojas Kumar Kashyap** ([@ojaskashyap18](https://github.com/ojaskashyap18))  
- **Sushil** ([@sushil-0x01](https://github.com/sushil-0x01))

---

## ✅ How to run

1. Install Logisim.  
2. Clone the repository:
3. Open `Circuit/tic_tac_toe.circ` in Logisim.  
4. Toggle switches to make moves and watch LED outputs for win/draw.
