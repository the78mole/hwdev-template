# Component Selection Guide

This guide helps with component selection and standardization for hardware projects.

## Standard Components Library

### Resistors
- **Standard Values**: E24 series (1%, 5% tolerance)
- **Package Sizes**: 0603, 0805 (prefer 0603 for space efficiency)
- **Power Ratings**: 1/10W (0603), 1/8W (0805)
- **Suppliers**: Yageo, Vishay, KOA

### Capacitors

#### Ceramic Capacitors (MLCC)
- **Package Sizes**: 0603, 0805
- **Voltage Ratings**: 6.3V, 10V, 16V, 25V, 50V
- **Dielectric Types**: 
  - X7R (general purpose, -55°C to +125°C)
  - C0G/NP0 (precision, stable)
- **Suppliers**: Murata, Samsung, TDK

#### Electrolytic Capacitors
- **Types**: Aluminum electrolytic, Tantalum
- **Voltage Ratings**: Derate to 50% of maximum rating
- **Temperature Considerations**: Choose appropriate temperature rating
- **Suppliers**: Nichicon, Panasonic, AVX

### Inductors
- **Types**: Ferrite core, powdered iron
- **Package Sizes**: 0603, 0805, 1206
- **Current Ratings**: Match to application requirements
- **Suppliers**: Murata, TDK, Coilcraft

### Semiconductors

#### Discrete Components
- **Diodes**: Schottky, standard rectifier, zener
- **Transistors**: MOSFET, BJT in SOT-23, SOT-223 packages
- **Protection**: TVS diodes, ESD protection

#### Integrated Circuits
- **Microcontrollers**: ARM Cortex-M, ESP32, STM32
- **Analog ICs**: Op-amps, voltage regulators, ADCs
- **Interface ICs**: Level shifters, drivers, transceivers

### Connectors
- **Board-to-Board**: Standard pitch connectors
- **Wire-to-Board**: Terminal blocks, headers
- **RF Connectors**: SMA, U.FL for high-frequency applications
- **USB**: USB-C preferred for new designs

## Component Lifecycle Management

### Obsolescence Planning
- Monitor component lifecycle status
- Identify potential obsolescence risks
- Plan for component replacements

### Alternative Sourcing
- Maintain list of approved alternates
- Validate electrical and mechanical compatibility
- Consider supply chain reliability

### Cost Optimization
- Target cost objectives for BOM
- Consider volume pricing breaks
- Balance cost vs. performance requirements

## Quality and Reliability

### Component Qualification
- Define qualification requirements
- Consider automotive/industrial grades for harsh environments
- Verify component specifications match requirements

### Testing Requirements
- Incoming inspection procedures
- Qualification testing protocols
- Reliability testing standards

## Procurement Guidelines

### Approved Vendor List
- Maintain list of approved suppliers
- Include distributor information
- Consider regional availability

### Inventory Management
- Standard inventory levels
- Lead time considerations
- Minimum order quantities

## Design for Manufacturing

### Assembly Considerations
- Component orientation standards
- Package size limitations
- Mixed assembly processes (SMT + through-hole)

### Testing Access
- Provide test points for critical signals
- Consider in-circuit test requirements
- Plan for functional testing

## Environmental Considerations

### RoHS Compliance
- Use lead-free components
- Verify material compliance
- Maintain compliance documentation

### Operating Environment
- Temperature range requirements
- Humidity and contamination resistance
- Mechanical shock and vibration

## Documentation Requirements

### Component Database
- Maintain component database with specifications
- Include footprint and symbol library references
- Document approved alternatives

### Change Control
- Track component changes and revisions
- Maintain approval records
- Document impact assessments

## References

- [Component Selection Guides](https://www.electronics-tutorials.ws/)
- [Supplier Websites](https://www.digikey.com/)
- [Industry Standards](https://www.jedec.org/)