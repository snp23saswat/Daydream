# Daydream

A Godot Engine game development project/experiment repo, built on a Godot 4 FPS template.

## Contents

- `Godot4-FPS-Template-main.zip` — base FPS template the project builds on
- `3d-project-completed.zip` — a completed 3D project snapshot
- `gunman vs zombie.zip` — a gameplay prototype/build

## Tech Stack

- **Engine:** Godot 4
- **Language:** GDScript (via Godot)

## Getting Started

1. Install [Godot 4](https://godotengine.org/download)
2. Clone this repo and unzip the relevant project archive:
   ```bash
   git clone https://github.com/snp23saswat/Daydream.git
   cd Daydream
   unzip "Godot4-FPS-Template-main.zip"
   ```
3. Open Godot 4, choose **Import**, and select the unzipped project's `project.godot` file.

## ⚠️ Worth cleaning up

Right now the repo is essentially a folder of zipped project archives rather than a checked-in Godot project — that makes it hard to browse the code on GitHub, track changes with git diffs, or collaborate. Consider:
- Unzipping and committing the actual project source (with Godot's standard `.gitignore` for `.godot/`, `*.tmp`, etc.)
- Picking one project as "Daydream" and either removing the others or splitting them into separate repos with clearer names

## Notes

> Add a short description of what "Daydream" actually is as a game (genre, goal, current state — prototype vs. playable), plus a screenshot or clip if you have one.
