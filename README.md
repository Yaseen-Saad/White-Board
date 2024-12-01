# Canvas White Board

## Description

The **Canvas Drawing Board** is an advanced HTML5 drawing application that allows users to draw, erase, and save their artwork. The board supports a variety of features such as customizable brush size and color, the ability to add text, background uploads, gradient backgrounds, and more. Additionally, users can undo and redo their actions, providing a seamless experience while creating or editing their artwork.

## Features

- **Drawing Mode**: Draw freely on the canvas with adjustable brush size and color.
- **Eraser Mode**: Erase parts of your drawing using the eraser tool.
- **Brush Size**: Adjust the brush size with a range slider.
- **Brush Color**: Pick any color from the color picker to draw on the canvas.
- **Text Tool**: Add text to the canvas with customizable font, size, and color.
- **Grid Overlay**: Toggle a grid overlay for better precision while drawing.
- **Clear Canvas**: Clear the canvas to start a new drawing.
- **Gradient Tool**: Apply linear or radial gradients as a background to the canvas.
- **Background Image Upload**: Upload your own background image for the canvas.
- **Undo and Redo**: Undo and redo your drawing actions.
- **Save Drawing**: Save your artwork as a PNG image.

## Installation

1. Clone or download the repository.
2. Open the `index.html` file in your browser to start using the drawing board.

## Usage

1. **Drawing**: Use your mouse or touchpad to draw on the canvas.
2. **Brush Size**: Use the brush size slider to adjust the width of your brush.
3. **Brush Color**: Use the color picker to select the brush color.
4. **Text Tool**: Click on the "Add Text" button to add text to the canvas. Customize font size and color.
5. **Eraser**: Toggle the eraser mode by clicking the "Eraser" button to erase parts of your drawing.
6. **Clear Canvas**: Click the "Clear" button to remove all drawings from the canvas.
7. **Grid Overlay**: Toggle the grid overlay on the canvas for more precision while drawing.
8. **Gradient Background**: Apply a gradient background using the "Gradient" button.
9. **Background Image**: Upload an image file to use as the background for the canvas.
10. **Undo/Redo**: Use the "Undo" and "Redo" buttons to navigate back and forth through your drawing actions.
11. **Save**: Click the "Save" button to download your drawing as a PNG file.

## Code Structure

- `index.html`: Main HTML file that includes the canvas and toolbar.
- JavaScript section:
  - Handles the drawing and erasing functionality.
  - Manages the undo and redo stacks.
  - Handles various features like text tool, gradient background, and grid overlay.
  - Saves and loads images to and from the canvas.

## Requirements

- A modern web browser (Google Chrome, Firefox, Safari, etc.) with support for HTML5 Canvas.

## Known Issues

- The canvas background might not scale well with images that are too large.
- The undo/redo functionality works in a limited history stack and may not be as efficient for long drawing sessions.

## Contributing

Feel free to fork this project, open issues, and submit pull requests. Contributions are welcome! Please make sure to test your changes thoroughly before submitting.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

### Example Usage

To see the canvas in action, follow these steps:
1. Open the `index.html` file in a browser.
2. Start drawing by clicking and dragging the mouse.
3. Use the toolbar buttons to adjust your drawing tool settings, such as size, color, and brush type.
4. Save your work once finished!
