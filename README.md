# Power Board 6 - Multi-Rail DC-DC Converter Board

A flexible power distribution board featuring three cascading buck converter stages for rapid prototyping and R&D testing.

## Overview

While working at Sable Systems International, I needed a way to quickly access multiple voltage rails during R&D testing without constantly rewiring power supplies. This board was developed to solve that problem by providing regulated outputs at different voltage levels from a single input source.

## Features

- **Primary Stage**: 24VDC → 12VDC buck converter
- **Secondary Stage**: 12VDC → 5VDC buck converter  
- **Tertiary Stage**: 5VDC → 3.3VDC buck converter
- High-efficiency power delivery optimized for multiple simultaneous loads
- Integrated protection and filtering on each rail

## Design

The board is designed in KiCAD and includes:
- Full schematic and PCB layout
- Custom component footprints and symbol libraries
- Thermal and power analysis documentation
- 3D model for visualization and assembly planning

## Files

- `Power_Board_6.kicad_sch` - Complete schematic
- `Power_Board_6.kicad_pcb` - PCB layout and routing
- `Power_Board_6.kicad_pro` - Project configuration and design rules
- `3D_Model.glb` - 3D visualization
- `Reports/` - Power analysis and design documentation

## Getting Started

To work with this design:
1. Install [KiCAD 10.0](https://www.kicad.org/download/) or compatible version
2. Open `Power_Board_6.kicad_pro` to view the complete project
3. Review power analysis reports in the `Reports/` directory before modifying converter stages

## Use Cases

- Rapid prototyping with devices requiring multiple voltage rails
- R&D testing platforms needing flexible power distribution
- Educational demonstrations of buck converter design
- Reference design for multi-stage power delivery systems

---

*Developed for efficient power distribution during research and development work.*
