# Tetris Game with Python and Pygame

This repository contains a simple Tetris game implemented in Python using the Pygame library. Tetris is a classic tile-matching puzzle game where players manipulate falling tetrominoes (geometric shapes composed of four square blocks) to create horizontal lines without any gaps. When a line is completed, it disappears, and any blocks above it fall to fill the space.

## Features

- Classic Tetris gameplay experience.
- Use of Pygame library for graphics and user interaction.
- Customizable settings such as game speed and key bindings.
- Score tracking and display.

## Prerequisites

Before running the Tetris game, make sure you have the following installed:

- Python 3.x
- pip (Python package manager)
- Pygame library

## Installation

1. Clone this repository to your local machine:

    ```
    git clone <repository_url>
    ```

2. Navigate to the project directory:

    ```
    cd <project_directory>
    ```

3. Create and activate a virtual environment (optional but recommended):

    ```
    python -m venv venv
    ```

    - On Windows:

        ```
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```
        source venv/bin/activate
        ```

4. Install Pygame library:

    ```
    pip install pygame
    ```

    `or`

    ```
    pip install -r requirements.txt
    ```

## Running the Game
Once you have installed the prerequisites, you can run the Tetris game:

```
python tetris.py
```

## Gameplay Controls

* Left arrow: Move tetromino left.
* Right arrow: Move tetromino right.
* Down arrow: Soft drop (increase falling speed).
* Up arrow: Rotate tetromino clockwise.
* Spacebar: Hard drop (instantly drop tetromino to the bottom).