# Interactive_Arch_Viz_UE
Interactive architectural visualization using Unreal Engine

Welcome to the **Interactive Archviz Project**! This repository showcases an advanced architectural visualization project developed using Unreal Engine 5.2. Our project aims to provide an immersive and interactive experience, allowing users to explore and interact with architectural designs in real-time.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Overview

The Interactive Archviz Project leverages the power of Unreal Engine 5.2 to transform architectural designs from SketchUp into a fully interactive 3D environment. This project supports a range of interactive features, enhancing the user's ability to visualize and interact with the architectural space.

## Features

- **First-Person View**: Navigate through the architectural space in a first-person perspective.
- **Teleportation**: Instantly move to different areas within the environment using teleportation mechanics.
- **Door Interactions**: Open and close doors to explore different rooms and spaces.
- **Material Changing**: Change the materials of various surfaces to visualize different design choices.
- **Time of Day Adjustment**: Dynamically adjust the time of day to see how lighting and shadows change.

## Installation

Follow these steps to set up the project on your local machine:

1. **Download the project**
  
2. **Download and install Unreal Engine 5.2** from the [official website](https://www.unrealengine.com/en-US/download).

3. **Install the Datasmith plugin** for SketchUp from the [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/datasmith-exporter).

4. **Convert SketchUp file to Datasmith format**:
   - Open your SketchUp file (.skp) in SketchUp.
   - Use the Datasmith plugin to export the file to Datasmith format (.udatasmith).

5. **Import Datasmith file into Unreal Engine**:
   - Open Unreal Engine 5.2.
   - Import the Datasmith file into Unreal Engine project.
6. **Add your file to level 2 "StartGameMode"**
   - Remove any existing models from the level2
   - Import the model to the workspace
   - Add all necessary collisions into the model
   - Find the door blueprints, add you door meshes to them, and replace your door with this door.
   - Define location and orientation of all lights.
   - Define all materials to be modified.
   - Find the variant manager and add all the necessary variations for your project (lights, time of the day, and materials)
   - When all looks good you can build for Windows, Android and Mac.

## Usage
Find the usage of the build application from the video

## Contact
For any questions or feedback, please contact:
- Minhaj Falaki: minhajfalaki@gmail.com




