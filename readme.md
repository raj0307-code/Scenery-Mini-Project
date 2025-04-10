# Scenery-Mini-Project

This Three.js viewer showcases a low-poly 3D scenery with intuitive camera controls. Users can explore the minimalist environment through either orbit navigation or immersive FPV drone-style movement while experiencing dynamic lighting conditions. The project demonstrates how even simplified 3D models can create compelling visual experiences when combined with advanced rendering techniques.

![Scenery mini-project img](https://github.com/user-attachments/assets/36f665b3-6b67-43c3-8c32-37fe2ad5f539)

## Features

- **Dual Control Systems**:
  - **Orbit Controls**: Traditional zoom, pan, and rotate around the model
  - **FPV Drone Controls**: Fly around the scene with WASD/arrow keys and mouse look
  
- **Dynamic Sky System**:
  - Realistic sky rendering with physically-based atmospheric scattering
  - Adjustable sun position, turbidity, and scattering parameters
  - Preset environments (Default, Sunset, Dawn, Night, Midday)
  
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
- **RGBELoader**: For loading HDR environment maps
- **lil-gui**: For user interface controls

## Model Information

The 3D model used in this viewer is sourced from TurboSquid and has been optimized using Blender 3D.

**Original Model**: [View on TurboSquid](https://www.turbosquid.com/3d-models/3d-medieval-stronghold-and-village-model-2250878)

**Model Download Link**: [Download Scene.glb from Google Drive](https://drive.google.com/file/d/1fb16rIeUBkwViebeKwLjbg0sHjp9e8fa/view?usp=sharing)

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
