# Production Files

This directory contains manufacturing files generated from your KiCad project:

## Automatically Generated Files

The GitHub workflow automatically generates production files when you create a release:

- **Gerber Files**: PCB fabrication files (*.gbr)
- **Drill Files**: Drilling instructions (*.drl)
- **Pick and Place**: Component placement files (*.csv)
- **BOM**: Bill of Materials (*.csv)
- **PDF Documentation**: Schematic and PCB drawings

## Manual Generation

You can also generate files manually using KiCad or the workflows:

### Using KiCad GUI
1. Open your PCB file
2. File → Fabrication Outputs → Gerbers
3. File → Fabrication Outputs → Drill Files
4. File → Fabrication Outputs → Component Placement

### Using Workflows
Run the "Generate Production Files" workflow manually from the Actions tab.

## File Organization

```
production/
├── ProjectName_v1.0.0/
│   ├── gerbers/
│   ├── drill/
│   ├── assembly/
│   └── documentation/
└── ProjectName_production_files.zip
```

## Manufacturing Partners

Use these files with your chosen PCB manufacturer:
- Upload the complete zip file to most online services
- Verify layer stackup and design rules match your requirements
- Review manufacturing preview before ordering