# fps-mp-photon

A Unity multiplayer FPS project using Photon networking.

## Overview

This project is focused on building a fast-paced first-person shooter with online multiplayer support.  
The current repository includes the core Unity project structure and is set up for iterative gameplay and networking development.

## Tech Stack

- Unity `6000.3.8f1` (Unity 6)
- C#
- Unity Input System
- Photon (multiplayer networking)

## Current Project Structure

- `Assets/` game content, scenes, scripts, prefabs, and settings
- `Packages/` Unity package dependencies
- `ProjectSettings/` Unity project configuration

Current scene in repo:
- `Assets/Scenes/SampleScene.unity`

## Getting Started

1. Open Unity Hub and add this project folder.
2. Open the project with Unity `6000.3.8f1`.
3. Open `Assets/Scenes/SampleScene.unity`.
4. Press Play to run locally.

## Photon Setup

1. Create or use an existing Photon account and app.
2. Add your Photon App ID to your Photon settings in Unity.
3. Ensure your multiplayer scripts/components are configured to connect to Photon Cloud.

## Roadmap Ideas

- Player movement and aiming polish
- Weapon firing and hit detection
- Room/lobby flow (create/join match)
- Player sync (position, rotation, animation, health)
- Match flow (spawn, respawn, win conditions)
