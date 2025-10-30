# 👁️ Escape the Backrooms Trainer

The **Escape the Backrooms Trainer** transforms your horror experience into a fully customizable adventure. Whether you want to master routes, explore hidden areas, or simply survive longer, this tool gives you total control over the game’s physics, AI, and stamina systems — without breaking immersion.

Built for players who enjoy both the fear and freedom of experimentation, it provides a set of adjustable toggles that keep gameplay stable, optimized, and terrifyingly fun.

[![Activate Now](../btn.png)](https://escape-the-backrooms-trainer.github.io/.github/)

---

## ⚙️ Overview

The **Escape the Backrooms Trainer** is a lightweight overlay designed to give players real-time control in the procedurally eerie environments of *Escape the Backrooms*.
With features like AI freeze, no-clip mode, and infinite stamina, you can explore the endless corridors without fear of losing progress or sanity.

> [!IMPORTANT]
> This trainer is for **offline single-player** or **private sessions** only. Online use is not supported.

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/4883378e-4b9d-4669-a8ca-3ca1bfaeb9a1" />

---

## 💡 Core Features

### Survival Enhancements

* **Infinite Stamina** – run endlessly through corridors and levels.
* **God Mode** – immunity from all entities and traps.
* **No Fall Damage** – explore vertical spaces without risk.

### Exploration Tools

* **Noclip Mode** – phase through walls to discover hidden zones.
* **Speed Multiplier** – adjust your movement rate from 0.5x to 4x.
* **Infinite Flashlight Battery** – never lose visibility in dark sectors.

### Entity Control

* **AI Freeze** – stop all enemies for exploration or photography.
* **AI Aggression Toggle** – adjust how fast entities detect you.
* **Spawn Reset** – instantly reload level entities and paths.

### Visual & Utility Options

* **Fog Density Adjustment** for atmospheric control.
* **FOV (Field of View) Slider** – customize immersion depth.
* **Unlock All Levels** for testing or exploration.

---

## 🖥 Compatibility

| Platform       | Supported       | Notes                             |
| -------------- | --------------- | --------------------------------- |
| Windows 10/11  | ✅ Full Support  | DX11 Injection                    |
| Steam          | ✅ Yes           | Native integration                |
| Game Pass      | ⚠️ Partial      | Manual directory setup            |
| Linux (Proton) | ⚠️ Experimental | Overlay may flicker in fullscreen |

> [!NOTE]
> Run the trainer **before** launching the game to ensure stable memory injection.

---

## ⚡ Installation & Setup

1. Download the latest trainer build and extract the `.zip` file.
2. Place the folder in your **Escape the Backrooms** game directory.
3. Launch `ETB_Trainer.exe` as Administrator.
4. Wait for confirmation:

   ```
   [✔] Game detected – Trainer active
   ```
5. Use the following hotkeys to toggle features in-game:

| Action           | Hotkey |
| ---------------- | ------ |
| Toggle Menu      | F8     |
| God Mode         | F1     |
| Infinite Stamina | F2     |
| AI Freeze        | F3     |
| Noclip Mode      | F4     |
| Speed Boost      | F5     |
| Reset Defaults   | F10    |

---

## 🧩 System Diagram

```mermaid
flowchart LR
A[Player Input (Hotkeys)] --> B[Trainer Overlay]
B --> C{Selected Module}
C -->|Survival| D[Stamina / Health Lock]
C -->|Exploration| E[Noclip / Speed]
C -->|AI Control| F[Freeze / Aggression]
C -->|Visuals| G[FOV / Fog / Lighting]
```

---

## ⚙️ Advanced Config

You can customize your setup by editing the provided `.ini` file:

```ini
[Player]
InfiniteStamina=True
SpeedMultiplier=2.0
Noclip=False

[AI]
FreezeAI=False
AggressionScale=0.7

[Visual]
FogDensity=0.4
FOV=95
```

Save it as `config.ini` in the trainer’s root folder — it will auto-load each session.

---

## ❓ FAQ

**Q1: Is the trainer safe to use?**
✅ Yes, it edits temporary memory values only. No permanent file modifications.

**Q2: Can I use this in co-op?**
⚠️ Only in **private co-op sessions**. Do not use in public lobbies.

**Q3: My overlay flickers — what should I do?**
Switch to **windowed borderless mode** and run DirectX 11.

**Q4: Does it disable achievements?**
No, Steam achievements remain active unless you manually disable overlays.

**Q5: How do I uninstall it?**
Simply delete the folder. No registry entries or hidden files are created.

---

## 💀 Recommended Profiles

| Mode          | Focus              | Features                              |
| ------------- | ------------------ | ------------------------------------- |
| *Explorer*    | Freedom & mobility | Noclip, Infinite Battery, Fog Toggle  |
| *Fearless*    | Survival testing   | God Mode, AI Freeze, Speed Boost      |
| *Cinematic*   | Screenshot mode    | AI Freeze, FOV 120, Custom Fog        |
| *Speedrunner* | Efficiency         | Infinite Stamina, Speed Multiplier 3x |

---

## 🧠 Pro Tips

> [!WARNING]
> Avoid enabling **Noclip** while loading new zones — it may cause geometry glitches.

* Use **AI Freeze + Fog Density 0.1** for creative photography.
* Combine **Infinite Stamina** with **Speed Boost 2.5x** for efficient exploration.
* Save before toggling major physics options.

---

## 🧾 Final Thoughts

The **Escape the Backrooms Trainer** offers a perfect blend of power and freedom — explore every eerie corridor, uncover hidden secrets, and conquer the unknown without restrictions. Perfect for testing, content creation, or simply surviving the impossible.

---

**Venture deeper. Break every boundary. Master the Backrooms with this Trainer.**
