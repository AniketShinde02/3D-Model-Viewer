# 3D Plane Model Viewer

A responsive and interactive 3D model viewer built with Three.js. This project loads an OBJ file (named `frogface.obj`) and displays it with smooth orbit controls, lighting, and view switching options.

## Features

- **3D Model Display**: Loads and renders a 3D model (OBJ format) using Three.js.
- **OrbitControls Integration**: Allows users to click/tap and drag to rotate, zoom, and inspect the model interactively (optimized for both desktop and mobile).
- **View Switching Buttons**: Includes buttons for switching camera views:
  - **Front View**
  - **Top View**
  - **Side View**
- **Responsive Design**: Adjusts layout and canvas size to fit various screen sizes (from smartphones like the Pixel 7 to larger screens).
- **Loader Animation**: Displays a spinning loader while the 3D model is being loaded.
- **Modern Aesthetics**: Uses a gradient background, semi-transparent container, and styled buttons for an exhibition-level look.

## Technologies Used

- **[Three.js](https://threejs.org/)** (version r152) – Core library for rendering the 3D scene.
- **OBJLoader** – Loads 3D models in OBJ format.
- **OrbitControls** – Provides intuitive drag and zoom controls for navigating the 3D scene.
- **HTML5, CSS3, and JavaScript** – For building the UI and interactive functionality.

## Getting Started

### Prerequisites

- Ensure that you have your `frogface.obj` file in the same directory as the `index.html`.
- For local testing, it is recommended to run the project via a local server (to avoid CORS issues with file loading).

### Running the Project Locally

1. **Using Node.js and http-server**:
   ```bash
   cd path/to/your/project
   npx http-server .
