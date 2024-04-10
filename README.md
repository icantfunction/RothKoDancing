# RothKo Dancing

This project is a simple web page that uses HTML and CSS to create a visual representation inspired by the works of the painter Mark Rothko. The page consists of a frame containing a canvas, which in turn contains three colored blocks.

## Files

The project consists of two main files:

1. `RothKoDancing.html`: This is the main HTML file. It sets up the structure of the page, linking to the CSS file for styling.

2. `styles.css`: This file contains the CSS styles for the page. It defines the layout and appearance of the frame, canvas, and the three colored blocks.

## Structure

The HTML structure consists of a `div` with the class `frame`, which contains another `div` with the class `canvas`. Inside the `canvas` are three more `div` elements with the classes `one`, `two`, and `three`.

## Styling

The CSS file defines the following styles:

- `.frame`: This class defines the outer frame. It has a solid black border, a width of 500px, and is centered on the page.

- `.canvas`: This class defines the canvas inside the frame. It has a width of 500px, a height of 600px, and a dark brown background color. It also has an overflow property set to hidden to prevent content from spilling out of the canvas.

- `.one`, `.two`, `.three`: These classes define the three colored blocks inside the canvas. Each block has a different size, color, and rotation.

## Viewing the Project

To view the project, open the `RothKoDancing.html` file in a web browser. The styles from the `styles.css` file will be applied to the HTML structure, creating the final visual representation.