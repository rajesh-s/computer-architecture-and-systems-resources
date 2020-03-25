# Tools and Utilities

- [Tools](#tools)
  - [Open Source Tools for Digital Design](#open-source-tools-for-digital-design)
  - [Simulators](#simulators)
    - [Architectural](#architectural)
    - [Digital/Analog Simulators](#digitalanalog-simulators)
  - [Emulators](#emulators)
- [Utilities](#utilities)
  - [Hardware Design](#hardware-design)
- [Misc](#misc)

## Tools

### Open Source Tools for Digital Design

- [Verilator](https://www.veripool.org/projects/verilator/) - Verilator is the fastest free Verilog HDL simulator, and outperforms most commercial simulators
- [Icarus Verilog](https://github.com/steveicarus/iverilog) - Icarus Verilog is not aimed at being a simulator in the traditional sense, but a compiler that generates code employed by back-end tools.
- [SymbiFlow](https://symbiflow.github.io) - Open source FPGA tooling available under [YosysHQ](https://github.com/YosysHQ)
- [GTKWave](http://gtkwave.sourceforge.net/) - GTKWave is a fully featured GTK+ based wave viewer.
- [Wavedrom](https://wavedrom.com/) - WaveDrom draws your Timing Diagram or Waveform from simple textual description.
- [SymbiYosys](https://github.com/YosysHQ/SymbiYosys) - Front-end for Yosys-based formal verification flows
- [Upscale Project](http://upscale.stanford.edu/) - Formal tools for OSH
- [Yosys](http://www.clifford.at/yosys/) - Yosys is a framework for Verilog RTL synthesis.
- [Open Timer](https://github.com/OpenTimer/OpenTimer) - A High-Performance Timing Analysis Tool for VLSI Systems
- [Glade](https://peardrop.co.uk/) - Fast IC layout and schematic editor capable of reading and writing common EDA formats
- [OpenRAM](https://openram.soe.ucsc.edu) - An [open-source](https://github.com/VLSIDA/OpenRAM) static random access memory (SRAM) compiler.
- [Open Circuit Design Flow](http://opencircuitdesign.com/) - A suite of tools including Qflow covering various aspects of digital design
  - [Magic](http://opencircuitdesign.com/magic/index.html) - the VLSI layout editor, extraction, and DRC tool.
  - [XCircuit](http://opencircuitdesign.com/xcircuit/index.html) - the circuit drawing and schematic capture tool.
  - [IRSIM](http://opencircuitdesign.com/irsim/index.html) - the switch-level digital circuit simulator.
  - [Netgen](http://opencircuitdesign.com/netgen/index.html) - the circuit netlist comparison (LVS) and netlist conversion tool.
  - [Qrouter](http://opencircuitdesign.com/qrouter/index.html) - the over-the-cell (sea-of-gates) detail router.
  - [Qflow](http://opencircuitdesign.com/qflow/index.html) - a complete digital synthesis design flow using open-source software and open-source standard cell libraries.
  - [PCB](http://opencircuitdesign.com/pcb/index.html) - the printed circuit board layout editor.
- [ngspice](http://ngspice.sourceforge.net/) - open source spice simulator
- [The Open Road Project](https://github.com/The-OpenROAD-Project) - Includes [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA), [RePlAce](https://github.com/The-OpenROAD-Project/RePlAce), [OpenDB](https://github.com/The-OpenROAD-Project/OpenDB), [ioPlacer](https://github.com/The-OpenROAD-Project/ioPlacer), [FastRoute4](https://github.com/The-OpenROAD-Project/FastRoute4-lefdef) and other tools. [Start here](https://github.com/The-OpenROAD-Project/OPENROAD_USERS_READ_ME_FIRST)
- [Open Register Design](https://github.com/Juniper/open-register-design-tool) - Tool to generate register RTL, models, and docs using SystemRDL or JSpec input
- [LibrePCB](https://librepcb.org/) - A powerful, innovative and intuitive EDA tool for everyone!
- [ACT Tools Suite](http://avlsi.csl.yale.edu/act/doku.php) - Asynchronous Circuit Design Toolkit to support the design and implementation of asynchronous logic
- [PyMTL](https://github.com/cornell-brg/pymtl) - PyMTL is an open-source, Python-based framework for multi-level hardware modeling.
- [OpenFPGA](https://github.com/LNIS-Projects/OpenFPGA) - FPGA IP generator supporting highly-customizable homogeneous FPGA architectures
- [LibSystemCTLM](https://github.com/Xilinx/libsystemctlm-soc/blob/master/README.md) - This library contains various SystemC/TLM-2.0 modules that enable co-simulation of Xilinx QEMU, SystemC/TLM-2.0 models and RTL.
- [Fully autonomous SoC Synthesis](https://github.com/idea-fasoc/fasoc) - focused on developing a complete system-on-chip (SoC) synthesis tool from user specification to GDSII.
- [EDALIZE](https://github.com/olofk/edalize) - Edalize is a Python Library for interacting with EDA tools.
- [Open Source (FOSS) FPGA (EDA) Tooling Interchange Formats + Toolchain parts](https://j.mp/openfpga-diagram)
- [nMigen](https://github.com/m-labs/nmigen) - A refreshed Python toolbox for building complex digital hardware
- [Cascade](https://github.com/vmware/cascade) - Just-in-time compiler for Verilog
- [PyRTL](http://ucsbarchlab.github.io/PyRTL/) - A collection of classes for pythonic register-transfer level design, simulation, tracing, and testing suitable for teaching and research.
- [myHDL](http://www.myhdl.org/) - MyHDL turns Python into a hardware description and verification language
- [LLHD](http://www.llhd.io/) - is an intermediate representation for digital circuit descriptions, together with an accompanying simulator and SystemVerilog/VHDL compiler.
- [TerosHDL](https://github.com/TerosTechnology/terosHDL) - It is a  open source IDE to make FPGA development easier

### Simulators

#### Architectural

- [gem5](http://gem5.org/Main_Page) - The gem5 simulator is a modular platform for computer-system architecture research, encompassing system-level architecture as well as processor microarchitecture.
  - [Lapidary](https://github.com/efeslab/lapidary) - Tool to enable more efficient gem5 simulations
- [Venus](https://github.com/kvakil/venus) - Venus is a RISC-V instruction set simulator built for education.
- [FireSim](https://fires.im) - FireSim is an open-source cycle-accurate FPGA-accelerated full-system hardware simulation platform that runs on cloud FPGAs
- [CPULator](https://cpulator.01xz.net/) - CPUlator Computer System Simulator designed as a tool for learning assembly-language programming and computer organization
- [ESESC](https://github.com/masc-ucsc/esesc) - A fast multiprocessor simulator with detailed power, thermal, and performance models for modern out-of-order multicores.

#### Digital/Analog Simulators

- [DigitalJS](https://github.com/tilk/digitaljs) - Visualize and simulate digital logic using HDL
- [Digital](https://github.com/hneemann/Digital) - Digital is a easy-to-use digital logic designer and circuit simulator designed for educational purposes.
- [EDA Playground](https://www.edaplayground.com/) - Run HDL/HVL code in your browser
- [Electronic Circuit Simulator](https://www.falstad.com/circuit/) - Falstad circuit simulator
- [ASMBits](https://asmbits.01xz.net/wiki/Main_Page) - Assembly Practice
- [HDLBits](https://hdlbits.01xz.net/wiki/Main_Page) - Verilog Practice
- [8bit Workshop](http://8bitworkshop.com/redir.html?platform=verilog) - Verilog to waves instantly
- [Logic Design and Circuit Simulator](https://github.com/hneemann/Digital)
- [LogicEmu](https://lodev.org/logicemu/) - Logic simulator in your browser
- [Transistor level 6502 Hardware Simulation in Javascript](https://github.com/trebonian/visual6502) - [Visual6502](https://floooh.github.io/visual6502remix/)
- [Xyce](https://xyce.sandia.gov/) - open source, SPICE-compatible, high-performance analog circuit simulator, capable of solving extremely large circuit problems by supporting large-scale parallel computing platforms.
- [Micro Cap 12](http://www.spectrum-soft.com/download/download.shtm) - Micro-Cap 12 is an integrated schematic editor and mixed analog/digital simulator that provides an interactive sketch and simulate environment for electronics engineers. Now Open Source.
- [Logisim](http://www.cburch.com/logisim/) - Logisim is an educational tool for designing and simulating digital logic circuits.
- [LogisimITA](http://www.logisim.altervista.org/) - An independently developed fork of logisim that's preferred by many
- [Logisim-Evolution](https://github.com/reds-heig/logisim-evolution/) - Another flavour of Logisim after the development of original version was stopped

### Emulators

- [TinyEMU](https://bellard.org/tinyemu/) - TinyEMU is a system emulator for the RISC-V and x86 architectures.
- [Unicorn](https://www.unicorn-engine.org/) - Unicorn is a lightweight multi-platform, multi-architecture CPU emulator framework.
- [Emulator for Ben Eater's 8bit computer](https://fizzgig.itch.io/8-bit-breadboard-computer)
- [8bit Chip Emulator](https://github.com/floooh/chips) - A toolbox of 8-bit chip-emulators, helper code and complete embeddable system emulators

## Utilities

### Hardware Design

- [Data sheet scrubber](https://github.com/idea-fasoc/datasheet-scrubber) - The FASoC Datasheet Scrubber is a utility that scrubs through large sets of PDF datasheets/documents in order to extract key circuit information.
- [SystemVerilog Unit Test \(SVUT\)](https://github.com/damofthemoon/svut) - SVUT is a very simple flow to create a Verilog/SystemVerilog unit test.
- [AirHDL](https://airhdl.com) - Create register maps and headers
- [BitBench](http://triq.net/bitbench) - Visually dissect and analyze bit strings.
- [Bitfield](https://github.com/drom/bitfield) - BitField diagram Renderer
- [Diagrammer](https://github.com/freechipsproject/diagrammer) - Provides dot visualizations of chisel/firrtl circuites
- [VCD2Wavedrom](https://github.com/Toroid-io/vcd2wavedrom) - Handy for getting from simulation to spec quickly.
- [ipyxact](https://github.com/olofk/ipyxact) - Python-based IP-XACT parser
- [sv2v](https://github.com/zachjs/sv2v) - SystemVerilog to Verilog conversion
- [svlint](https://github.com/dalance/svlint) - System Verilog lint using rust
- [Wavedrom to Verilog](https://github.com/wavedrom/verilog)
- [HDL Checker](https://github.com/suoto/hdl_checker/blob/master/README.md) - HDL Checker is a language server that wraps VHDL/Verilg/SystemVerilog tools that aims to reduce the boilerplate code needed to set things up.
- [Wavedrom to ASCII converter](https://github.com/Wren6991/asciiwave) - README embeddable waveforms!
- [RgGen](https://github.com/rggen/rggen) - RgGen is a code generation tool for ASIC/IP/FPGA/RTL engineers. It will automatically generate soruce code related to configuration and status registers \(CSR\)
- [System RDL Compiler](https://github.com/SystemRDL/systemrdl-compiler) - The systemrdl-compiler module implements a generic compiler front-end for Accellera's SystemRDL 2.0 register description language.
- [Verismith](https://github.com/ymherklotz/verismith) - Verilog Fuzzer to test the major simulators and sythesisers by generating random, valid Verilog.
- [Jeff's ASIC tools](http://www.kwcpa.com/tools/) - Useful tools for working with HDL

## Misc

- [Online ARM Assember](https://azm.azerialabs.com/)