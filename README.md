# Cat Interactive AR

Cat Interactive AR is a **Unity-based AR project** that simulates interaction with a virtual 3D cat using **hand gestures** in the real world.

The project combines **Augmented Reality (AR)** and **Computer Vision (CV)** to allow users to interact with a virtual pet in a more natural way, without relying on screen touch input.  
This project was developed as part of a university course project.

## What This Project Does
- Displays a 3D cat model in an AR environment
- Uses the device camera for real-time interaction
- Detects hand landmarks using Mediapipe Hand Landmarker
- Uses hand position and simple gesture cues as input
- Triggers basic responses or animations from the virtual cat

This project focuses on interaction design rather than complex AI behavior.

## Core Technologies
- Unity
- AR Foundation
- Mediapipe Hand Landmarker
- Computer Vision (Hand Tracking)
- C#

## Project Structure
```base
CatInteractiveAR/
├── Assets/ # Unity assets and scripts
├── Final_Build_And_Markers/ # Prebuilt version and AR markers
├── Packages/ # Unity packages
├── ProjectSettings/ # Unity project settings
├── README.md
└── .gitignore
```

## How It Works
1. The AR camera captures live video
2. Hand landmarks (21 points) are detected from the camera feed
3. Hand position is mapped into the AR scene
4. Simple conditions are used to detect interaction states
5. The virtual cat responds through movement or animation

## Setup and Installation
**Requirements**
- Unity (with AR Foundation installed)
- AR-supported device
- Unity Hub

**Installation**
1. Clone the repository  
```bash
  $ git clone https://github.com/sSODAs/Cat_Interactive_AR.git
```
2. Open the project using Unity Hub
3. Open the main scene and run in the Editor or build the project to an AR-supported device

<br>

## Notes
- This project is intended for learning and demonstration purposes
- Hand tracking performance depends on lighting and camera quality

