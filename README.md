Drawing Application

A simple web-based drawing application that allows users to draw on a canvas using customizable colors and thicknesses. This application is built with HTML, CSS, and JavaScript.

Features

Selectable Drawing Color: Users can choose any drawing color using a color picker.

Adjustable Brush Thickness: Brush thickness can be changed via a numeric input.

Clear Canvas Button: Users can reset the canvas to start fresh with the click of a button.

Responsive Design: The interface is user-friendly and adjusts to different screen sizes.


Installation

To set up the drawing application on your local machine, follow these steps:

1. Clone the repository:

git clone https://github.com/yourusername/drawing-app.git
cd drawing-app


2. Open index.html in your web browser:

Simply double-click the index.html file or open it through your browser's file menu.




Usage

1. Select a color from the color picker.


2. Adjust the brush thickness using the numeric input.


3. Click and drag on the canvas to draw.


4. Press the "Clear" button to erase the canvas.



Files

index.html: The main HTML structure of the application.

style.css: Contains the styling for the toolbar, canvas layout, and other UI elements.

script.js: Implements the drawing functionality, color selection, and canvas clearing.


JavaScript Functionality

Drawing Logic: The application listens for mouse events to enable drawing on the canvas. The stroke color and thickness are set based on user input.

Event Listeners:

mousedown: Starts the drawing process.

mousemove: Draws continuously as the mouse moves.

mouseup and mouseout: Stops the drawing when the mouse button is released or the cursor leaves the canvas.


Clear Canvas: The clearCanvas function resets the canvas to a blank state.


CSS Styling

The toolbar is styled with a fixed width, dark background, and white text.

The canvas has a responsive design, with rounded corners and a solid border.

Buttons feature a modern look with a rounded shape and contrasting colors for a user-friendly interface.


Contributing

Contributions are welcome! To improve the application:

1. Fork the repository.


2. Create a new branch for your feature or bug fix.


3. Commit your changes.


4. Push your branch and submit a pull request.



License

This project is licensed under the MIT License.

Acknowledgments

Thanks to MDN Web Docs for providing resources on the HTML5 canvas.

Inspired by various online drawing applications.
