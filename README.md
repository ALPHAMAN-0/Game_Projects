# Game Projects

A collection of game development projects built in Java.

## Project 1: Flappy Bird

A clone of the classic Flappy Bird game built with Java Swing. The player controls a bird that must navigate through randomly generated pipes without collision.

### Features

- Bird movement with gravity and jump mechanics
- Randomly generated pipe obstacles
- Collision detection with pipes and screen boundaries
- Sound effects (background music and game over sound)
- Score tracking

### How to Run

1. Make sure you have **Java JDK 8+** installed
2. Navigate to the `Project 1/` directory
3. Compile and run:
   ```bash
   javac App.java FlappyBird.java
   java App
   ```

### Project Structure

```
Project 1/
├── App.java              # Entry point, sets up JFrame window
├── FlappyBird.java       # Game logic, rendering, and input handling
├── Image/                # Game sprites (bird, pipes, background)
├── Song/                 # Audio files (background music, game over)
├── Photo/                # Development diagrams and screenshots
└── Presentation/         # Project presentation (Flappy Bird.pptx)
```

### Controls

- **Spacebar** or **Click** -- Make the bird jump
