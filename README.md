⚡ STM Custom Development Board
A custom STM-based development board designed using KiCad, inspired by Blue Pill–style boards for embedded development and rapid prototyping.
This project demonstrates a complete PCB design workflow including schematic capture, footprint creation, PCB layout, 3D visualization, and manufacturing file generation.
🧠 Overview
This board integrates:
STM microcontroller core
USB programming interface
3.3V voltage regulation
Boot and reset circuitry
Status LEDs
GPIO breakout headers
Programming/debug interface
External crystal oscillator
Power filtering and decoupling network
The goal of this design is to create a compact and reusable development board for embedded system experimentation.
🛠 PCB Design
The board was designed using KiCad and includes:
Complete schematic design
Fully routed PCB layout
Custom symbol and footprint libraries
3D board visualization
Manufacturing-ready design files
📂 Repository Structure
STM-OWN
│
├── Main/
│   ├── Main.kicad_pcb
│   ├── Main.kicad_sch
│   ├── Main.kicad_pro
│
├── SIGN.pretty/          # Custom footprint library
│
├── LAYOUT.png            # PCB layout preview
├── FRONT.png             # Front render
├── BACK.png              # Back render
├── ANGLE-1.png           # 3D view
├── ANGLE-2.png           # 3D view
│
├── Layout.pdf            # PCB layout export
├── Schematic.pdf         # Circuit schematic
├── Basic.pdf             # Additional documentation
│
└── README.md
🔧 Hardware Features
STM microcontroller based design
USB interface for programming and power
3.3V regulated power supply
Boot and reset buttons
GPIO header breakout
Status indicator LEDs
External crystal oscillator
Decoupling and filtering network
🧩 Design Workflow
This project demonstrates:
Schematic design in KiCad
Custom symbol creation
Custom footprint creation
PCB layout and routing
3D PCB validation
Design rule checks (DRC)
Manufacturing export files
🖥 Requirements
To open the project you need:
KiCad 7 or newer
Download:
https://kicad.org
🚀 Getting Started
Clone the repository:
git clone https://github.com/shreyashswarnkar210205/STM-OWN.git
Open the project in KiCad:
Main/Main.kicad_pro
📘 Learning Goals
This project was built to practice:
PCB design workflow
KiCad project management
Embedded hardware design
Component placement strategies
PCB routing techniques
📜 License
This project is open-source and intended for learning and experimentation.