# TANGRAM

Interactive Tangram puzzle application created in C++ with wxWidgets.

This project was co-developed for the 2024 **“Basics of Computer Graphics”** course at **AGH University of Krakow**.

## Project overview

The application lets you solve Tangram silhouettes by moving and rotating the seven classic Tangram tiles.

Main interface areas:
- **Workspace** – area where you arrange tiles
- **Image panel** – target silhouette to recreate
- **Tray** – initial tile container

## Features

- Drag-and-drop style tile placement
- Tile rotation while holding a tile
- Randomly selected silhouette challenge
- Optional silhouette solution preview
- Reset/clear board functionality

## Controls

- **Left mouse button (tray):** pick a tile from the tray
- **Left mouse button (workspace):** hold and move a tile
- **Q / E:** rotate currently held tile
- **Right mouse button (workspace):** return selected tile to tray
- **Wyczysc:** clear workspace and reset tiles
- **Nowy obrazek:** generate a new silhouette challenge
- **Rozwiazanie:** show solution silhouette

## Tech stack

- **Language:** C++
- **GUI:** wxWidgets
- **IDE/Build environment:** Visual Studio solution (`TANGRAM.sln`)

## Repository structure

- `/TANGRAM/main.cpp` – application entry point
- `/TANGRAM/GUIMyFrame1.*` – main application logic and event handling
- `/TANGRAM/GUI.*` – wxFormBuilder-generated UI class
- `/TANGRAM/Tan.*` – Tangram tile model, transformations, hit testing
- `/TANGRAM/DrawingFunctions.cpp` – drawing logic for workspace/tray/target silhouettes

## Running the project

1. Open `/home/runner/work/TANGRAM/TANGRAM/TANGRAM.sln` in Visual Studio.
2. Ensure wxWidgets is installed and configured in your Visual Studio environment.
3. Build and run the `TANGRAM` project.

> Note: The repository includes project source files and solution metadata; adjust local Visual Studio/wxWidgets settings if needed.
