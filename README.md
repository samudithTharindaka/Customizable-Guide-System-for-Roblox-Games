# Roblox Guide System

Enhance player experiences in your Roblox games with our customizable guide system. Instruct seamlessly and customize interactions to create engaging gameplay.

## Introduction

This guide system is designed to provide interactive instructions to players within Roblox games. By integrating this system, you can enhance the player's understanding of game mechanics, objectives, and controls, thereby improving their overall experience. Its also comes with handy animations

## Features

- **Customizable Guide Texts:** Easily customize guide texts to suit your game's specific needs. Update instructions, tips, or objectives as needed to keep players engaged.

- **Seamless Integration:** Integrate the guide system seamlessly into your game's user interface. The system provides a smooth and non-intrusive way to convey information to players.

- **Versatile Usage:** Use the guide system to instruct players on various aspects of your game, including controls, objectives, gameplay mechanics, and more. The system's versatility allows for a wide range of applications.

## Getting Started

To integrate the guide system into your Roblox game, follow these steps:

1. **Download the Script:** Download the `GuideSystem.lua` script file from this repository.

2. **Add Script to Game:** Insert the `GuideSystem.lua` script into your game's Workspace or ServerScriptService. Make sure it is a local script
   
3. **Connect the variables:**  connect the text label that you need to animate to the variable at the top of the script

4. **Customize Guide Texts:** Modify the `guideTexts` table in the script to include the desired guide texts for your game.

5. **Run the Script:** Run the script in your game to display the guide texts to players.

## Example Usage

```lua
-- Insert the GuideSystem.lua script into your game
local guideSystem = require(game.ServerScriptService.GuideSystem)

-- Customize the guide texts
local guideTexts = {
    "Welcome to our game!",
    "Use WASD to move around.",
    "Press Space to jump.",
    "Collect coins to score points.",
    "Avoid obstacles to stay alive.",
    "Have fun playing!"
}

-- Initialize the guide system
guideSystem.init(guideTexts)
