AssaultCube External Aimbot (C++)
A lightweight, external aimbot for AssaultCube v1.2.0.2. This project was developed for educational purposes to demonstrate memory manipulation, 3D mathematical calculations, and process interaction using the Windows API.

<img width="1783" height="1017" alt="image" src="https://github.com/user-attachments/assets/103e4913-dd28-409a-989d-c9d88d84a053" />

🚀 Features
External Execution: Runs as a separate process without injecting code.

FOV-Based Targeting: Instead of just aiming at the closest enemy, it targets the enemy closest to your crosshair.

Smoothing System: Adjustable movement speed to make aiming look more natural.

Real-time Console Feedback: Shows current target ID and FOV distance.

Keybinds:

Right Mouse Button (Hold): Activate Aimbot.

END Key: Close the script safely.

🛠️ Requirements & Technical Details
Architecture: x86 (AssaultCube is a 32-bit game).

Compiler: Visual Studio with C++17 or higher.

Character Set: Must be configured to "Use Multi-Byte Character Set" in Project Properties.

📝 How to use
Open AssaultCube.

Join a match and ensure you are alive before starting the script.

Run the compiled .exe as Administrator at x64 > Release.

Hold the Right Mouse Button to lock onto targets within the FOV range.

🚧 Known Issues
Startup Constraint: The script currently only initializes correctly if executed while the player is already alive in the match. If started at the main menu, memory addresses may not resolve properly.

🎯 Future Updates (To-do)
Team Check: Implement a filter to prevent the aimbot from targeting allies.

Auto-Initialization: Fix the bug to allow the script to be opened at any time (even if dead or in the menu).

No Recoil: Add a feature to eliminate weapon kickback.

⚠️ Disclaimer
This project is for educational purposes only. Using cheats in multiplayer matches can lead to bans. I do not encourage or condone cheating in online games.
