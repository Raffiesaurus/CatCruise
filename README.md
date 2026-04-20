# Cat Cruise

![Cat Cruise](CatCruise.png)

An **endless runner mobile game** built with Unreal Engine 4 Blueprints and published on the Google Play Store. You play as a cat cruising through an obstacle course — dodge, survive, and climb the leaderboard.

---

## Features

- Endless runner gameplay with increasing difficulty
- **Google Play Games** integration — global leaderboards and achievements
- Fully custom art pipeline:
  - All UI elements designed in **Photoshop**
  - All 3D models built and animated in **Blender**
- Blueprint-only implementation — no C++
- Optimised for Android mobile

---

## Tech

- **Engine:** Unreal Engine 4.26
- **Platform:** Android
- **Scripting:** Blueprints
- **Online:** UE4 Online Subsystem (OnlineFramework) → Google Play Games Services
- **Art:** Photoshop (UI), Blender (3D models + animation)

---

## Opening the Project

1. Install **Unreal Engine 4.26** via the Epic Games Launcher
2. Clone the repo
3. Right-click `CatCruise.uproject` → **Generate Visual Studio project files**
4. Open in UE4.26

> For Android builds, configure your Android SDK/NDK paths in **Project Settings → Platforms → Android**.
> Google Play Games integration requires a configured Google Play Console app with a matching App ID.

---

## License

MIT
