# 40-Hz

40-Hz is a simple web application designed to play a 40 Hz tone, which is often used for binaural beats to improve focus, relaxation, and meditation. This application also includes a bell notification feature that can be customized for different intervals.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- Plays a 40 Hz tone in a loop for binaural beats.
- Customizable bell notification with adjustable intervals.
- Simple and clean user interface with background image and logo.

## Installation

1. Clone the repository:
   git clone https://github.com/philiposullivan/40-Hz.git
2. Navigate to the project directory:
   cd 40-Hz
3. Open `40hz.html` in your preferred web browser.

## Usage

1. Click the play button to start playing the 40 Hz tone. The audio will loop between 5 and 20 seconds.
2. Click the bell icon to play a bell sound and set an interval for repeated notifications. The interval can be adjusted by clicking the bell icon multiple times:
   - First click: 1-minute interval
   - Second click: 5-minute interval
   - Third click: 10-minute interval
   - Fourth click: Resets to 1-minute interval

## Customization

### Background Image

To change the background image, replace the `download.jpg` file in the `src/img` directory with your preferred image. Ensure the file name remains the same or update the background property in the CSS body selector within the `styles.css` file.

### Logo

To change the logo, replace the `logo_256_white.png` file in the `src/img` directory with your preferred logo. Ensure the file name remains the same or update the `src` attribute of the `<img>` tag in the HTML.

### Audio Files

To use different audio files:

1. Replace `9a.ogg` with your desired 40 Hz tone file.
2. Replace `bell.ogg` with your preferred bell sound file.
3. Ensure the file names remain the same or update the `src` attributes of the respective `<audio>` tags in the HTML.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin my-feature-branch`
5. Submit a pull request.

## License

This project is Open Source. 
