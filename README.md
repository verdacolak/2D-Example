# 2D Flappy Bird Clone

This is a 2D Flappy Bird clone developed using Unity 6 and C#. The project focuses on implementing fundamental game development concepts, object management, and basic UI workflows.

## 🚀 Features & Mechanics
* **Bird Physics:** Jump and gravity mechanics implemented using Rigidbody2D and AddForce.
* **Infinite Spawning System:** An obstacle generation system that continuously spawns pipes at random heights (`Random.Range`) and fixed time intervals.
* **Score Management:** A trigger-based scoring system (`OnTriggerEnter2D`) that updates the player's score on the UI (Text) in real-time.
* **Scene & Game Management:** A fully functional 'Game Over' state that displays a retry menu and reloads the active scene using `SceneManager`.

## 🛠️ Tech Stack
* **Game Engine:** Unity 6
* **Language:** C#
* **IDE:** Visual Studio

## 💻 How to Play
1. Launch the game.
2. Press the `Space` bar to make the bird flap and navigate through the gaps between the pipes.
3. Hitting an obstacle triggers the game over state; click the `Play Again` button to restart the game.
