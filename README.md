# Snake Game

A classic arcade-style Snake game built with Python using an Object-Oriented Programming (OOP) approach. This project demonstrates clean code structure and real-time event handling using the Turtle graphics library.

## Key Features

- Modular Architecture: The game logic is split into dedicated classes (Snake, Food, Scoreboard) for better scalability and readability.

- Collision Detection: Precise mathematical checks for wall boundaries, self-collisions, and food consumption.

- State Management: Real-time scoring and "Game Over" sequences handled through a centralized game loop.

- Custom Graphics: A minimalist, high-contrast UI designed for clarity.

## Technical Implementation

The project utilizes the Turtle module to handle the GUI and key bindings.

## Collision Logic:
 The game uses the Pythagorean distance formula to detect when the snake "eats" the food.

## File Structure:
- main.py: The entry point that manages the game loop and screen updates.

- snake.py: Defines the snake's body, movement, and growth logic.

- food.py: Handles the random generation of food items.

- scoreboard.py: Manages the UI text and score tracking.

## How to Play:

1. Clone the repo:  git clone https://github.com/janice-1705/snake_game.git
   
2. Run the script: python main.py

3. Use your Arrow Keys to move the snake and collect the blue food!
