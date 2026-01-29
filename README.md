## Tic-Tac-Toe AI (Minimax)  

### Overview  
This project implements a **Tic-Tac-Toe game** in Python, where the player competes against an AI that uses the **Minimax Algorithm** to make optimal moves. The AI ensures the best possible strategy for winning or forcing a tie.  

### Key Features  
**Human vs. AI (Minimax Algorithm)**  
**Optimal AI Move Calculation** 
**Interactive Console-Based Gameplay**  
**Handles Wins, Losses & Ties** 

### Project Structure  
```
Tic-Tac-Toe-AI/
│── README.md  # Documentation  
│── tic_tac_toe.py  # Game implementation  
```  

### Technologies Used  
Python  
Minimax Algorithm  

### How to Run the Game?  
#### 1️ Clone the Repository  
```bash
git clone https://github.com/Aishvariyaa/Tic-Tac-Toe-AI.git
cd Tic-Tac-Toe-AI
```  

#### 2️ Run the Game  
```bash
python tic_tac_toe.py
```  

### How to Play?  
1️ The game starts with an **empty 3x3 board**  
2️ The player (**O**) makes the first move by entering row & column indices (0-2)  
3️ The AI (**X**) responds using the **Minimax algorithm**  
4️ The game continues until there’s a **win or a tie**  

### Sample Game  
```
- - -
- - -
- - -

Enter row (0-2): 1
Enter column (0-2): 1

- - -
- O -
- - -

AI moves...

- - X
- O -
- - -

...

Congratulations! You won!
```

### Next Steps  
Improve AI performance using **Alpha-Beta Pruning**  
Add a **GUI version with Pygame**  
Implement a **two-player mode** 
