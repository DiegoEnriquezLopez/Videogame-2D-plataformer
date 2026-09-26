**2D Platformer Game**

<img width="1513" height="524" alt="Portada" src="https://github.com/user-attachments/assets/505f53f0-03f5-4a76-b36f-39e3c4055338" />

**Overview**

This videogame is a platforming game developed in Unity using C#. The project consists of three levels with different environments and progressively increasing difficulty. The player must navigate each level, interact with its gameplay elements, and reach the objective while managing the available lives.

**Gameplay**

The player controls a girl character who can move horizontally and jump. The game is based on platforming mechanics, where movement and jumping are used to navigate the level and interact with enemies, collectibles, and environmental hazards.

The game features a life system and level progression across three stages. Each level introduces different combinations of gameplay elements and progressively more challenging layouts.

**Enemies**

Slimes are the main enemies encountered throughout the game. Their interaction with the player depends on the direction of the collision.

- Front or back: The player loses one life.
- From above: The slime is eliminated.

When a slime is eliminated, an explosion animation is triggered as visual feedback.

**Obstacles**

- Fire: An environmental hazard placed throughout the levels. If the player touches the fire, the current level is restarted.

- Spikes: Stationary hazards that require the player to carefully time their movement and jumps. Touching a spike causes the current level to restart.

**Collectibles**

-Coins: Distributed throughout the levels and can be collected by the player. Collecting a coin triggers a sparkle particle effect and an audio cue.

**GUI**

The game's graphical user interface provides information and controls for the player.

The interface includes:

- Hearts: Display the player's remaining lives.
- Buttons: Provide the game's interactive interface controls.

The GUI uses imported button assets to define the visual appearance of the interface.

**Levels**

The game contains three levels, each with its own environment and layout.

- Level 1: Introduces the basic gameplay mechanics and the game's environment.
- Level 2: Increases the difficulty with a more demanding arrangement of platforms, enemies, and hazards.
- Level 3: Features the most challenging layout, requiring the player to combine the movement and interaction mechanics introduced in the previous levels.

Each level uses different combinations of backgrounds, terrain blocks, and platforms to create its environment.

**Visual Effects**

The project includes several visual assets and effects used to enhance gameplay interactions.

- Backgrounds: Three different background images are used to create the environments.
- Terrain: Ground and terrain blocks are used to construct the levels.
- Explosion: Used when a slime is eliminated.
- Sparkles: Used as a particle effect when collecting coins.

**Audio**

The game includes background music and sound effects associated with specific gameplay events:

- Background music: Plays during gameplay.
- Coin collection: Plays when a coin is collected.
- Player damage: Plays when the player loses a life.
- Game start/restart: Plays when the game begins or a level is restarted.
- Enemy elimination: Plays when a slime is defeated.
- Jump: Plays when the player jumps.
- Level completion: Plays when the player completes a level.

**How to Run**

Requirements

- Unity Hub
- Unity 6.4.7f1

Running the Project

- Clone or download the repository.
- Open Unity Hub.
- Select Add Project.
- Choose the project folder.
- Open the project using the required Unity version.
- Open the main scene.
- Press Play in the Unity Editor.

Building the Game

- Open the project in Unity.
- Go to File → Build Settings.
- Select the target platform.
- Add the required scenes to the build.
- Select Build.
- Choose the destination folder.
- Run the generated application.
