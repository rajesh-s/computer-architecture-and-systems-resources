# Hardware Design

- [Chip Design \(ASIC/FPGA/SoC\)](#chip-design-asicfpgasoc)
  - [FPGA](#fpga)
  - [Analog Design](#analog-design)
  - [Digital Design](#digital-design)
  - [Open Source Implementations](#open-source-implementations)
    - [Open Core Collections](#open-core-collections)
    - [Elements](#elements)
- [Resources](#resources)
  - [Articles](#articles)
  - [Courses & Tutorials](#courses--tutorials)
  - [Books](#books)
  - [Others](#others)

## Chip Design \(ASIC/FPGA/SoC\)

### FPGA

- [FPGA Design Elements](https://github.com/laforest/FPGADesignElements) - A self-contained online book containing a library of FPGA design modules and related coding/design guides.
- [Blinky on every FPGA](https://github.com/fusesoc/blinky)
- [SoC Builder from LiteX](https://github.com/enjoy-digital/litex) - LiteX is a MiSoC-based SoC builder using Migen as Python DSL that can be used to create SoCs and full FPGA designs.

### Analog Design

- [The Designer's Guide® Community](https://designers-guide.org/) Analog, mixed-signal and RF circuit designers come to learn about simulation, modeling and design.
- [Using gm/Id methodology](https://eesurgeon.wordpress.com/2016/07/06/using-the-gmid-methodology-in-analog-circuit-design/)

### Digital Design

### Open Source Implementations

#### Open Core Collections

- [OpenCores](https://opencores.org/) - OpenCores is the most prominent online community for the development of gateware IP (Intellectual Properties) Cores.
- [LibreCores](https://www.librecores.org/) - A "LibreCore" is such an IP core that is created and distributed in the open source spirit.
- [OpenTitan](https://github.com/lowrisc/opentitan) - OpenTitan will make the silicon RoT design and implementation more transparent, trustworthy, and secure for enterprises, platform providers, and chip manufacturers.

#### Elements

- [Basic Common SV Modules](https://github.com/taichi-ishitani/tbcm) - FIFO, onehot, round robin Arbiter etc.
- [Ethernet 1G/100M/10M Core](https://github.com/lewiz-support/LMAC_CORE1) - Open source Ethernet Core 1
- [Asynchronous FIFO](https://github.com/damofthemoon/async_fifo) - A dual clock asynchronous FIFO written in verilog, tested with Icarus Verilog
- [CDC Modules](https://github.com/damofthemoon/cdc) - This repository gathers several basic modules to handle CDC in a design

## Resources

### Articles

- [SystemVerilog 2007 changelog explained](http://www.verilab.com/blog/2018/02/ieee-std1800-2017-for-systemverilog-what-changed/)
- Blogs on Physical Design
  - [Informative blog. A good starting point.](https://gogul.dev/hardware/physical-design)
  - [Good info on Clock Tree aspects](http://88physicaldesign.blogspot.com/)
  - [All about Timing Analysis](http://www.vlsi-expert.com/p/static-timing-analysis.html?m=1)
- [UPF Commands and options](https://semiengineering.com/empowering-upf-commands-with-effective-elements-lists/)
- [System Verilog.io](https://www.systemverilog.io/) - Covers concepts, formal verification and language
- David Fong's ASIC architecture [blog](https://daffy1108.wordpress.com/)
- [Using SDRAM in FPGA Designs](https://www.joshbassett.info/sdram-controller/)

### Courses & Tutorials

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

### Books

- Constraining Designs for Synthesis and Timing Analysis \| A Practical Guide to Synopsys Design Constraints \(SDC\) - Gangadharan, Sridhar, Churiwala, Sanjay.
- Static Timing Analysis for Nanometer Designs: A Practical Approach - Jayaram Bhasker and Rakesh Chadha.

### Others

- [FuseSoC](https://github.com/olofk/fusesoc) - FuseSoC is an award-winning package manager and a set of build tools for HDL (Hardware Description Language) code. Its main purpose is to increase reuse of IP (Intellectual Property) cores and be an aid for creating, building and simulating SoC solutions.
- [EDAlize](https://github.com/olofk/edalize) - An abstraction library for interfacing EDA tools
- [Renode](https://renode.io/) - Open source software development framework with commercial support from Antmicro that lets you develop, debug and test multi-node device systems reliably, scalably and effectively.
- [Open Road](https://vlsicad.ucsd.edu/~abk/BDC-Kahng-200102-OpenROAD-v4a.pptx) and [EDA Frontiers](https://vlsicad.ucsd.edu/~abk/BDC-Kahng-200103-FrontiersEDA-v2.pptx) presentation by Andrew Kahng
- [DARPA EDA POSH](https://www.darpa.mil/attachments/eri_design_proposers_day.pdf) presentation by Andreas Olofsson
