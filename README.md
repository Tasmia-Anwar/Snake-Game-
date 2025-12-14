#  Snake Game – C# Windows Forms

A classic **Snake Game** developed using **C# Windows Forms**.
The game includes a grid-based movement system, scoring mechanism, pause/resume functionality, and a settings menu to customize snake and food colors.

---

##  Features

* **Grid-based Game Area**
*   Snake starts with 3 segments
*   Randomly generated food
* **Score & High Score system**
*  **Pause / Resume** functionality
*  **Settings Menu**

  * Change Snake Color
  * Change Food Color
*  **Game Over detection**

  * Wall collision
  * Self collision
*  Restart & Exit options
*  Keyboard controls (Arrow Keys)

---

## Controls

** Keys Action              
 Move Up             
 Move Down           
 Move Left
 Move Right          
 Pause Button , Pause / Resume Game 


## Technologies Used

* **Language:** C#
* **Framework:** .NET (Windows Forms)
* **IDE:** Visual Studio
* **Graphics:** GDI+ (Panel Paint event)

---

##  Game Design Overview

* The game uses a **Timer-based game loop** to move the snake.
* The snake body is stored using a `List<Point>`.
* Collision detection is handled separately for:

  * Walls
  * Snake body
* The grid is drawn inside the `Paint` event of the game panel.
* A **ContextMenuStrip** is used as a settings menu to change colors.
* Double buffering is enabled to reduce flickering.

---

##  Project Structure

```
Snake_Game/
│
├── Form1.cs                # Main game logic
├── Form1.Designer.cs       # UI design
├── Program.cs              # Application entry point
├── Resources/              # Images & icons
├── Snake_Game.exe          # Executable file
└── README.md               # Project documentation
```

---



