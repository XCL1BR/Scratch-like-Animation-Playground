# Scratch-like-Animation-Playground
A project inspired by the MIT Scratch app, built using **React**, **TailwindCSS**, **npm Blockly**, and **Phaser**. This application allows users to create and animate multiple sprites, implement motion controls, and utilize drag-and-drop blocks for interactive sprite manipulation.

Live: https://scratch-like-animation-playground.vercel.app/

## Features

### 1. Motion Animations

Under the "Motion" category, the following animations are available:

- **Move Steps**: Moves a sprite by the specified number of steps.
- **Turn Degrees**: Rotates a sprite by a given number of degrees.
- **Go to X & Y**: Moves the sprite to specified x and y coordinates.
- **Repeat Animation**: Loops the motion block(s) as long as specified.

### 2. Multiple Sprites Support

- Ability to create and animate multiple sprites.
- Each sprite can have its own motion animation.
- A "Play" button starts animations for all sprites simultaneously.

### 3. Hero Feature: Collision-Based Animation Swap

- When two sprites collide, their animations swap dynamically.

## Tech Stack

- **React**: For building the UI components.
- **TailwindCSS**: For easy, responsive styling.
- **Blockly**: For implementing drag-and-drop functionality similar to the Scratch interface.
- **Phaser**: For sprite animation and collision detection.

