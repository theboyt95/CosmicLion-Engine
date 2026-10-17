# CosmicLion Engine

<img width="1100" height="1100" alt="Image" src="https://github.com/user-attachments/assets/1b12d8ca-c6ef-400a-bdd7-5d5e9e1355d7" />

Welcome to CosmicLion Engine!

A Friday Night Funkin' engine built entirely in Clickteam Fusion 2.5+!

CosmicLion Engine is a fan-made FNF engine designed to bring V-Slice-style gameplay and chart compatibility to Clickteam Fusion.

The main goal of this project is to provide a customizable foundation for developers who want to create their own FNF mods, fangames, or experiments using Clickteam Fusion.

Features
V-Slice Chart Support: Reads note data directly from V-Slice JSON charts.
Metadata Support: Uses V-Slice metadata files to handle song information, BPM, and BPM changes.
Input and Judgement System: Includes note hit detection, scoring, combos, and misses.
DeltaTimer: Allows the game to run at any framerate without breaking camera movements, tweens, and other time-dependent effects.
Rating Popups: Animated judgement and combo popups featuring movement, gravity, and fading, just like the original FNF!
Camera System: Supports camera movement, zoom effects, and camera bop.
Song Event System: Includes support for events such as FocusCamera, Add Camera Zoom, and SetCameraBop.
Beat and Step Tracking: Keeps gameplay events synchronized with the song, including BPM changes chart and Metadata Requirements.


[!IMPORTANT]


CosmicLion Engine requires BOTH a V-Slice chart JSON file and its corresponding metadata JSON file to load a song correctly.
Chart JSON

Contains the song's gameplay data, including:

Notes
Sustain lengths
Song events
Metadata JSON

Contains the song's timing information, including:

BPM (Beats Per Minute)
BPM changes
Other timing-related data

Both files must follow the Friday Night Funkin' V-Slice JSON format.

Charts from other engines, such as Psych Engine or Codename Engine, are not guaranteed to work without conversion.

Requirements and Dependencies

If you want to open, edit, or compile the engine's source project, you will need the following software and extensions.

Software
Clickteam Fusion 2.5+
The Clickteam Fusion 2.5+ DLC
A compatible, up-to-date Clickteam Fusion build
Required Objects and Extensions
Extension	Purpose
LB JSON Object	Reads and processes JSON chart, metadata, and event data.
Array	Stores and manages chart information.
String Parser	Handles string processing.
Easing Object	Provides smooth camera transitions and animations.
Control X	Supports custom keybinds.



⚠️ Clickteam Fusion 2.5+ Is Required!

This engine uses Child Events, a feature introduced with the Clickteam Fusion 2.5+ DLC.

Because of this, the source project will not open in the standard version of Clickteam Fusion 2.5 without the 2.5+ DLC.

Please make sure all required extensions are properly installed before opening the .mfa source file.

These requirements apply to developers editing or compiling the source project, not necessarily to players running a compiled game.



Usage and Credits:

CosmicLion Engine is free to use and modify!

You are welcome to:

Use the engine for your own FNF mods or fangames.
Modify the source code and add your own features.
Build your own projects using the engine.
Publish games made with CosmicLion Engine.
Credit Requirements

All I ask is that you give proper credit!

If you use this engine in your project, please credit me somewhere visible, such as in your game's credits or description.

Please do not claim that you created the original engine yourself.

You are also responsible for respecting the licenses and credits of any third-party assets or extensions used in your projects.

You do not need to ask for permission to use the engine, as long as proper credit is given.

Final Notes

CosmicLion Engine is a passion project made to explore what can be achieved with Clickteam Fusion.

The engine may receive improvements, bug fixes, and additional features over time.

Thank you for checking out CosmicLion Engine, and have fun creating your own FNF Clickteam projects!

Made with Clickteam Fusion 2.5+

CosmicLion Engine is an unofficial fan project and is not affiliated with The Funkin' Crew developers.
