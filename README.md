# Roll-A-Ball AI Game 🎮🟡

A 3D Unity-based game where the player controls a rolling ball that collects pickups while avoiding an AI-controlled enemy. Features dynamic physics-based interactions, Unity NavMesh pathfinding, and win/loss game logic.

---

## 🕹️ Gameplay Overview

- 🎯 **Objective**: Collect all yellow cubes (goal objects) before the enemy reaches you
- ⚠️ **Lose condition**: Enemy reaches the player
- ✅ **Win condition**: Collect all pickups before being caught

---

## 🧠 Features

- 🔵 Player-controlled rolling sphere using Rigidbody physics
- 🟡 Pickup items (goal objects) with score tracking
- 🟥 Dynamic and static environmental blocks
  - Dynamic objects move when hit
  - Static objects remain fixed (no Rigidbody)
- 🧠 AI enemy uses Unity **NavMesh** to chase the player
- 🖥️ UI counter displays remaining pickups
- 🎉 Game ends on win or loss condition

---

## 🧱 Project Structure

```bash
.
├── Assets/
│   ├── Scripts/                  # Player controller, enemy AI, pickup logic
│   ├── Scenes/                  # Main game scene
│   └── Prefabs/                 # Player, enemy, pickups, environment pieces
├── Packages/
├── ProjectSettings/
├── UserSettings/
├── RollABall.sln                # Visual Studio solution file
├── README.md

```

## 🛠️ Tech Stack
Engine: Unity (URP 3D)

- Language: C#

- Physics: Unity Rigidbody & Collider components

- AI Navigation: Unity NavMesh

- UI: Canvas-based score + win/loss screens

## 🧪 How to Run
- Open the project in Unity Hub

- Load the included .sln or .unity scene file

- Enter Play Mode (▶️) in the Unity Editor

## 📦 Planned Improvements (Optional)
- Add difficulty levels (multiple enemies or faster speed)

- Add restart button or main menu screen

- Mobile controls or WebGL export for browser play
