# Procedural Blob Renderer (TouchDesigner)

A real-time procedural blob rendering system built in TouchDesigner using noise-driven deformation, displacement mapping, and chromatic edge processing.

This project explores organic motion, generative shape formation, and real-time post-processing workflows inside a node-based GPU pipeline.

---

## Overview

This system generates animated blob-like forms using layered noise fields to drive deformation and displacement. The resulting shapes are stylized with edge detection, RGB channel separation, and glow-based post-processing to create a dynamic, high-contrast visual aesthetic.

The project serves as:

- A generative visual study  
- A foundation for audio-reactive performance work  
- A modular base for installation or projection mapping  

---

## Features

- Multi-layer procedural noise deformation
- Real-time animation via time-based Z-offset
- Chromatic aberration edge stylization
- Modular TOP/CHOP-based architecture
- Designed for live performance extension

---

## Technical Breakdown

### Shape Generation
Noise TOPs are layered and combined to create organic displacement maps that drive blob form evolution.

### Deformation
Position and Transform operators manipulate geometry in real time using procedurally generated texture data.

### Post-Processing
Edge detection and RGB channel offsets create stylized outlines and glow effects.

### Optional Audio Reactivity
The system can be extended with:
- `Audio Device In CHOP`
- `Analyze CHOP` (RMS / Peak detection)
- `Lag CHOP` for stable modulation smoothing

Parameters such as deformation amplitude, blur radius, or scale can be mapped to live audio input.

---

## Requirements

- TouchDesigner 2023+ (tested in 2025 build)
- GPU capable of real-time TOP processing

---

## How to Use

1. Open the `.toe` file.
2. Navigate to `/project1`.
3. Adjust:
   - Noise frequency and amplitude
   - Edge threshold
   - Blur amount
4. (Optional) Connect audio input and export CHOP channels to modulation parameters.

---

## Future Directions

- Integrated audio-reactive performance mode
- Depth layering and parallax systems
- Feedback loop experimentation
- Projection-ready output mapping
- Parameter UI for live control

---

## Author

Built as part of an ongoing exploration into generative systems, audiovisual performance, and real-time graphics workflows.
