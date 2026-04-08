# 🍎 AR Apple Catcher Game (Built using Meta Spark AR)

## Overview

This project is an interactive AR filter game built using **Meta Spark AR**. The game uses **face tracking** to control a virtual basket that moves with the player's head movement. Apples fall from random positions on the screen, and the player must **catch them in the basket** by moving their face.

The game keeps track of the player's **score** and provides **three lives** before ending, creating an engaging and playful augmented reality experience.

## Features

- 🧠 **Face tracking:** The basket follows the user's chin movement in real time.  
- 🍏 **Random apple spawns:** Apples fall from different positions to make each game unique.  
- 🪣 **Collision detection:** When the apple hits the basket, the score increases.  
- ❤️ **Lives system:** Players get three lives before the game ends.  

## How It Works

1. The face tracker detects the user's face and attaches a virtual basket near the chin.
2. Apples are spawned from random positions above the screen.
3. Each time an apple enters the basket's area, the score increases.
4. If an apple falls without being caught, one life is deducted.
5. After three missed apples, the game displays a "Game Over" message.

## How to Clone This Repository

To get a copy of this project on your local machine, follow these steps:

### Prerequisites
- Git installed on your system ([Download Git](https://git-scm.com/))

### Steps

1. **Open your terminal/command prompt** and navigate to your desired directory:
   ```bash
   cd path/to/your/directory
   ```

2. **Clone the repository:**
   ```bash
   git clone https://github.com/K-Tanish/SparkAR-ARExperience.git
   ```

3. **Navigate to the project folder:**
   ```bash
   cd SparkAR-ARExperience
   ```

## How to Run on Local Device

To run this AR experience on your local device, follow these steps:

### Prerequisites
- **Meta Spark AR** installed ([Download Meta Spark AR](https://www.meta.com/en/spark/tools/spark-ar-studio/))
- A compatible device:
  - **iOS:** iPhone 6S or newer with iOS 12+
  - **Android:** Android 8.0+ with ARCore support
  - **Meta/Facebook:** Cameras app on compatible Meta devices

### Steps

1. **Open Meta Spark AR Studio** on your computer

2. **Open the project:**
   - Go to `File` → `Open` (or `File` → `Recent`)
   - Navigate to the cloned repository folder
   - Select the `AppleCatcher.arproj` file

3. **Test in the simulator:**
   - Click the **Play** button or press `Ctrl+Enter` (Windows) / `Cmd+Enter` (Mac)
   - Use the simulator to test the game with face tracking
   - Interact with the virtual face tracker to control the basket

4. **Build and deploy to your device:**
   - On the right panel, click the **Export** button or go to `File` → `Export`
   - Choose your target platform:
     - **Instagram Story Camera:** Select the Instagram option
     - **Meta Audience Network:** For other Meta platforms
   - Follow the platform-specific instructions to publish and test on your device
   - Scan the QR code or access the effect on your mobile device camera

5. **Enjoy the game!**
   - Open the AR filter on your mobile device
   - Allow camera and face tracking permissions
   - Start catching apples with your face!
