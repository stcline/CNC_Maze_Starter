# CNC Maze Starter

Welcome to the **CNC Maze Starter** repository! This resource is designed for high school students enrolled in **PLTW (Project Lead The Way) Introduction to Engineering Design (IED)** who are beginning to explore Computer Numerical Control (CNC) machining.

## What Is This Repo?

This repository will provide starter CNC files (`.nc`) to help you get up and running with CNC programming quickly. Once the starter files are available, you can use them as a foundation, study the G-code, and modify them to create your own maze designs.

## What Is CNC?

CNC stands for **Computer Numerical Control**. CNC machines use pre-programmed computer software to control the movement of tools and machinery. In IED, you will use CNC concepts to design and manufacture parts with precision.

## Getting Started

1. **Download the starter `.nc` files** from this repository once they are available.
2. **Open the files** in your CNC software or a G-code viewer to visualize the toolpath.
3. **Modify the code** to customize your maze design — change dimensions, paths, and depths to make it your own.
4. **Simulate before cutting** — always run a simulation to check for errors before sending code to a machine.

## Key G-Code Concepts

| Command | Description |
|---------|-------------|
| `G00`   | Rapid positioning (move without cutting) |
| `G01`   | Linear interpolation (straight-line cut) |
| `G02`   | Clockwise circular arc |
| `G03`   | Counter-clockwise circular arc |
| `M03`   | Spindle on (clockwise) |
| `M05`   | Spindle stop |
| `M30`   | End of program |

## Tips for Success

- Always set your **Work Coordinate System (WCS)** before running a program.
- Double-check your **feed rates** and **spindle speeds** for the material you are cutting.
- Use a **G-code simulator** (such as [NC Viewer](https://ncviewer.com/)) to preview your toolpath before machining.
- Ask your instructor before making any changes to a machine.

## Resources

- [PLTW IED Course Information](https://www.pltw.org/our-programs/pltw-engineering/pltw-engineering-curriculum#ied)
- [NC Viewer — Free Online G-Code Viewer](https://ncviewer.com/)
- [Autodesk Fusion 360 CAM Basics](https://www.autodesk.com/products/fusion-360/blog/cnc-programming-basics/)

---

*Happy machining! 🛠️*