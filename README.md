Here's the text for the README.md file:

# bootdev-asteroids

This repository contains a Python implementation of the classic Asteroids game, created as part of the Boot.dev curriculum.

## Description

This project is a simplified version of the Asteroids arcade game. The game features:

* A player-controlled spaceship.
* Asteroids of varying sizes.
* Shooting mechanics to destroy asteroids.
* Basic game loop.

## Features

* **Asteroid Generation:** Randomly generated asteroids of different sizes and speeds.
* **Player Control:** Control the spaceship's movement and firing using keyboard inputs.
* **Collision Detection:** Detects collisions between the player, asteroids, and shots.

## Getting Started

### Prerequisites

* Python 3.x
* `pip` (Python package installer)

### Installation

1. Clone the repository:

    ```
    git clone https://github.com/radnunes/bootdev-asteroids.git
    cd bootdev-asteroids
    ```

2. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

### How to Run

To start the game, execute the following command in your terminal:

```
python main.py
```

Make sure you are in the root directory of the repository before running this command.

## File Structure

* `asteroid.py`: Defines the Asteroid class and its behavior.
* `asteroidfield.py`: Manages the creation and updates of the asteroids.
* `circleshape.py`: Defines circular shapes used for objects like asteroids and shots.
* `constants.py`: Contains various constant values used throughout the game.
* `main.py`: The main entry point of the game; handles the game loop.
* `player.py`: Defines the Player class (spaceship) and its controls.
* `requirements.txt`: Lists the project's dependencies.
* `shot.py`: Defines the Shot class (projectiles fired by the player).

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests. 

## License

MIT License
