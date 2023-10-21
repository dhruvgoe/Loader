# Loader Animation

This repository contains a simple loader animation created using HTML and CSS. The loader consists of a rotating circle with changing colors, providing a visually appealing loading effect.

## Features
**Dynamic Animation**: The loader animation utilizes CSS animations to create a rotating effect with changing colors at each quarter rotation, providing an engaging loading experience.

## Getting Started
To use this loader animation, simply include the **index.html** file and **style.css** file in your project.
Link the style.css file in your HTML file to apply the loader styles.

## Usage

### HTML (index.html):
The HTML file sets up the basic structure of the webpage. It includes a <div> element with a class of wrapper that contains another <div> element with a class of loader. The loader animation will be displayed inside this loader div.

### CSS (style.css):
**.wrapper**:

This class sets the margin, padding, and box-sizing properties to ensure that the loader is properly positioned and sized within the webpage.

**.loader**:
The loader class styles the circular loader element.

border property creates a thick circle by defining a 20-pixel border with a light gray color (#f3f3f3).

border-top property changes the color of the top part of the circle to create a colorful loading effect. The loader's top border starts blue, then changes to red, yellow, and green as it completes each quarter rotation.

border-radius property sets the border corners to create a circular shape.

width and height properties specify the dimensions of the loader (150 pixels by 150 pixels).

animation property applies the spin animation to the loader. The animation lasts for 3 seconds (3s), follows a linear timing function, and continues infinitely.

**@keyframes spin**:

This CSS rule defines the spin animation.

At 0%, the loader starts with no rotation.

At 25%, it rotates 90 degrees and changes the top border color to red.

At 50%, it completes half a circle (180 degrees) and changes the top border color to yellow.

At 75%, it rotates 270 degrees and changes the top border color to green.

At 100%, it completes a full circle (360 degrees) and restarts the animation.

## Customization

You can customize the loader appearance by adjusting the border and border-top properties in the .loader class to change the thickness and color of the loader circle and its segments.

Modify the animation duration in the @keyframes spin rule to make the rotation faster or slower by changing the 3s value to your desired duration.

## Contributing
Contributions are welcome! If you have ideas for improvements or find any issues, please create an issue or submit a pull request.


Feel free to modify the README file to include specific instructions, guidelines for contributors, or any other information relevant to your project. **Happy coding!**
