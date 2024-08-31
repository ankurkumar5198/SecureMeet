# Privacy Protector Extension

## Overview

The Privacy Protector Chrome Extension is designed to enhance user privacy during online meetings. It addresses the concern of accidental exposure by automatically disabling the user's camera, microphone, or screen share when it detects the user is not present in the scene or is engaged in another activity. This extension aims to prevent potential privacy breaches by ensuring that the user's media is turned off when not actively in use.

## Features

- **Automatic Detection:** Detects when the user is not present in the scene.
- **Privacy Protection:** Automatically disables camera, microphone, or screen sharing.
- **User Notifications:** Alerts users when their media is active while they are not engaged.

## Files

- `background.js`: Contains background script to manage the extension's core functionality.
- `content.js`: Manages interactions with web pages and detects user presence.
- `manifest.json`: Defines the extension’s metadata and permissions.
- `popup.html`: Provides the HTML structure for the extension's popup interface.
- `popup.js`: Contains JavaScript to handle user interactions within the popup.
- `rules.json`: Contains rules and settings for detecting user presence and media control.
- `site.webmanifest`: Defines the web app manifest for the extension.
- `styles.css`: Provides styling for the popup and other UI elements.
- `favicon.ico`: Icon for the extension.
- `favicon-16x16.png`: 16x16 pixel icon for the extension.
- `favicon-32x32.png`: 32x32 pixel icon for the extension.

## Installation

1. Download or clone this repository to your local machine.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" using the toggle in the top right corner.
4. Click "Load unpacked" and select the directory where you downloaded or cloned the repository.

## Usage

- Once installed, the extension will run in the background.
- If the extension detects that you are not present in the scene or are engaged in another activity, it will automatically disable your media.
- You can access the extension’s settings and status from the popup interface.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [aisdaunting@gmail.com](mailto:aisdaunting@gmail.com).
