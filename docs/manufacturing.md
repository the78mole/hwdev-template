# Manufacturing Guide

This guide covers the manufacturing process for PCBs and assembly procedures.

## PCB Fabrication

### Fabrication Specifications

#### Standard Specifications
- **Layer Count**: 2-layer, 4-layer (specify in design)
- **Board Thickness**: 1.6mm standard, other thicknesses available
- **Copper Weight**: 1 oz (35μm) standard, 2 oz for high current
- **Surface Finish**: HASL, ENIG, OSP (specify requirements)
- **Solder Mask Color**: Green standard, other colors available
- **Silkscreen Color**: White standard

#### Design Rules
- **Minimum Trace Width**: 0.1mm (4 mil)
- **Minimum Spacing**: 0.1mm (4 mil)
- **Minimum Via Drill**: 0.2mm (8 mil)
- **Minimum Annular Ring**: 0.05mm (2 mil)

### Fabrication Files

#### Gerber Files
- Copper layers (*.gbr)
- Solder mask layers (*.gbs, *.gts)
- Silkscreen layers (*.gbo, *.gto)
- Board outline (*.gm1 or Edge.Cuts)

#### Drill Files
- Excellon drill files (*.drl)
- Tool list and sizes
- Plated vs. non-plated holes

#### Additional Files
- Pick and place files (*.csv)
- Bill of Materials (*.csv)
- Assembly drawings (*.pdf)
- Fabrication drawings (*.pdf)

### Recommended Fabricators

#### Prototype Quantities (1-10 boards)
- **JLCPCB**: Low cost, good quality, fast turnaround
- **PCBWay**: Good service, variety of options
- **OSH Park**: High quality, USA-based

#### Production Quantities (100+ boards)
- **Advanced Circuits**: USA-based, high reliability
- **Sunstone Circuits**: Quick turnaround, good service
- **Sierra Circuits**: High-end applications

## PCB Assembly

### Assembly Process

#### Surface Mount Technology (SMT)
1. **Solder Paste Application**: Stencil printing
2. **Component Placement**: Pick and place machine
3. **Reflow Soldering**: Controlled temperature profile
4. **Inspection**: AOI (Automated Optical Inspection)

#### Through-Hole Assembly
1. **Component Insertion**: Manual or automatic
2. **Wave Soldering**: For through-hole components
3. **Manual Touch-up**: As needed
4. **Final Inspection**: Visual and electrical testing

### Assembly Files Required

#### For SMT Assembly
- Pick and place file (centroid data)
- Bill of Materials with manufacturer part numbers
- Assembly drawings with component orientations
- Paste stencil gerber file

#### Component Procurement
- Approved vendor list
- Alternative part numbers
- Component packaging requirements (cut tape, reel)

### Assembly Considerations

#### Design for Assembly (DFA)
- **Component Orientation**: Consistent orientation when possible
- **Component Spacing**: Adequate spacing for assembly tools
- **Test Points**: Accessible for testing and debugging
- **Fiducial Markers**: For automated assembly alignment

#### Mixed Assembly
- SMT components first, then through-hole
- Consider component height restrictions
- Plan for selective soldering if needed

## Quality Control

### Inspection Procedures

#### Incoming Inspection
- PCB dimensional verification
- Visual inspection for defects
- Electrical continuity testing

#### In-Process Inspection
- Solder paste inspection (SPI)
- Post-placement inspection
- Post-reflow inspection

#### Final Inspection
- Functional testing
- Electrical performance verification
- Cosmetic inspection

### Testing Requirements

#### Electrical Testing
- In-circuit testing (ICT)
- Functional testing
- Boundary scan testing (if applicable)

#### Environmental Testing
- Temperature cycling
- Humidity testing
- Vibration testing (if applicable)

## Cost Optimization

### Design Considerations
- **Panelization**: Multiple boards per panel
- **Standard Processes**: Use standard fabrication processes
- **Component Selection**: Standard package sizes and values
- **Assembly Optimization**: Minimize manual operations

### Volume Considerations
- **Prototype**: Small quantities, quick turnaround
- **Pilot Production**: Medium quantities, validate process
- **Production**: Large quantities, optimize for cost

## Supply Chain Management

### Lead Times
- **PCB Fabrication**: 5-15 days typical
- **Component Procurement**: 2-52 weeks depending on availability
- **Assembly**: 3-10 days after components received

### Risk Management
- **Component Allocation**: Secure long-lead components early
- **Alternative Sources**: Maintain approved alternatives
- **Inventory Planning**: Balance cost vs. availability

## Documentation

### Manufacturing Package
- Complete Gerber file set
- Bill of Materials with specifications
- Assembly instructions
- Test procedures
- Quality requirements

### Revision Control
- Version control for all manufacturing files
- Change notification procedures
- Approval process for changes

## Environmental Compliance

### RoHS Compliance
- Lead-free soldering processes
- Material compliance documentation
- Supply chain verification

### REACH Compliance
- Substance of Very High Concern (SVHC) tracking
- Material declarations from suppliers

## References

- [IPC Standards](https://www.ipc.org/)
- [JEDEC Standards](https://www.jedec.org/)
- [Manufacturing Guidelines](https://www.circuitinsight.com/)