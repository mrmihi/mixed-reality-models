# Mixed Reality Models

A web-based Augmented Reality (AR) project that brings 3D models to life using marker-based AR technology. The project is accessible at [https://mrmihi.github.io/mixed-reality-models/](https://mrmihi.github.io/mixed-reality-models/).

## Features

- Marker-based AR experience using the Hiro marker
- Interactive 3D model visualization
- Synchronized audio playback with marker detection
- Responsive design for various devices
- Support for GLTF and OBJ model formats

## Technologies Used

- [A-Frame](https://aframe.io/) (v0.7.1) - Web framework for building VR experiences
- [AR.js](https://github.com/jeromeetienne/AR.js) - JavaScript library for adding augmented reality experiences to web apps
- [A-Frame Extras](https://github.com/n5ro/aframe-extras) - Additional components for A-Frame

## Project Structure

```
mixed-reality-models/
├── assets/           # 3D models and audio files
├── markers/         # AR marker definitions
├── index.html       # Main application file
└── package.json     # Project dependencies
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/mrmihi/mixed-reality-models.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the local development server:
   ```bash
   npx local-web-server
   ```

4. Open your browser and navigate to `http://localhost:8000`

## Usage

1. Print or display the Hiro marker (you can find it in the `markers` directory)
2. Open the application in a web browser on your mobile device
3. Point your camera at the Hiro marker
4. The 3D model will appear and audio will start playing automatically

## Requirements

- A modern web browser with WebXR support
- A device with a camera (mobile device recommended)
- The Hiro marker for AR tracking

## Acknowledgments

- A-Frame team for the amazing VR/AR framework
- Jerome Etienne for AR.js
- All contributors and users of this project 