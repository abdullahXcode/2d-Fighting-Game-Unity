# 2D Game Fight with Enemy

A 2D action/shooter game built in Unity where the player fights against various enemies including UFOs and HoneyBees.

## 🎮 Features
- **Player Movement**: Smooth 2D movement controls using Unity's new Input System.
- **Combat System**: Shoot bullets to destroy enemies.
- **Multiple Enemies**: Face off against different enemy types:
  - **UFO Enemy**: Flying adversaries that challenge your aim.
  - **HoneyBee**: Agile enemies to dodge and destroy.
  - **Enemy2**: Additional enemy variant.
- **Dynamic Background**: Scrolling background for an immersive experience.
- **Game Loop**: Clear Win and Game Over conditions with dedicated scenes.

## 🛠️ Built With
- **Unity Version**: 6000.2.6f2
- **Language**: C#

## 🚀 How to Play
1.  Clone this repository or download the source code.
2.  Open the project in Unity (Version 6000.2.6f2 or later recommended).
3.  Open the `Scenes` folder and load the main gameplay scene (likely `Level1` or similar, or check `File > Build Settings` for the first scene).
4.  Press **Play** in the Unity Editor.

### Controls
*   **Move**: W/A/S/D or Arrow Keys
*   **Shoot**: Spacebar / Left Mouse Button (Depending on configuration)
*   *(Customize these details if you have specific input mappings)*

## 📂 Project Structure
*   `Assets/Scripts`: Contains C# scripts for Player, Enemies, and Game Logic.
*   `Assets/Scenes`: Game scenes (Main, Win, Game Over).
*   `Assets/Resources`: Game assets and prefabs.
*   `Builds`: dedicated folder for build outputs.

## 📦 Build Instructions
1.  Go to **File > Build Settings**.
2.  Ensure all scenes (`GameOverScene`, `WinScene`, etc.) are added to the "Scenes In Build" list.
3.  Click **Build**.
4.  Select the `Builds` folder in the project directory as the output target.

<img src="images/2d-unity-game.png" width="800" alt="2D Unity Game">

## 📝 License
This project is for educational/personal use.
