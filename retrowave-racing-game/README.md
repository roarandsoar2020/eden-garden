# Retrowave Racing Game

This is a single spec that produces a complete, impressive game with no scaffolding or partial work.The Agent makes autonomous decisions about geometry, animation, particle systems, and performance based on the set goals.

## The Core Specification

```
Build a high-octane 3D retrowave racing game with endless synthwave aesthetics, neon visuals,
and intense arcade driving action. Single HTML file using Three.js. Arrow keys for steering,
speed increases over time, neon grid road, synthwave color palette (purple, pink, cyan),
score based on distance.
```

## What to Look For in the Output

### Visual Elements
- **Neon Grid Road**: A stylized road with glowing grid lines (cyan/pink color)
- **Synthwave Sky**: Gradient background with purples, pinks, and cyans
- **Neon Obstacles**: Bright obstacles with glow effects (cubes, walls, or geometric shapes)
- **Camera Movement**: Smooth camera following or third-person view of the car

### Game Mechanics
- **Keyboard Control**: Arrow keys (or WASD) for steering, movement feels responsive
- **Acceleration**: Speed increases automatically over time (or with throttle); feel the progression
- **Add life lines**: "Start the game with 3 life lines. When the car hits an obstacle, reduce life line by 1. When life line is 0, cause the game over. Game should not get over if there is still life line left."
- **Score/Distance**: Counter that increases as you move, visible on screen

### Code Quality
- **Single HTML File**: No external imports except Three.js from CDN
- **Inline CSS & JS**: Everything in one file, ready to run
- **Performance**: 60 FPS with smooth rendering

---

## Upcoming Enhancements (Backlog for Jules)

1. **Add hazards**: "Add enemy cars that patrol the road. Additionaly add moving obstacles." 
2. **Add music**: "Add a synthwave audio track from a royalty-free source (or generate one)."
3. **Difficulty progression**: "Make enemy cars and obstacles appear more frequently as the score increases."
4. **High score persistence**: "Save the top 3 scores to localStorage and display them on a game-over screen."

---
