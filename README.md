# Air-Strike
# Strike Force

A fast-paced 2D side-scrolling air combat game where you pilot a strike fighter across a hostile desert battlefield. Destroy enemy convoys, evade guided missiles, manage fuel reserves, and unleash devastating nuclear strikes to survive as long as possible.

Based on the uploaded game file. 

## Features

* Dynamic desert terrain with hills, valleys, and mountains
* Real-time day and night cycle
* Dynamic weather system with rain effects
* Fuel management system
* Missile warning and threat detection system
* Voice alerts for radar locks and incoming missiles
* Multiple enemy vehicle types
* Homing missile enemies
* Combo scoring system
* Distance-based progression
* Nuclear weapon system
* Mobile touch controls
* Local high score saving
* Particle effects, explosions, smoke, and debris
* Procedural enemy spawning
* Distance bonus rewards

## Enemy Types

### Truck

* Basic ground target
* Fast and lightly armored

### Bus

* Medium durability target
* Higher score reward

### Tanker

* Explosive vehicle
* Causes large chain-reaction explosions

### Convoy Vehicle

* Heavy armor
* High score reward

### Missile Launcher

* Tracks and launches guided missiles
* Most dangerous enemy type

## Controls

### Keyboard

| Key             | Action              |
| --------------- | ------------------- |
| W / Arrow Up    | Climb               |
| S / Arrow Down  | Descend             |
| A / Arrow Left  | Decrease Speed      |
| D / Arrow Right | Increase Speed      |
| Space           | Drop Bomb           |
| N               | Deploy Nuclear Bomb |

### Mobile

* On-screen directional controls
* Fire button
* Nuclear strike button

The game is optimized for landscape orientation on mobile devices.

## Gameplay Mechanics

### Fuel System

Fuel continuously decreases during flight.

* Low speed consumes less fuel
* High speed consumes more fuel
* Collect fuel containers to refill fuel reserves
* Running out of fuel causes engine failure

### Nuclear Weapons

Nuclear bombs are earned through combat performance.

Requirements:

1. Destroy 3 enemy targets to earn 1 nuclear weapon
2. Aircraft must be at high altitude
3. Maximum storage: 3 nuclear weapons

Nuclear strikes create a massive blast radius capable of destroying entire enemy formations.

### Missile Threat System

Threat levels include:

* Radar Detected
* Missile Lock
* Missile Tracking
* Missile Incoming

Visual warnings and voice alerts help the player react to threats.

### Combo System

Destroy enemies rapidly to increase the combo multiplier.

Higher combos provide:

* Increased score rewards
* Faster progression
* Greater combat efficiency

### Distance Rewards

Bonus points are awarded for surviving longer distances.

Milestone rewards increase as distance grows.

## Progression

Difficulty scales automatically based on distance traveled.

As you advance:

* Enemy spawn rates increase
* More missile launchers appear
* Missile accuracy improves
* Enemy formations become larger
* Survival becomes increasingly challenging

## Saving System

The game automatically saves:

* High Score
* Maximum Distance Traveled
* Best Kill Count

Data is stored locally in the browser using Local Storage.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* HTML5 Canvas API
* Web Audio API
* Speech Synthesis API
* Local Storage API

## Installation

1. Download the project files.
2. Open the HTML file in a modern web browser.
3. Click **Initiate Mission**.
4. Start flying.

No external dependencies are required.

## Recommended Browser Support

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Brave

For the best experience, use a browser that supports:

* Web Audio API
* Speech Synthesis API
* HTML5 Canvas

## Objective

Survive as long as possible, travel the greatest distance, destroy enemy forces, maintain fuel reserves, and achieve the highest score before your aircraft is destroyed.
