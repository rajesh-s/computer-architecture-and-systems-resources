<!-- no toc -->

# Hardware Design

- [1. Chip Design \(ASIC/SoC\)](#1-chip-design-asicsoc)
  - [1.1. Analog Design](#11-analog-design)
  - [1.2. Digital Design](#12-digital-design)
  - [1.3. Open Source Implementations](#13-open-source-implementations)
    - [1.3.1. Open Core Collections](#131-open-core-collections)
    - [1.3.2. Elements](#132-elements)
- [2. Resources](#2-resources)
  - [2.1. Articles](#21-articles)
  - [2.2. Courses & Tutorials](#22-courses--tutorials)
  - [2.3. Books](#23-books)
  - [2.4. Others](#24-others)
- [3. Open Source Hardware](#3-open-source-hardware)
  - [3.1. Community Organization](#31-community-organization)
- [4. Research](#4-research)
  - [4.1. Design Conferences](#41-design-conferences)
  - [4.2. Workshops and Conference Sessions on Open Source EDA](#42-workshops-and-conference-sessions-on-open-source-eda)

## 1. Chip Design \(ASIC/SoC\)

### 1.1. Analog Design

- [The Designer's Guide® Community](https://designers-guide.org/) Analog, mixed-signal and RF circuit designers come to learn about simulation, modeling and design.
- [Using gm/Id methodology](https://eesurgeon.wordpress.com/2016/07/06/using-the-gmid-methodology-in-analog-circuit-design/)

### 1.2. Digital Design

### 1.3. Open Source Implementations

#### 1.3.1. Open Core Collections

- [OpenCores](https://opencores.org/) - OpenCores is the most prominent online community for the development of gateware IP (Intellectual Properties) Cores.
- [LibreCores](https://www.librecores.org/) - A "LibreCore" is such an IP core that is created and distributed in the open source spirit.
- [OpenTitan](https://github.com/lowrisc/opentitan) - OpenTitan will make the silicon RoT design and implementation more transparent, trustworthy, and secure for enterprises, platform providers, and chip manufacturers.

#### 1.3.2. Elements

- [Basic Common SV Modules](https://github.com/taichi-ishitani/tbcm) - FIFO, onehot, round robin Arbiter etc.
- [Ethernet 1G/100M/10M Core](https://github.com/lewiz-support/LMAC_CORE1) - Open source Ethernet Core 1
- [Asynchronous FIFO](https://github.com/damofthemoon/async_fifo) - A dual clock asynchronous FIFO written in verilog, tested with Icarus Verilog
- [CDC Modules](https://github.com/damofthemoon/cdc) - This repository gathers several basic modules to handle CDC in a design
- [One-Hot Mux](https://andy-knowles.github.io/one-hot-mux/) - Understanding synthesis of the one-hot mux

## 2. Resources

### 2.1. Articles

- [SystemVerilog 2007 changelog explained](http://www.verilab.com/blog/2018/02/ieee-std1800-2017-for-systemverilog-what-changed/)
- Blogs on Physical Design
  - [Informative blog. A good starting point.](https://gogul.dev/hardware/physical-design)
  - [Good info on Clock Tree aspects](http://88physicaldesign.blogspot.com/)
  - [All about Timing Analysis](http://www.vlsi-expert.com/p/static-timing-analysis.html?m=1)
- [UPF Commands and options](https://semiengineering.com/empowering-upf-commands-with-effective-elements-lists/)
- [System Verilog.io](https://www.systemverilog.io/) - Covers concepts, formal verification and language
- David Fong's ASIC architecture [blog](https://daffy1108.wordpress.com/)
- [Lessons in Hardware Reuse](https://zipcpu.com/blog/2020/01/13/reuse.html)
- [Libre Silicon Project](https://libresilicon.com/) - An open source semiconductor manufacturing process standard
- [Discussion on Lowlevel LLVM-like language as HDL middle layer](https://github.com/SymbiFlow/ideas/issues/19)

### 2.2. Courses & Tutorials

- [Verilog, Formal Verification and Verilator Beginner's Tutorial](http://zipcpu.com/tutorial/#training)
- [ASIC Verilog](http://asic-world.com/verilog/veritut.html)
- [NANDLand Verilog](https://www.nandland.com/verilog/tutorials/tutorial-introduction-to-verilog-for-beginners.html)
- [FPGA Tutorial](https://www.fpga4fun.com/)
- Rob A. Rutenbar, [VLSI CAD Part I: Logic](https://www.coursera.org/learn/vlsi-cad-logic) and [VLSI CAD Part II:Layout](https://www.coursera.org/learn/vlsi-cad-layout)
- Sung Kyu Lim, [ECE6133: Physical Design Automation of VLSI Systems](http://limsk.ece.gatech.edu/course/ece6133/)
- David Z. Pan, [EE 382V: VLSI Physical Design Automation](http://users.ece.utexas.edu/~dpan/EE382V_PDA/)
- Sanjit A. Seshia, [EECS 219C: Formal Methods: Specification, Verification, and Synthesis](https:/people.eecs.berkeley.edu/~sseshia/219c/)
- Chung-Kuan Cheng, [CSE245: Computer Aided Circuit Simulation and Verification](https://cseweb.ucsd.edu/classes/wi15cse245-a/)
- Gogul Ilango's notes [ASIC Design](https://gogul09.github.io/asic-design)
- ZipCPU's [blog](http://zipcpu.com/) - A good starting point for Verilog/ FPGA/ Formal Verification
- Eric LaForest's [blog](http://fpgacpu.ca/) as a resource about FPGAs, computer history, and computer architecture.
- [VLSI STA](http://www.vlsi-expert.com/p/static-timing-analysis.html) - Concepts and conventions explained

### 2.3. Books

- Constraining Designs for Synthesis and Timing Analysis \| A Practical Guide to Synopsys Design Constraints \(SDC\) - Gangadharan, Sridhar, Churiwala, Sanjay.
- Static Timing Analysis for Nanometer Designs: A Practical Approach - Jayaram Bhasker and Rakesh Chadha.

### 2.4. Others

- [FuseSoC](https://github.com/olofk/fusesoc) - FuseSoC is an award-winning package manager and a set of build tools for HDL (Hardware Description Language) code. Its main purpose is to increase reuse of IP (Intellectual Property) cores and be an aid for creating, building and simulating SoC solutions.
- [EDAlize](https://github.com/olofk/edalize) - An abstraction library for interfacing EDA tools
- [Renode](https://renode.io/) - Open source software development framework with commercial support from Antmicro that lets you develop, debug and test multi-node device systems reliably, scalably and effectively.
- [Open Road](https://vlsicad.ucsd.edu/~abk/BDC-Kahng-200102-OpenROAD-v4a.pptx) and [EDA Frontiers](https://vlsicad.ucsd.edu/~abk/BDC-Kahng-200103-FrontiersEDA-v2.pptx) presentation by Andrew Kahng
- [DARPA EDA POSH](https://www.darpa.mil/attachments/eri_design_proposers_day.pdf) presentation by Andreas Olofsson
- [Letters from EDA users](http://www.deepchip.com/) - Insights from EDA users over the years

## 3. Open Source Hardware

### 3.1. Community Organization

- [FOSSi Foundation](https://fossi-foundation.org/) - Free and Open Source Silicon (FOSSi) are components and systems that are inside silicon devices (‘chips’). It is our core belief that building blocks that form such digital devices can be made free and open

## 4. Research

### 4.1. Design Conferences

- [ORConf](https://orconf.org/) - The open source digital design conference organized by the [Free and Open Source Silicon (FOSSi) Foundation](https://fossi-foundation.org/)
- [WOSH](https://fossi-foundation.org/wosh/) - Week of Open Source Hardware alongwith [The RISCV Workshop](https://tmt.knect365.com/risc-v-workshop-zurich/)
- [ISCAS](https://iscas2020.org/) - IEEE International Symposium on Circuits and Systems
- [ICONS](https://ornlcda.github.io/icons2019/) - Conference on Neuromorphic Computing
- [VLSI Symposia](https://vlsisymposium.org/) - Conference on semiconductor technology and circuits
- [ISSCC](http://isscc.org/) -  International Solid-State Circuits Conference is the foremost global forum for presentation of advances in solid-state circuits and systems-on-a-chip
- [MCSoC](http://mcsoc-forum.org/m2019/ieee-mcsoc-2019-presentation-slides/) - Multicore SoC's

### 4.2. Workshops and Conference Sessions on Open Source EDA

- WOSET: Workshop on Open-Source EDA Technology
  - [WOSET](https://woset-workshop.github.io/), co-located with ICCAD, Nov 8, 2018; San Diego, CA, USA.
- OSDA: Workshop on Open Source Design Automation
  - [OSDA 2019](https://osda.gitlab.io/), co-located with DATE, March 29, 2019; Florence, Italy.
- [ORConf: The open source digital design conferece](https://orconf.org/)
  - ORConfs: [2018](https://orconf.org/2018/) \| [2017](https://orconf.org/2017/) \| [2016](https://orconf.org/2016/) \| [2015](https://orconf.org/2015/) \| [2014](https://orconf.org/2014/) \| [2013](https://orconf.org/2013/) \| [2012](https://orconf.org/2012/)
- DAC Birds of a Feather: Open Source Academic EDA Software
  - [DAC 2019 BOF](https://github.com/The-OpenROAD-Project/Birds-of-a-Feather-Open-Source-Academic-EDA-Software/wiki/DAC-2019-Birds-of-a-Feather:-Open-Source-Academic-EDA-Software), June 5, 2019; Las Vegas, NV, USA.
- [DAC 2019 Session 37, Unleashing Open Source EDA](http://www2.dac.com/events/eventdetails.aspx?id=267-37), June 4, 2019; Las Vegas, NV, USA.
- [Workshop on Open Source Design Automation \(OSDA\)](https://osda.gitlab.io/)