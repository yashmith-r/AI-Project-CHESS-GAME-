# AI-Project-CHESS-GAME:
Chess Game with AI
Welcome to our Chess Game featuring a graphical user interface (GUI) for a unique 2-agent setup. In this game, the human player controls both a king and a boat, while the AI manages its own king. Points, unique rules, and movement patterns create a fresh and exciting chess experience.

Features
Human vs AI Gameplay: Control a king and a boat against the AI's king.
Unique Mechanics: Different movement patterns and point values for the king and boat.
Dynamic Scoring: Earn or lose points based on your moves and captures.
Artificial Intelligence
We use the Minimax Algorithm to make the AI's moves strategic and challenging:

Minimax Algorithm: Evaluates possible moves to maximize the player's chances and minimize the AI's risks.
Evaluation Function: Predicts and counters the user's moves.
Valid Moves Calculation: Ensures each piece moves according to game rules.
Implementation
Our AI strategy includes three key functions:

cal_valid_moves: Calculates valid moves for each piece.
evaluation: Assesses the game state to guide the AI's decisions.
minmax: Recursively explores moves to determine the best strategy for the AI
