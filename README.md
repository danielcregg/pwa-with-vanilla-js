# PWA with Vanilla JS

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

> **Note:** This repository is a fork of [ibrahima92/pwa-with-vanilla-js](https://github.com/ibrahima92/pwa-with-vanilla-js).

A coffee-themed Progressive Web App built entirely with vanilla JavaScript, HTML, and CSS. Demonstrates how to build a fully installable, offline-capable PWA without any frameworks or build tools.

## Overview

Dev'Coffee is a sample PWA that displays a grid of coffee cards rendered dynamically from JavaScript. It features a complete service worker implementation with asset caching for offline use, a web app manifest with multiple icon sizes for cross-platform installability, and iOS-specific meta tags for Apple device support. The project also includes Android asset links for Trusted Web Activity (TWA) integration and GitHub Pages deployment via Jekyll configuration.

## Features

- Fully offline-capable with service worker caching of all assets
- Responsive card-based grid layout using CSS Grid with auto-fit columns
- Dynamic content rendering from a JavaScript data array
- Installable on Android, iOS, and desktop platforms
- Multiple icon sizes (72x72 through 512x512) for all device resolutions
- Apple touch icon support for iOS home screen integration
- Android Trusted Web Activity (TWA) asset links configuration
- GitHub Pages ready with Jekyll `_config.yml`

## Prerequisites

- A modern web browser (Chrome, Edge, Firefox, or Safari)
- A local web server for development (e.g., `python -m http.server` or VS Code Live Server)
- HTTPS for service worker registration in production

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/pwa-with-vanilla-js.git
   cd pwa-with-vanilla-js
   ```

2. Serve the files using any static web server:
   ```bash
   python3 -m http.server 8000
   ```

### Usage

1. Open `http://localhost:8000` in your browser.
2. Browse the coffee card gallery with images and tasting links.
3. To install as a standalone app, click the install prompt in the browser address bar.
4. Once installed, the app works fully offline with all images and styles cached.

## Tech Stack

- **HTML5** -- Semantic markup with iOS and PWA meta tags
- **CSS3** -- Responsive grid layout, card components, and Nunito font
- **JavaScript** -- Dynamic DOM rendering, service worker registration, and event handling
- **Service Worker** -- Cache-first strategy for all static assets and images
- **Web App Manifest** -- Full icon set and standalone display configuration
- **Jekyll** -- GitHub Pages deployment configuration

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
