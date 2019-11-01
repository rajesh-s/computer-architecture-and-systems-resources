# awesome-computer-architecture [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated compendium of awesome Computer Architecture resources

<p align="center">
  <img src="https://d1rkab7tlqy5f1.cloudfront.net/TUDelft/Onderwijs/Opleidingen/Master/MSc_Computer_Engineering/PastedGraphic-2.jpg">
</p>

Table of Contents
=================

- [Table of Contents](#table-of-contents)
  - [Conferences](#conferences)
    - [Open Source centric](#open-source-centric)
    - [Interconnects](#interconnects)
    - [High Performance Computing](#high-performance-computing)
  - [MOOCs](#moocs)
  - [Blogs/ Books](#blogs-books)
  - [Tools and Utilities](#tools-and-utilities)
    - [Open Source Tools for Digital Design](#open-source-tools-for-digital-design)
    - [Simulators](#simulators)
    - [Emulators](#emulators)
  - [Communities](#communities)
  - [Interesting Resources](#interesting-resources)
  - [Digging Deeper](#digging-deeper)
  - [Other specific curated lists related to CompArch](#other-specific-curated-lists-related-to-comparch)

## Conferences

- [ISCA](https://iscaconf.org/) - International Symposium on Computer Architecture
- [ASPLOS](https://asplos-conference.org/) - ASPLOS is the premier forum for interdisciplinary systems research, intersecting computer architecture, hardware and emerging technologies, programming languages and compilers, operating systems, and networking.
- [MICRO](https://www.microarch.org/) - IEEE International Symposium on Microarchitecture
- [ISCAS](https://iscas2020.org/) - IEEE International Symposium on Circuits and Systems
- [ICONS](https://ornlcda.github.io/icons2019/) - Conference on Neuromorphic Computing
- [USENIX](https://www.usenix.org/conferences) - Systems Researchers

- Search tools for conferences:
  - [ConfSearch](http://confsearch.ethz.ch/confsearch/)
  - [WikiCfp](http://www.wikicfp.com/cfp/)

- Halls of Fame:
  - [SOSP/OSDI](https://www.cs.utexas.edu/~vijay/hall.html) - Systems Research
  - [ISCA](http://pages.cs.wisc.edu/~arch/www/iscabibhall.html)
  - [MICRO](http://newsletter.sigmicro.org/micro-hof.txt/view) - Microarchitecture
  - [Computer Architecture Aggregated Hall-of-Fame](http://moin.ece.gatech.edu/cathof.html)

### Open Source centric

- [ORConf](https://orconf.org/) - The open source digital design conference organized by the [Free and Open Source Silicon (FOSSi) Foundation](https://fossi-foundation.org/)
- [WOSH](https://fossi-foundation.org/wosh/) - Week of Open Source Hardware alongwith [The RISCV Workshop](https://tmt.knect365.com/risc-v-workshop-zurich/)

### Interconnects

- [Hot Interconnects](http://www.hoti.org/) - Symposium on High-Performance Interconnects
- [International Symposium on Networks-on-Chip (NOCS)](https://www.engr.colostate.edu/nocs2019/) is dedicated to interdisciplinary research on on-chip, package-scale, chip-to-chip, and datacenter rack-scale communication technology, architecture, design methods, applications and systems.

### High Performance Computing

- [SuperComputing](https://sc19.supercomputing.org/) -  International Conference for High Performance Computing, Networking, Storage, and Analysis.
- [HPCA](https://www.computer.org/conferences/cfp/HPCA2020) - International Symposium on High-Performance Computer Architecture by IEEE Computer Society
- [Hot Chips](https://www.hotchips.org/) - A Symposium on High Performance Chips
- [PASC](https://pasc-conference.org/) - The Platform for Advanced Scientific Computing (PASC) Conference is an interdisciplinary conference in HPC that brings together domain science, applied mathematics and computer science – where computer science is focused on enabling the realization of scientific computation.
- [ISC High Performance](https://www.isc-hpc.com/) - Event for HPC, Networking, Storage, AI/ML

## MOOCs

- Prof. Onur Mutlu's [lectures](https://www.youtube.com/channel/UCIwQ8uOeRFgOEvBLYc3kc3g/playlists) and [talks](https://people.inf.ethz.ch/omutlu/talks.htm)
- Computer Architecture [course](https://www.coursera.org/learn/comparch) by David Wentzlaff on Coursera
- [Notes](https://github.com/aphyr/distsys-class) on an introduction to distributed systems.

## Blogs/ Books

- ZipCPU's [blog](http://zipcpu.com/) - A good starting point for Verilog/ FPGA/ Formal Verification
- Eric LaForest's [blog](http://fpgacpu.ca/) as a resource about FPGAs, computer history, and computer architecture.
- David Fong's ASIC architecture [blog](https://daffy1108.wordpress.com/)

## Tools and Utilities

### Open Source Tools for Digital Design

- [Verilator](https://www.veripool.org/projects/verilator/) - Verilator is the fastest free Verilog HDL simulator, and outperforms most commercial simulators
- [Icarus Verilog](https://github.com/steveicarus/iverilog) - Icarus Verilog is not aimed at being a simulator in the traditional sense, but a compiler that generates code employed by back-end tools.
- [SymbiFlow](https://symbiflow.github.io) - Open source FPGA tooling available under [YosysHQ](https://github.com/YosysHQ)
- [GTKWave](http://gtkwave.sourceforge.net/) - GTKWave is a fully featured GTK+ based wave viewer.
- [Wavedrom](https://wavedrom.com/) - WaveDrom draws your Timing Diagram or Waveform from simple textual description.
- [SymbiYosys](https://github.com/YosysHQ/SymbiYosys) - Front-end for Yosys-based formal verification flows
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
- [The Open Road Project](https://github.com/The-OpenROAD-Project) - Includes [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA), [RePlAce](https://github.com/The-OpenROAD-Project/RePlAce), [OpenDB](https://github.com/The-OpenROAD-Project/OpenDB), [ioPlacer](https://github.com/The-OpenROAD-Project/ioPlacer), [FastRoute4](https://github.com/The-OpenROAD-Project/FastRoute4-lefdef) and other tools.
- [Open Register Design](https://github.com/Juniper/open-register-design-tool) - Tool to generate register RTL, models, and docs using SystemRDL or JSpec input
- [LibrePCB](https://librepcb.org/) - A powerful, innovative and intuitive EDA tool for everyone!
  
### Simulators

- [gem5](http://gem5.org/Main_Page) - The gem5 simulator is a modular platform for computer-system architecture research, encompassing system-level architecture as well as processor microarchitecture.
- [DigitalJS](https://github.com/tilk/digitaljs) - Visualize and simulate digital logic using HDL
- [FireSim](https://fires.im) - FireSim is an open-source cycle-accurate FPGA-accelerated full-system hardware simulation platform that runs on cloud FPGAs
- [Venus](https://github.com/kvakil/venus) - Venus is a RISC-V instruction set simulator built for education.
- [EDA Playground](https://www.edaplayground.com/) - Run HDL/HVL code in your browser
- [Electronic Circuit Simulator](https://www.falstad.com/circuit/)
- [CPULator](https://cpulator.01xz.net/) - CPUlator Computer System Simulator designed as a tool for learning assembly-language programming and computer organization
- [ASMBits](https://asmbits.01xz.net/wiki/Main_Page) - Assembly Practice
- [HDLBits](https://hdlbits.01xz.net/wiki/Main_Page) - Verilog Practice
- [8bit Workshop](http://8bitworkshop.com/redir.html?platform=verilog) - Verilog to waves instantly
- [Logic Design and Circuit Simulator](https://github.com/hneemann/Digital)

### Emulators

- [TinyEMU](https://bellard.org/tinyemu/) - TinyEMU is a system emulator for the RISC-V and x86 architectures.
- [Unicorn](https://www.unicorn-engine.org/) - Unicorn is a lightweight multi-platform, multi-architecture CPU emulator framework.
- [Emulator for Ben Eater's 8bit computer](https://fizzgig.itch.io/8-bit-breadboard-computer)

## Communities

- [ACM](https://www.acm.org/) Association for Computing Machinery
- [SIGARCH](https://www.sigarch.org/) Computer professionals working on the forefront of computer design in both industry and academia.
- [Semiconductor Research Coroportation](https://www.src.org/)
- [CHIPS Alliance](https://chipsalliance.org/) - CHIPS (Common Hardware for Interfaces, Processors and Systems) Alliance harnesses the energy of open source collaboration to accelerate hardware development.
- [OpenCAPI](https://opencapi.org/) - Open Coherent Accelerator Processor Interface

## Interesting Resources

- [Workshop on Open Source Design Automation (OSDA)](https://osda.gitlab.io/)
- [A great resource on upcoming Systems conferences and venues](http://www.cs.technion.ac.il/~dan/index_sysvenues_deadline.html)
- [Computer Latency at a Human Scale](https://www.prowesscorp.com/computer-latency-at-a-human-scale/)
- [Networking conference search tool](
http://confsearch.ethz.ch/confsearch/faces/pages/staticresults.jsp?query=usenix%20asplos%20ewsn%20hotnets%20hotos%20ipsn%20isca%20micro%20mobicom%20mobihoc%20mobisys%20nsdi%20osdi%20sensys%20sigcomm%20sosp%20uist&sortMode=1&graphicView=1)
- [Libre Silicon Project](https://libresilicon.com/) - An open source semiconductor manufacturing process standard
- [Discussion on Lowlevel LLVM-like language as HDL middle layer](https://github.com/SymbiFlow/ideas/issues/19)
- [Chips for Machine Intelligence in 2019](https://www.jameswhanlon.com/new-chips-for-machine-intelligence.html)
- [Microprocessor trend data](https://github.com/karlrupp/microprocessor-trend-data)
- [Demonstration of Hardware Effects](https://github.com/Kobzol/hardware-effects) - This repository demonstrates various hardware effects that can degrade application performance in surprising ways and that may be very hard to explain without knowledge of the low-level CPU and OS architecture.

## Digging Deeper

Computer Architecture is diverse and there's constant interplay between domains that are under it. Look under each of these to find specific information. (At the time of writing, these are the specific areas that I'm most interested in)

- [Hardware Design](./more/hardware_design.md)
- [Processors](./more/processors.md)
- [Interconnects](./more/interconnects.md)
- [Performance](./more/performance.md)
- [Hardware-Software Interface](./more/hw_sw.md)
- [High Performance Computing](./more/hpc.md)

## Other specific curated lists related to CompArch

- [Deep Learning Hardware resources](https://github.com/RaviVijay/awesome-dl-hw-resources) A curated list of awesome hardware/chip design resources for deep learning
- [Awesome-HDL](https://github.com/drom/awesome-hdl) A curated list of amazingly awesome hardware description language projects.
- [Awesome-Quantum-Computing](https://github.com/desireevl/awesome-quantum-computing) - A curated list of awesome quantum computing learning and developing resources.
- [Getting started with FPGA](https://github.com/lastweek/FPGA) - This repository is intended for folks who are new and want to learn something about FPGA. This repository is a collection of useful resources and links rather than a thorough FPGA tutorial.
