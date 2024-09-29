# 3D Physics Engine

A simple 3D physics engine built with `three.js` to simulate bouncing balls in a 3D space. The simulation applies basic physics principles such as gravity and collision detection with the ground.

## Features

- 3D rendering using `three.js`
- Simple physics simulation: gravity and bouncing
- Randomized colors and velocities for objects
- Responsive design: canvas adjusts to window size

## Getting Started

To run the project, you only need a modern web browser with WebGL support.

### Live Preview

To view the simulation, simply open the `index.html` file in a web browser.

### How It Works

1. **Gravity**: A constant downward force is applied to all objects.
2. **Collisions**: When an object hits the ground, its velocity is reversed, simulating a bounce. The velocity is slightly reduced to mimic energy loss.
3. **Randomization**: Each ball is given a random position, color, and initial velocity for more dynamic simulation.

## Requirements

- Web browser with WebGL support (most modern browsers)
- Internet connection to load the `three.js` library from the CDN

## Customization

Feel free to modify the `index.html` file to:

- Change the number of balls created
- Adjust gravity or velocity dampening
- Add more 3D objects or advanced physics like friction

## License

This project is open source and available under the [MIT License](LICENSE).
