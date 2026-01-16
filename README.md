
# Snake Game (Python + Pygame)

Classic arcade action! Guide the snake to eat food, grow longer, and survive as long as possible. Built with smooth Pygame graphics and responsive controls.

---

## Objective

The objective of the game is to control a snake on a grid and eat food items to grow in length.  
The game ends when the snake collides with its own body.

---

## Game Setup

- Screen Size: **600 x 600 pixels**
- Snake starts at the center of the screen  
- Food appears randomly on the grid  
- Snake moves in steps of **10 pixels**  
- The snake wraps around the screen edges  

---

## Gameplay Mechanics

### Snake Movement

- The snake moves continuously in the direction selected by the player.
- Controls:
  - ⬅ Left Arrow – Move Left  
  - ➡ Right Arrow – Move Right  
  - ⬆ Up Arrow – Move Up  
  - ⬇ Down Arrow – Move Down  

- When the snake crosses the screen border, it appears from the opposite side.

---

### Eating Food

- Food appears randomly on the screen.
- When the snake eats the food:
  - The snake grows longer  
  - A new food item appears at a random location  

---

### Game Over

- The game ends if the snake collides with its own body.
- `"GAME OVER"` is printed in the console.

---

## Game Features

- Black background  
- Green snake body  
- White food item  
- Smooth movement with real-time keyboard input  
- Edge wrap-around feature  

---

## Future Improvements

- Add score display  
- Add levels with increasing speed  
- Add obstacles  
- Add restart option after game over  

---

# Installation

## Requirements

Before running the game, make sure you have the following installed:

- Python 3.x
- Pygame Library (`pip install pygame`) // use python -m pip install pygame 

## Installation Steps

1. **Clone the Repository:
      git clone https://github.com/sankatimeghana/Snake-Game.git**
    
2. **Install Pygame:
      If Pygame is not installed, install it using pip: pip install pygame**
   
3.  **And at last Run the Game**
