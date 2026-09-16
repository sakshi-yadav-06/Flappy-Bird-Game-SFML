# 🐦 Flappy Bird --- C++ & SFML

A 2D Flappy Bird-style arcade game developed in **C++** using the **SFML
(Simple and Fast Multimedia Library)**.

The project demonstrates game-loop programming, keyboard input, sprite
rendering, collision detection, scoring, and real-time 2D graphics.

## 🎮 Features

-   🐦 Player-controlled bird movement
-   🚧 Randomized pipe obstacles
-   💥 Collision detection
-   ⭐ Score tracking
-   🖥️ Real-time 2D graphics
-   🔊 Sound and audio support
-   🎯 Keyboard-based gameplay
-   ⚡ Game loop with real-time updates
-   🧩 Modular C++ source structure

## 🛠️ Technologies Used

  Technology                      Purpose
  ------------------------------- -------------------------------------
  **C++**                         Core game logic
  **SFML 2.5.1**                  Graphics, window, audio and input
  **Visual Studio Build Tools**   C++ compilation
  **Git & GitHub**                Version control and project hosting

## 📁 Project Structure

``` text
Flappy-Bird-Game-SFML/
│
├── assets/                     # Game images, fonts and audio
├── Bird.cpp                    # Bird implementation
├── Bird.h                      # Bird class/interface
├── Game.cpp                    # Main game management
├── Game.h                      # Game class/interface
├── Globals.h                   # Shared game constants
├── Pipe.cpp                    # Pipe implementation
├── Pipe.h                      # Pipe class/interface
├── main.cpp                    # Program entry point
├── Flappy Bird Tuts.vcxproj    # Visual Studio project
├── Flappy Bird Tuts.vcxproj.filters
├── .gitignore
└── README.md
```

## 🎯 How to Play

1.  Start the game.
2.  Use the **Spacebar** to make the bird flap upward.
3.  Guide the bird through the gaps between the pipes.
4.  Avoid hitting the pipes or ground.
5.  Continue passing pipes to increase your score.

> The exact controls can depend on the current game implementation.

## 💻 Requirements

-   Windows 10/11
-   C++ compiler compatible with the project
-   Visual Studio Build Tools / Visual Studio
-   SFML 2.5.1
-   Git (optional, for development)

## ⚙️ SFML Setup

This project uses **SFML 2.5.1**.

The project configuration expects SFML to be available through the
configured include and library directories.

Typical SFML layout:

``` text
SFML-2.5.1/
├── include/
│   └── SFML/
├── lib/
└── bin/
```

For Visual Studio builds, the required SFML DLL files should be
available beside the generated executable at runtime.

## ▶️ Build

Open PowerShell in the project directory and build with MSBuild:

``` powershell
& "C:\Program Files (x86)\Microsoft Visual Studio\18\BuildTools\MSBuild\Current\Bin\MSBuild.exe" ".\Flappy Bird Tuts.vcxproj" /p:Configuration=Debug /p:Platform=x64 /m
```

After a successful build, the executable is generated under:

``` text
x64/Debug/
```

The `x64/` build output is intentionally excluded from Git using
`.gitignore`.

## 🚀 Run

After building, run the generated executable from the `x64/Debug`
directory.

Make sure the required SFML runtime DLLs and game assets are available
where the executable can access them.

## 🧠 Concepts Demonstrated

This project is useful for practicing:

-   Object-Oriented Programming in C++
-   Classes and objects
-   Game loops
-   Event handling
-   Keyboard input
-   2D sprite rendering
-   Collision detection
-   Coordinate systems
-   Random obstacle generation
-   Score management
-   Audio integration
-   Project organization

## 📌 Future Improvements

Possible extensions include:

-   🏆 High-score persistence
-   ⏸️ Pause and resume
-   🔄 Restart button
-   🎚️ Difficulty levels
-   🎨 Custom themes and skins
-   📱 Improved UI
-   🥇 Leaderboard system
-   🎵 Background music controls
-   🪶 Animation improvements

## 👨‍💻 Author

**Sakshi Yadav**

GitHub: `https://github.com/sakshi-yadav-06`

## 📜 Credits

This repository is based on an existing Flappy Bird C++/SFML project.
The repository has been configured and adapted for the author's
development environment, including Visual Studio 2026/MSBuild and SFML
2.5.1 setup.

Original project contributors are retained in the repository's
history/credit where applicable.

## 📄 License

If this project is based on an existing repository, please check the
original project's license before redistributing or relicensing the
code.

------------------------------------------------------------------------

⭐ If you are using this project for learning, feel free to explore the
source code and experiment with new gameplay features.
