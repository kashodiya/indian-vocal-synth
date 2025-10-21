# Indian Vocal Synth

A web-based Bezier curve editor for creating and manipulating vocal synthesis curves.

## Features

### Bezier Curve Editor
- **Interactive Point Creation**: Click anywhere to add new control points
- **Curve Manipulation**: Drag points and handles to shape your curves
- **Grid System**: 20px grid with light grey lines for precise positioning
- **Grid Snapping**: All points automatically snap to grid intersections
- **Multi-Selection**: Shift+Click to select multiple points
- **Undo/Redo**: Full history system with keyboard shortcuts

### Controls
- **Mouse Controls**:
  - Click to add points
  - Drag points to move them (snaps to grid)
  - Drag handles to adjust curve shape
  - Click on curves to add points along them
  - Shift+Click on points to select/deselect multiple

- **Keyboard Shortcuts**:
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

1. Open `index.html` in a web browser
2. Start creating curves by clicking to add points
3. Use the grid for precise positioning
4. Experiment with different curve shapes for vocal synthesis

## Technical Details

- Built with p5.js for canvas rendering
- Grid system with 20px spacing
- History system supports up to 50 undo/redo operations
- All point operations snap to grid intersections
- Responsive design works on different screen sizes