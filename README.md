# Black Hole

A real-time WebGL-based black hole simulation that showcases gravitational lensing, an accretion disk, and background stars using ray tracing techniques. This project uses fragment shaders to simulate how light behaves around a black hole based on general relativity.

Features

- Realistic Gravitational Lensing – Light bends around the black hole according to the Schwarzschild metric.
- Accretion Disk Simulation – A glowing, spinning disk affected by Doppler shift and gravitational redshift.
- Dynamic Star Field – A procedural star background that distorts under extreme gravity.
- Interactive Controls – Adjust black hole mass, disk brightness, and other parameters in real-time.
- WebGL & GLSL Shaders – Runs entirely in the browser using GPU acceleration.

How It Works

Uses WebGL2 to render the scene with ray tracing in the fragment shader.

Each pixel represents a light ray affected by the black hole's gravity.

The accretion disk is colored based on relativistic Doppler effects and redshift.

Background stars distort dynamically based on gravitational lensing.

UI controls allow real-time interaction with the scene.


Getting Started

1. Clone the repository:

```git clone https://github.com/bzk9x/blackhole.git```


2. Open .html file in a modern web browser.



Demo

Live Demo (if hosted) 
