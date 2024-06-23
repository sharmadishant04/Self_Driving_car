# Self-Driving Car AI

This project implements a self-driving car simulation using deep Q-learning. The car learns to navigate a virtual environment with obstacles, aiming to reach a specific goal while avoiding collisions.

## Features

- Uses PyTorch to implement a deep Q-learning neural network.
- Includes experience replay for training the model.
- Simulates the car's environment with Kivy.
- Allows interactive drawing of obstacles on the map.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/self-driving-car-ai.git
    cd self-driving-car-ai
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\\Scripts\\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

Run the script to start the self-driving car simulation:

```sh
python map.py
