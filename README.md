Digital Clock using JS

A simple, clean, and stylish digital clock created with HTML, CSS, and JavaScript. It displays the current time in a 12-hour format with AM/PM against a cool, tech-inspired background.


✨ Features
Real-time Clock: Displays the current time, updated every second.

12-Hour Format: Shows time in a user-friendly 12-hour format with an AM/PM indicator.

Dynamic and Responsive: The clock is centered and designed to look great on different screen sizes.

Modern UI: Features a clean, futuristic design with a blurred background effect for readability.

📂 File Structure
Here is the structure of the project files:

DIGITAL CLOCK USING JS/
│
├── index.html         # The main HTML file for the clock's structure
├── style.css          # CSS for styling the clock and background
├── index.js           # JavaScript for the clock's functionality
├── COMP.jpeg          # The background image
├── b.exe              # Executable file (not part of the web project)
└── m.exe              # Executable file (not part of the web project)

⚙️ How It Works
The project combines three core web technologies:

index.html: Sets up the basic structure of the webpage. It contains a div element with the ID Clock which acts as the display for the time.

style.css: This file handles the entire visual presentation. It sets the COMP.jpeg image as a fixed, full-screen background. It uses Flexbox to center the clock perfectly on the screen. The clock's text is styled with a monospace font, and a semi-transparent, blurred background is applied to the clock div to make the time legible and stand out.

index.js: This is the engine of the clock.

The updateClock function is the core of the logic. It creates a new Date() object to get the current time.

It then extracts the hours, minutes, and seconds. The hours are converted from 24-hour to 12-hour format, and an AM/PM meridiem is determined.

To ensure a consistent "00:00:00" format, numbers less than 10 are padded with a leading zero.

Finally, the function updates the content of the Clock div with the newly formatted time string.

The setInterval(updateClock, 1000) command ensures that this updateClock function runs every 1000 milliseconds (1 second), keeping the displayed time accurate.

🚀 How to Use
To run this project, you don't need any special setup. Just follow these simple steps:

Clone the repository or download the files.

Navigate to the project directory.

Open the index.html file in your favorite web browser.

The digital clock will be displayed on the page and will start running immediately.

🎨 Customization
It's easy to customize the look and feel of the clock:

Change the Background: To use a different background image, simply replace the COMP.jpeg file with an image of your choice, or update the background-image URL in the style.css file.

Adjust the Font: You can change the clock's font size, color, or family by modifying the properties in the #Clock selector within style.css.

Modify the Clock's Background: The backdrop-filter and background-color properties for the #Clock ID in the CSS file can be adjusted to change the transparency and blur effect behind the time display.
