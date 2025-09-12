# Hardware Project Files

This directory contains your KiCad project files:

- `*.kicad_pro` - KiCad project file
- `*.kicad_sch` - Schematic files
- `*.kicad_pcb` - PCB layout files
- `libraries/` - Custom component libraries

## Getting Started

1. Create a new KiCad project in this directory
2. Use the project name that matches your repository name
3. Set up your design rules and constraints
4. Begin your schematic design

## Library Management

Store custom libraries in the `libraries/` subdirectory:
- Symbol libraries (*.kicad_sym)
- Footprint libraries (*.pretty)
- 3D model files (*.step, *.wrl)

## Version Control

KiCad files are version controlled. The .gitignore is configured to:
- Track main project files
- Ignore temporary and backup files
- Ignore user-specific settings (*.kicad_prl)

Commit often and use meaningful commit messages describing your design changes.