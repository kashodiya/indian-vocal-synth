# Indian Vocal Synth

A web-based Bezier curve editor for creating and manipulating vocal synthesis curves with Indian classical music notation (Swar) support.

## Features

### Bezier Curve Editor
- **Interactive Point Creation**: Click anywhere to add curve points, Shift+Click to add Swar points
- **Curve Manipulation**: Drag points and handles to shape your curves
- **Grid System**: 40px grid with precise positioning
- **Grid Snapping**: All points automatically snap to grid intersections
- **Multi-Selection**: Ctrl+Click on curve points to select/deselect multiple
- **Undo/Redo**: Full history system with keyboard shortcuts

### Indian Swar Notation System
- **Swar Points**: Square notation points representing Indian classical music swars
- **36 Swars**: Complete range across 3 octaves (lower, middle, upper)
- **Interactive Swar Change**: Click on Swar points to enter change mode
- **Arrow Key Navigation**: Up/Right for higher swar, Down/Left for lower swar
- **Visual Feedback**: Yellow border indicates active swar change mode
- **Devanagari Font**: Uses "ome-bhatkhande-hindi" font for authentic notation

### Controls
- **Mouse Controls**:
  - Click to add curve points (circles)
  - Shift+Click to add Swar points (squares)
  - Drag points to move them (snaps to grid)
  - Drag handles to adjust curve shape
  - Click on curves to add points along them
  - Ctrl+Click on curve points to select/deselect multiple
  - Click on Swar points to enter swar change mode
  - Click on empty canvas to deselect points

- **Keyboard Shortcuts**:
  - `Arrow Keys` - Navigate swars in swar change mode
  - `Escape/Enter` - Exit swar change mode
  - `Delete` - Delete selected points
  - `Ctrl+Z` (or `Cmd+Z`) - Undo last action
  - `Ctrl+Y` or `Ctrl+Shift+Z` - Redo action

- **UI Buttons**:
  - Clear All - Remove all points
  - Delete Selected - Remove selected points
  - Toggle Grid - Show/hide grid lines
  - Toggle Handles - Show/hide control handles
  - Undo/Redo - History navigation

## Getting Started

### Running with Live Server
1. Install live-server globally: `npm install -g live-server`
2. Navigate to the project directory
3. Run: `live-server --port=8080 --host=0.0.0.0`
4. Open your browser to the provided URL

### Basic Usage
1. **Create Curve Points**: Click on empty canvas areas
2. **Create Swar Points**: Hold Shift and click on canvas
3. **Edit Swars**: Click on any Swar point to enter change mode, use arrow keys
4. **Move Points**: Drag any point to reposition (snaps to grid)
5. **Shape Curves**: Drag the control handles to adjust curve shapes

### Coordinate System
- **X-axis**: Represents time progression
- **Y-axis**: Represents tone/pitch (Swar) levels

## Technical Details

- Built with p5.js for canvas rendering and interaction
- Grid system with 40px spacing for precise positioning
- 36 Indian classical swars across 3 octaves (lower, middle, upper)
- History system supports up to 50 undo/redo operations
- All point operations snap to grid intersections for accuracy
- Devanagari font support for authentic swar notation
- Responsive canvas design adapts to different screen sizes

## Swar Mapping

The system includes 36 swars across three octaves:
- **Lower Octave**: sl, Rl, rl, Gl, gl, ml, Ml, pl, Dl, dl, Nl, nl
- **Middle Octave**: s, R, r, G, g, m, M, p, D, d, N, n  
- **Upper Octave**: su, Ru, ru, Gu, gu, mu, Mu, pu, Du, du, Nu, nu