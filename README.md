# 💍 ringOdate3D - 3D Calendar Ring Project

Welcome to the **ringOdate3D** repository! This project contains the 3D CAD models for a customizable, date-themed mechanical ring. The design features a base ring integrated with a calendar mechanism and interchangeable numbers, allowing the wearer to display a specific date or track time.

## 📂 Project Overview
This repository hosts the geometric components required to manufacture or 3D print a multi-part "date ring". The design separates the ring band, the calendar face, and the individual numbers into distinct files, making it ideal for multi-color 3D printing (using systems like Bambu Lab AMS or Prusa MMU) or CNC machining.

## 🗂️ Repository Contents
The models are provided in a mix of native Rhinoceros 3D files and DXF (Drawing Exchange Format) files. DXF is excellent for maintaining precise vector curves when moving between CAD, CAM, and slicing software.

### Native Rhino File
*   **`Calendar.3dm`**: The master Rhinoceros 3D assembly file. This contains the complete 3D geometry, layers, and spatial relationships of the entire ring mechanism.

### Component DXF Files (`.dxf`)
DXF files are included for the individual parts, making it easy to import specific components into other CAD software or slicing tools.
*   **`Ring.dxf`**: The base geometry of the ring band.
*   **`Calendar (Green).dxf`**: The calendar face/plate component (named "Green" to indicate the intended filament color for multi-color printing).
*   **`Numbers (white).dxf`**: The individual numerical digits used for the date display (named "White" for multi-color printing contrast).
*   **`Rounder (3 pieces).dxf`**: A specialized 3-piece component, likely used as an assembly jig, a rounding tool, or a specific mechanical joint for the ring.

## 🛠️ Tools & Technologies
*   **Software:** [Rhinoceros 3D (Rhino)](https://www.rhino3d.com/) - Used for designing the precise NURBS curves and mechanical clearances required for a wearable, moving ring.
*   **File Formats:** `.3dm` (Rhino's native format) and `.dxf` (AutoCAD Drawing Exchange Format, widely used for 2D/3D vector data exchange).

## 🖨️ Manufacturing & 3D Printing
Because this design is separated into distinct files with color hints (Green, White), it is perfectly set up for **Multi-Material 3D Printing**:
1.  **Slicing:** Import the `.dxf` or `.3dm` files into your slicer (e.g., Bambu Studio, PrusaSlicer, Cura).
2.  **Multi-Color:** Assign the `Ring` to a base color (e.g., black or silver), the `Calendar` to green, and the `Numbers` to white. 
3.  **Assembly:** If printing in separate parts, use the `Rounder (3 pieces)` as a guide for assembly or post-processing.

## 👤 Author
*   **Anastasia Repina** 
*   Check out my other 3D CAD projects and my CV at [arepina.github.io](https://arepina.github.io/)

---
*Feel free to explore the files, modify the dates, or use this as a reference for your own parametric jewelry designs!*
