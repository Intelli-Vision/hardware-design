# Intellivision Electronics

This repository contains the KiCad files for the Intellivision smart glasses project. These files are used for designing the printed circuit boards (PCBs) and include schematic diagrams, PCB layouts, and related design files.

## Contents

- **`schematics/`**: Contains the schematic diagrams for the project. These are the electrical diagrams showing the connections and components used in the design.
- **`pcb/`**: Contains the PCB layout files. These files define the physical layout of the circuit board, including the placement of components and routing of traces.
- **`footprints/`**: Includes footprint files for various components used in the design. Footprints represent the physical layout of components on the PCB.
- **`symbols/`**: Contains symbol files for the components used in the schematics. Symbols represent the electrical functionality of components.
- **`3dmodels/`**: Contains 3D models of components, if applicable. These models are used for visualizing the assembled PCB in 3D.

## Getting Started

To work with these files, you need to have KiCad installed on your computer. You can download KiCad from [KiCad’s official website](https://www.kicad.org/download/).

### Opening Files

1. **Open KiCad**: Launch KiCad from your applications menu.
2. **Open Project**: Select `File > Open Project` and navigate to the `.pro` file in the root of this folder to load the entire project.
3. **View Schematics**: Use the KiCad schematic editor to view and modify schematic files.
4. **View PCB Layout**: Use the KiCad PCB editor to view and modify PCB layout files.

### Modifying Schematics and PCB

- **Schematic Changes**: Edit the schematic files using the schematic editor to add or modify components and connections.
- **PCB Layout Changes**: Edit the PCB layout files using the PCB editor to adjust component placement, routing, and other layout details.
- **Footprint and Symbol Updates**: Update footprints and symbols as needed to match the components used in your design.

### Generating Gerber Files

1. **Open PCB Layout**: Open the PCB layout file in KiCad.
2. **Generate Gerber Files**: Use the `File > Plot` option to generate Gerber files needed for manufacturing the PCB.

### 3D Visualization

To view a 3D model of the PCB:
1. **Open PCB Layout**: Open the PCB layout file.
2. **3D Viewer**: Click on the `View > 3D Viewer` option to see a 3D rendering of the PCB.

## Contributing

If you would like to contribute to the design:
1. Fork the repository.
2. Make your changes in a separate branch.
3. Submit a pull request with a description of your changes.

## Contact

For any questions or issues, please contact [Noah Moore](mailto:intellivision@noahkmoore.com) or open an issue in the repository
