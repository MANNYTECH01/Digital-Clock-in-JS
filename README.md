Project Overview
This project is a simple, browser-based digital clock that displays the current time in a 12-hour format with AM/PM. The clock is styled with a futuristic, hacker-themed background.

File Descriptions
index.html: The main HTML file that provides the structure for the digital clock. It contains a container for the clock and links to the CSS and JavaScript files.

style.css: The stylesheet for the project. It sets the background image, centers the clock, and styles the clock's appearance, including font, color, and a blurred background effect.

index.js: This file contains the JavaScript code that powers the digital clock. It includes a function to get the current time, format it, and update the display every second.

COMP.jpeg: An image file used as the background for the digital clock, featuring a silhouette of a person in a hoodie against a backdrop of blue numbers.

How It Works
HTML Structure: The index.html file sets up the basic structure of the webpage. It has a div element with the ID Clock which is where the time is displayed.

Styling: The style.css file styles the page. It sets the COMP.jpeg image as the background and centers the clock container. The clock itself is styled with a large, bold, monospace font and a semi-transparent white background with a blur effect to make it stand out from the background image.

JavaScript Logic: The index.js file contains the updateClock function which is the core of the clock's functionality.

This function gets the current date and time using new Date().

It converts the hours to a 12-hour format and determines whether it is AM or PM.

The hours, minutes, and seconds are formatted to always have two digits by adding a leading zero if needed.

The formatted time is then displayed in the Clock div.

The updateClock function is called every second using setInterval to ensure the time is always up-to-date.

How to Use
To use the digital clock, simply open the index.html file in a web browser. The clock will automatically start displaying the current time.

Customization
You can customize the appearance of the digital clock by editing the style.css file. For example:

Background Image: Change the background-image property in the body selector to use a different image.

Font: Change the font-family, font-size, and color properties in the #Clock selector to change the clock's text style.

Clock Background: Modify the backdrop-filter and background-color properties in the #Clock selector to change the appearance of the clock's background.