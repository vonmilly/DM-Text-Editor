# Text Editor Web Application
[![License: MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/license/mit/)
## Overview

This text editor web application is a powerful tool for writing and editing text, built with modern web technologies. It features a client-server architecture, with a backend serving the client application. The frontend is bundled using webpack, allowing for efficient management of JavaScript files. The application leverages IndexedDB for local storage, enabling seamless saving and retrieval of content. Additionally, it is equipped with service worker functionality, providing offline capabilities and enabling installation as a progressive web app (PWA).

## Folder Structure

The application follows a client-server folder structure:

text-editor/
│
├── client/ # Client-side code
│ ├── public/ # Public assets
│ └── src/ # Source code
│ ├── components/ # React components
│ ├── styles/ # CSS stylesheets
│ └── index.js # Main JavaScript file
│
└── server/ # Server-side code
├── routes/ # API routes
└── server.js # Express server setup

## Installation and Usage

To run the text editor web application, follow these steps:

1. Clone the repository

2. Navigate to the project directory:
cd text-editor

3. Install dependencies:
npm install

4. Start the server:
npm run start

5. Open your browser and navigate to `http://localhost:3000/`.

## Features

- **Backend-Server Architecture**: The application serves the client from a backend server.
- **Webpack Bundling**: JavaScript files are bundled using webpack for optimized performance.
- **IndexedDB Storage**: Content in the text editor is saved and retrieved using IndexedDB, ensuring persistence across sessions.
- **Progressive Web App (PWA)**: The application can be installed as a PWA, enabling offline access and desktop icon installation.
- **Service Worker**: A service worker is registered to pre-cache static assets, enabling faster loading and offline access.

## Deployment

The application is deployable to Render. Ensure proper build scripts are set up for webpack applications.

## Next-Gen JavaScript

The application supports next-gen JavaScript features, ensuring compatibility with modern browsers without errors.

## Author

This project was authored by Devonte Miller.