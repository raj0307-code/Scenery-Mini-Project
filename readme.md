# Three.js GLB Model Viewer

A feature-rich 3D model viewer built with Three.js that supports both orbit and FPV drone-style controls with dynamic sky lighting and environment settings.

## Features

- **Dual Control Systems**:
  - **Orbit Controls**: Traditional zoom, pan, and rotate around the model
  - **FPV Drone Controls**: Fly around the scene with WASD/arrow keys and mouse look
  
- **Dynamic Sky System**:
  - Realistic sky rendering with physically-based atmospheric scattering
  - Adjustable sun position, turbidity, and scattering parameters
  - Preset environments (Default, Sunset, Dawn, Night, Midday)
  
- **Advanced Rendering**:
  - PBR materials with HDR environment reflections
  - Realistic shadows with PCF soft shadow mapping
  - High-quality antialiasing for smooth edges
  
- **Performance Optimized**:
  - DRACO mesh compression support for faster loading
  - Adaptive renderer with pixel ratio limiting
  - Optimized material handling

- **User Interface**:
  - Comprehensive GUI controls for all settings
  - Responsive design that works on various screen sizes
  - Control overlay with keyboard shortcuts

## Technology Stack

- **Three.js**: Core 3D rendering engine
- **Blender 3D**: Used for model preparation and optimization
- **GLTFLoader**: For loading GLB/GLTF format models
- **DRACOLoader**: For decompressing compressed models
- **OrbitControls**: For standard 3D navigation
- **FlyControls**: For FPV drone-style navigation
- **RGBELoader**: For loading HDR environment maps
- **Sky**: For realistic sky rendering
- **lil-gui**: For user interface controls

## Model Information

The 3D model used in this viewer is sourced from TurboSquid and has been optimized using Blender 3D.

**Original Model**: [View on TurboSquid](https://www.turbosquid.com/3d-models/model-id-here)

**Model Download Link**: [Download Scene.glb from Google Drive](https://drive.google.com/file/d/1AbC123xYz/view?usp=sharing)

> **Note**: Due to file size limitations, the model cannot be hosted on GitHub. Please download the model from the Google Drive link above before running the application.

## Setup Instructions

1. Download the model file (`Scene.glb`) from the Google Drive link
2. Place the downloaded GLB file in the same directory as the HTML file
3. Open the HTML file in a web browser that supports WebGL

## Usage

- Use the GUI controls in the top-right corner to adjust settings
- Switch between Orbit and FPV controls using the dropdown
- When in FPV mode:
  - WASD / Arrow keys: Move forward/backward and strafe left/right
  - R/F: Move up/down
  - Q/E: Roll left/right
  - Mouse drag: Look around

## Browser Compatibility

This viewer works best in modern browsers with good WebGL support:
- Chrome (recommended)
- Firefox
- Edge
- Safari (WebGL 2.0 support required)

## License

This project is provided under the MIT License.

The 3D model is subject to the licensing terms provided by TurboSquid.

## Credits

- Three.js team for the incredible 3D library
- Example HDR environment map from Three.js examples
- Original 3D model from TurboSquid
