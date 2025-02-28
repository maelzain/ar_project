# AR Project – Augmented Reality Animation for ML

This repository contains an augmented reality (AR) project that displays an animation over a marker using A-Frame and AR.js. The animation is built from a sequence of PNG images located in the `frames` folder. When the default Hiro marker is detected, the AR scene displays the animation by cycling through images (from `timestep_10.png` up to `timestep_960.png`) in numerical order.

## Features

- **Marker-Based AR:** Uses AR.js to detect the Hiro marker and trigger the AR animation.
- **Dynamic Animation:** The animation frames are generated dynamically in code to ensure the proper numerical order.
- **Preloading:** Each frame is preloaded to minimize flicker or black screens.
- **Mobile-Friendly:** Works in modern browsers on mobile devices with camera access.

## Repository Structure

