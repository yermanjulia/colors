# Color Application
This application is a simple web-based random color generator built using HTML, CSS, and JavaScript.

## Overview
The color application presents a simple user interface with columns, each displaying a unique randomly generated color. Users can click on the lock button to retain a specific color across subsequent color refreshes. The application also responds to keyboard events, specifically the spacebar, to generate a new set of random colors.

Colors are generated in RGB format with Hex color codes, with an option to lock specific colors and maintain them while the others change.

## Files
The application consists of three main files:

1. `index.html`: This is the main page of the application, where colors are displayed in individual columns. Each column includes a color indicator and a lock button.
2. `styles.css`: This file contains the styling for the application, including the layout of the color columns and the hover effects for interactive elements.
3. `app.js`: This is the main logic of the application. It handles generating random colors, setting the colors in the UI, locking and unlocking colors, and setting the text color based on the luminance of the background color.

## Usage

1. Open `index.html` in your preferred web browser to start the application.
2. Each color column displays a color and a lock button. If you want to keep a specific color while generating new ones for the other columns, click the lock button next to that color.
3. Press the spacebar to generate a new set of random colors. Any column that is locked will retain its color while the others change.

### Dependencies
The application depends on:

`Chroma.js:` A small JavaScript library for dealing with colors. It is used to calculate the luminance of color to determine the best text color for contrast.

`Font Awesome:` A toolkit for web icons. It is used for the lock and unlocks icons in the color columns.

`Google Fonts:` A library of licensed fonts. The application uses the 'Roboto', 'Barlow', and 'Poppins' fonts.

