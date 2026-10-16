# 🌌 Solar System Simulation

A 3D Solar System simulation developed using **C++, OpenGL, GLU, and FreeGLUT** as an academic Computer Graphics project. The application visualizes planets orbiting the Sun, selected planetary moons, and a star-filled space environment with interactive controls and animated celestial bodies.

## 📌 Overview

The Solar System Simulation demonstrates fundamental computer graphics concepts through an interactive three-dimensional representation of our Solar System.

The application renders the Sun, eight planets, Pluto, selected moons, orbital paths, and a textured starfield. Users can control the simulation, change camera perspectives, zoom in and out, and toggle visual elements to explore the scene.

This project was developed during the second year of my B.E. Computer Engineering program to explore 3D graphics rendering, transformations, texture mapping, lighting, and animation.

## ✨ Features

- **3D Planet Visualization:** Render textured representations of the Sun, eight planets, and Pluto.
- **Planetary Animation:** Simulate orbital movement and planetary rotation.
- **Moon Simulation:** Visualize selected moons orbiting their respective planets.
- **Orbital Paths:** Toggle planetary orbital trails and moon orbit paths.
- **Interactive Camera:** Switch between three camera perspectives.
- **Zoom Controls:** Zoom in and out using the mouse scroll wheel.
- **Planet Labels:** Display or hide the names of celestial bodies.
- **Texture Mapping:** Apply bitmap textures to planets and the starfield.
- **Lighting Effects:** Use OpenGL lighting to enhance the appearance of 3D objects.
- **Interactive Controls:** Start, pause, and customize the visualization through keyboard and mouse input.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| C++ | Application logic and simulation |
| OpenGL | 3D rendering and graphics transformations |
| GLU | 3D sphere rendering and camera utilities |
| FreeGLUT | Window management, input handling, and animation callbacks |
| GLEW | OpenGL extension loading |
| BMP Textures | Planetary surfaces, starfield, and application logo |
| Visual Studio | Windows C++ development environment |

## 🎮 Controls

| Key / Input | Action |
|---|---|
| `Space` | Start or pause the animation |
| `O` | Show or hide planetary orbital trails |
| `o` | Show or hide moon orbital paths |
| `M` / `m` | Show or hide moons |
| `L` / `l` | Show or hide planet labels |
| `1` | Switch to the default camera view |
| `2` | Switch to the front-facing camera view |
| `3` | Switch to the alternate elevated camera view |
| Mouse scroll | Zoom in or out |
| Left-click | Enter the main simulation from the opening screen |
| Right-click | Exit the application |
| `Esc` | Exit the application |

## 🚀 Getting Started

### Prerequisites

- Windows operating system
- Microsoft Visual Studio with the C++ desktop development workload
- A graphics-compatible system supporting the required OpenGL functionality

The project includes dependencies for GLEW and FreeGLUT, along with the Visual Studio project configuration.

### Installation and Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/OmJangam1513/Solar-System-Simulation.git
   ```

2. Open `SolarSystem.vcxproj` in Microsoft Visual Studio.

3. Ensure the required GLEW and FreeGLUT libraries and DLLs are configured correctly for your build configuration and architecture.

4. Build the project using the appropriate Visual Studio configuration.

5. Run the generated executable with the required bitmap texture files available in the application's working directory.

6. Left-click the opening screen to enter the simulation, then use the keyboard and mouse controls to explore the Solar System.

## 📂 Project Structure

```text
Solar-System-Simulation/
├── main.cpp
├── imageloader.cpp
├── imageloader.h
├── SolarSystem.vcxproj
├── earth.bmp
├── jupiter.bmp
├── mars.bmp
├── mercury.bmp
├── neptune.bmp
├── pluto.bmp
├── saturn.bmp
├── sun.bmp
├── uranus.bmp
├── venus.bmp
├── stars.bmp
├── logo.bmp
└── README.md
```

*The structure above highlights the main source files, project configuration, and texture assets. The repository may contain additional dependency and build files.*

## 📚 Computer Graphics Concepts Demonstrated

- 3D modeling using geometric primitives
- Translation, rotation, and hierarchical transformations
- Perspective projection and camera positioning
- Texture mapping on spherical surfaces
- Lighting and shading
- Animation using timer callbacks
- Keyboard and mouse event handling
- Depth testing and double buffering

## 🎯 Learning Outcomes

- Applied fundamental computer graphics concepts in a practical application.
- Gained experience with C++ and OpenGL-based 3D rendering.
- Explored animation and transformations of multiple celestial objects.
- Implemented interactive camera movement and visualization controls.
- Understood the use of textures, lighting, and graphics libraries in a real-time simulation.

## 🔮 Future Improvements

- Add information panels containing planet facts and orbital characteristics.
- Implement selectable planets and camera tracking.
- Improve the orbital model with more realistic orbital parameters.
- Add adjustable animation speed and enhanced zoom controls.
- Introduce a more detailed interface for exploring individual celestial bodies.

## 👨‍💻 Author

**Om Jangam**

B.E. Computer Engineering | AI/ML Specialization

- GitHub: [@OmJangam1513](https://github.com/OmJangam1513)
- LinkedIn: [Connect with me](https://linkedin.com/in/om-jangam-75636735b)

---

*An academic project exploring interactive 3D visualization and fundamental Computer Graphics concepts.*
