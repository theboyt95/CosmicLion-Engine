# CosmicLion Engine

<p align="center">
  <img width="400" height="400" alt="CosmicLion Engine Logo" src="https://github.com/user-attachments/assets/1b12d8ca-c6ef-400a-bdd7-5d5e9e1355d7" />
</p>

<p align="center">
  <strong>A Friday Night Funkin' engine built entirely in Clickteam Fusion 2.5+</strong>
</p>

---

Welcome!  

**CosmicLion Engine** is a fan-made FNF engine that brings V-Slice-style gameplay and chart compatibility to Clickteam Fusion.  

The goal is simple: give developers a solid, customizable foundation to create their own FNF mods, fangames, or experiments — all inside Clickteam Fusion.

---

## Features

- **V-Slice Chart Support** — Reads note data directly from V-Slice JSON charts  
- **Metadata Support** — Uses V-Slice metadata files for song info, BPM, and BPM changes  
- **Input & Judgement System** — Note hit detection, scoring, combos, and misses  
- **DeltaTimer** — Runs at any framerate without breaking camera movements, tweens, or other time-based effects  
- **Rating Popups** — Animated judgement and combo popups with movement, gravity, and fading (just like original FNF)  
- **Camera System** — Camera movement, zoom effects, and camera bop  
- **Song Event System** — Supports events like FocusCamera, Add Camera Zoom, and SetCameraBop  
- **Beat & Step Tracking** — Keeps everything synced with the song, including BPM changes  

---

## Important: Chart + Metadata Requirements

> [!IMPORTANT]  
> CosmicLion Engine needs **both** a V-Slice chart JSON **and** its corresponding metadata JSON to load a song correctly.

| File | What it contains |
|------|------------------|
| **Chart JSON** | Notes, sustain lengths, song events |
| **Metadata JSON** | BPM, BPM changes, and other timing data |

Both files must follow the official Friday Night Funkin' **V-Slice** JSON format.  

Charts from other engines (Psych, Codename, etc.) are **not** guaranteed to work without conversion.

---

## Requirements & Dependencies

If you want to open, edit, or compile the source project, you'll need:

### Software
- Clickteam Fusion **2.5+**
- The Clickteam Fusion **2.5+ DLC**
- A compatible, up-to-date Clickteam Fusion build

### Required Extensions

| Extension       | Purpose |
|-----------------|--------|
| **LB JSON Object** | Reads and processes JSON chart, metadata, and event data |
| **Array**         | Stores and manages chart information |
| **String Parser** | Handles string processing |
| **Layer Object** | Make the camera beat in rhytm and manipulate things like the HUD, movement, etc |
| **Easing Object** | Smooth camera transitions and animations |
| **Control X**     | Custom keybinds support |

> [!WARNING]  
> **Clickteam Fusion 2.5+ is required!**  
> This engine uses **Child Events**, a feature that only exists with the 2.5+ DLC.  
> The source project will **not** open in regular Clickteam Fusion 2.5.

Make sure all required extensions are installed before opening the `.mfa` file.  

These requirements only apply to people editing or compiling the source — players of a compiled game don’t need them.

---

## Usage & Credits

CosmicLion Engine is **free to use and modify**.

You’re welcome to:
- Use it for your own FNF mods or fangames  
- Modify the source and add your own features  
- Build and publish projects with it  

### Credit Requirements

All I ask is that you give proper credit.

If you use this engine, please credit me somewhere visible (credits screen, description, etc.).  

Please don’t claim you created the original engine.

You’re also responsible for respecting the licenses and credits of any third-party assets or extensions used in your projects.

You don’t need to ask for permission — just give proper credit and you’re good to go.

---

## Final Notes

CosmicLion Engine is a passion project made to explore what can be achieved with Clickteam Fusion.

The engine may receive improvements, bug fixes, and additional features over time.

Thank you for checking out CosmicLion Engine, and have fun creating your own FNF Clickteam projects!

---

<p align="center">
  Made with Clickteam Fusion 2.5+
</p>

<p align="center">
  <em>CosmicLion Engine is an unofficial fan project and is not affiliated with The Funkin' Crew.</em>
</p>
