# Indian Vocal Synth

## Overview
This application is a visual editor for creating Indian vocal music patterns using Swar notation.

## How It Works
- A point indicates the frequency (pitch).
- Distance between points indicates time duration.
- Shape of the curve between points indicates the glide from one frequency to another.
- Time moves from left to right direction.
- X axis represents time.
- Y axis represents tone (Swar).

## Features
- Add curve points with a click
- Add square Swar points with Shift+Click
- Select points with Ctrl+Click (both curve and Swar points)
- Delete selected points with the "Delete Selected" button
- Drag points to move them
- Adjust curves with handles
- Play the created sequence
- Toggle grid and handles visibility
- Undo/Redo functionality

## Usage
Run the application using live-server:
```
npm install -g live-server
live-server
```
