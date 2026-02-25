# Duckling Dash

A Snake arcade remake built for Universal Windows Platform using C#. Control a duck collecting pellets — the trail grows and speed increases with each one collected, making the game progressively harder over time.

---

## Screenshots

*[Add screenshots here]*

---

## Gameplay

- Control a duck navigating a grid to collect pellets
- Each pellet collected grows the duck's trail
- Speed increases as the trail grows, raising the difficulty over time
- Game ends when the duck collides with its own trail or the boundary

---

## Tech Stack

| | |
|---|---|
| Language | C# |
| Platform | Universal Windows Platform (UWP) |
| UI | XAML |

---

## Project Structure

```
duckling-dash-uwp/
├── GameInterface/    # UWP UI layer — XAML pages and input handling
├── GameLibrary/      # Game logic — movement, collision, scoring
└── UWPGame.sln
```

---

## Running Locally

### Prerequisites
- Windows 10 or later
- Visual Studio 2019+ with UWP development workload installed

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Doaa-Awan/duckling-dash-uwp.git
```

2. Open `UWPGame.sln` in Visual Studio

3. Set `GameInterface` as the startup project

4. Press **F5** to build and run

---

## About

Built as a school project to learn UWP game loop architecture, C# event handling, and separation of UI and game logic across multiple projects.
