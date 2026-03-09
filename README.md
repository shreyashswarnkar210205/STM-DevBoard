STM-OWN Development Board
Custom STM-based development board designed and built using KiCad.
This project includes the complete schematic, PCB layout, 3D views, and fabrication files for the board.
The goal of this project was to design a custom microcontroller development board similar to Blue Pill–style boards, allowing easier integration into embedded projects.
Project Overview
This repository contains the full hardware design files for a custom STM microcontroller board.
The design includes:
Custom PCB designed in KiCad
Full schematic design
PCB layout and routing
3D visualization renders
Manufacturing ready layout files
The board can be used for:
Embedded system development
Microcontroller experimentation
Hardware prototyping
Learning PCB design workflows
Project Structure
STM-OWN
│
├── Main/                 # KiCad project files
│   ├── Main.kicad_pcb
│   ├── Main.kicad_sch
│   ├── Main.kicad_pro
│
├── SIGN.pretty/         # Custom footprint library
│
├── LAYOUT.png           # PCB layout preview
├── FRONT.png            # Front render
├── BACK.png             # Back render
├── ANGLE-1.png          # 3D view
├── ANGLE-2.png          # 3D view
│
├── Layout.pdf           # PCB layout export
├── Schematic.pdf        # Circuit schematic
├── Basic.pdf            # Additional documentation
│
└── README.md
PCB Design
The board was designed using KiCad and includes:
Fully routed PCB
Custom footprint library
Clean component placement
3D visualization for verification
Layout Preview
Front View
Back View
Design Files
Important files included in the repository:
File	Description
Main.kicad_sch	Complete schematic
Main.kicad_pcb	PCB layout
Main.kicad_pro	KiCad project configuration
SIGN.pretty	Custom footprint library
Layout.pdf	PCB layout export
Schematic.pdf	Circuit schematic
Requirements
To open and edit the project you need:
KiCad 7 or newer
Download:
https://kicad.org
How to Open the Project
Install KiCad
Clone the repository
git clone https://github.com/YOUR_USERNAME/STM-OWN.git
Open
Main/Main.kicad_pro
inside KiCad.
Features
Custom STM development board
Clean schematic design
Optimized PCB routing
Custom footprints
3D PCB visualization
Learning Goals
This project was created to practice:
PCB design workflow
KiCad project structuring
Footprint management
PCB routing and layout
Hardware documentation
License
This project is open-source and available for learning and experimentation.
