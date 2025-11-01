SNAKE GAME v1.0

Developed for Quincy 2005 (C Language)

📘 ABOUT

This is a simple, classic Snake Game built entirely in C, designed to run on Quincy 2005 or any standard Windows C compiler.
You control a growing snake that eats fruits (*) to score points.
The game ends if you hit a wall or your own tail.

Lightweight, nostalgic, and fully console-based — this project is a perfect mix of fun and fundamental C programming logic.

⚙️ FEATURES

Console-based gameplay

Randomly spawning fruits

Dynamic tail growth system

Real-time keyboard input

Live score display

Game Over and Replay option

On-screen controls & guidelines

🎮 CONTROLS
Key	Action
W	Move Up
A	Move Left
S	Move Down
D	Move Right
X	Exit Game
🧩 HOW TO PLAY

Run the game — guidelines will appear before each session.

Press any key to start.

Move the snake using W, A, S, D keys.

Eat the ‘*’ to increase your score by 10 points.

Avoid colliding with walls or your own tail.

When the game ends, your final score will be displayed.

Press Y to play again or N to quit.

💻 HOW TO BUILD IN QUINCY 2005

Open Quincy 2005.

Click File → New → C Program.

Copy and paste the entire Snake Game code.

Click Build → Execute or press F9.

Play directly in the console window.

(Ensure conio.h, stdlib.h, and windows.h headers are available — they come preinstalled with Quincy.)

🧠 CONCEPTS USED

Loops & conditional logic

Arrays for snake tail tracking

Random number generation for fruit placement

Keyboard handling via _kbhit() and _getch()

Console rendering using system("cls")

🏁 GAMEPLAY TIPS

Try not to corner yourself — your tail grows fast!

Each fruit adds +10 points.

The game’s speed depends on CPU delay loops (you can tweak them).

Challenge friends to beat your highest score!
