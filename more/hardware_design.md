# Hardware Design

* [Chip Design \(ASIC/FPGA/SoC\)](hardware_design.md#chip-design-asicfpgasoc)
  * [Projects](hardware_design.md#projects)
    * [FPGA](hardware_design.md#fpga)
  * [Tools & Utilities](hardware_design.md#tools--utilities)
  * [Open Source Implementations](hardware_design.md#open-source-implementations)
  * [Articles & Resources](hardware_design.md#articles--resources)
  * [Course & Tutorials](hardware_design.md#course--tutorials)
  * [Analog Design](hardware_design.md#analog-design)
  * [Books](hardware_design.md#books)
* [Board Level Design](hardware_design.md#board-level-design)
  * [Projects](hardware_design.md#projects-1)
  * [Tools](hardware_design.md#tools)
  * [Articles & Resources](hardware_design.md#articles--resources-1)
    * [Workshops and Conference Sessions on Open Source EDA](hardware_design.md#workshops-and-conference-sessions-on-open-source-eda)

## Chip Design \(ASIC/FPGA/SoC\)

### Projects

#### FPGA

* [FPGA Design Elements](https://github.com/laforest/FPGADesignElements) - A self-contained online book containing a library of FPGA design modules and related coding/design guides.
* [Blinky on every FPGA](https://github.com/fusesoc/blinky)
* [SoC Builder from LiteX](https://github.com/enjoy-digital/litex) - LiteX is a MiSoC-based SoC builder using Migen as Python DSL that can be used to create SoCs and full FPGA designs.

### Tools & Utilities

* [SystemVerilog Unit Test \(SVUT\)](https://github.com/damofthemoon/svut) - SVUT is a very simple flow to create a Verilog/SystemVerilog unit test.
* [AirHDL](https://airhdl.com) - Create register maps and headers
* [BitBench](http://triq.net/bitbench) - Visually dissect and analyze bit strings.
* [Bitfield](https://github.com/drom/bitfield) - BitField diagram Renderer
* [Diagrammer](https://github.com/freechipsproject/diagrammer) - Provides dot visualizations of chisel/firrtl circuites
* [VCD2Wavedrom](https://github.com/Toroid-io/vcd2wavedrom) - Handy for getting from simulation to spec quickly.
* [ipyxact](https://github.com/olofk/ipyxact) - Python-based IP-XACT parser
* [sv2v](https://github.com/zachjs/sv2v) - SystemVerilog to Verilog conversion
* [svlint](https://github.com/dalance/svlint) - System Verilog lint using rust
* [Wavedrom to Verilog](https://github.com/wavedrom/verilog)
* [HDL Checker](https://github.com/suoto/hdl_checker/blob/master/README.md) - HDL Checker is a language server that wraps VHDL/Verilg/SystemVerilog tools that aims to reduce the boilerplate code needed to set things up.
* [Wavedrom to ASCII converter](https://github.com/Wren6991/asciiwave) - README embeddable waveforms!
* [RgGen](https://github.com/rggen/rggen) - RgGen is a code generation tool for ASIC/IP/FPGA/RTL engineers. It will automatically generate soruce code related to configuration and status registers \(CSR\)
* [System RDL Compiler](https://github.com/SystemRDL/systemrdl-compiler) - The systemrdl-compiler module implements a generic compiler front-end for Accellera's SystemRDL 2.0 register description language.
* [Verismith](https://github.com/ymherklotz/verismith) - Verilog Fuzzer to test the major simulators and sythesisers by generating random, valid Verilog.

### Open Source Implementations

* [Basic Common SV Modules](https://github.com/taichi-ishitani/tbcm) - FIFO, onehot, round robin Arbiter etc.
* [Ethernet 1G/100M/10M Core](https://github.com/lewiz-support/LMAC_CORE1) - Open source Ethernet Core 1
* 
### Articles & Resources

* [SystemVerilog 2007 changelog explained](http://www.verilab.com/blog/2018/02/ieee-std1800-2017-for-systemverilog-what-changed/)
* Blogs on Physical Design
  * [Informative blog. A good starting point.](https://gogul.dev/hardware/physical-design)
  * [Good info on Clock Tree aspects](http://88physicaldesign.blogspot.com/)
  * [All about Timing Analysis](http://www.vlsi-expert.com/p/static-timing-analysis.html?m=1)
* [UPF Commands and options](https://semiengineering.com/empowering-upf-commands-with-effective-elements-lists/)
* [System Verilog.io](https://www.systemverilog.io/) - Covers concepts, formal verification and language

### Course & Tutorials

* [Verilog, Formal Verification and Verilator Beginner's Tutorial](http://zipcpu.com/tutorial/#training)
* [ASIC Verilog](http://asic-world.com/verilog/veritut.html)
* [NANDLand Verilog](https://www.nandland.com/verilog/tutorials/tutorial-introduction-to-verilog-for-beginners.html)
* [FPGA Tutorial](https://www.fpga4fun.com/)
* Rob A. Rutenbar, [VLSI CAD Part I: Logic](https://www.coursera.org/learn/vlsi-cad-logic) and [VLSI CAD Part II:Layout](https://www.coursera.org/learn/vlsi-cad-layout)
* Sung Kyu Lim, [ECE6133: Physical Design Automation of VLSI Systems](http://limsk.ece.gatech.edu/course/ece6133/)
* David Z. Pan, [EE 382V: VLSI Physical Design Automation](http://users.ece.utexas.edu/~dpan/EE382V_PDA/)
* Sanjit A. Seshia, [EECS 219C: Formal Methods: Specification, Verification, and Synthesis](https:/people.eecs.berkeley.edu/~sseshia/219c/)
* Chung-Kuan Cheng, [CSE245: Computer Aided Circuit Simulation and Verification](https://cseweb.ucsd.edu/classes/wi15cse245-a/)
* Gogul Ilango's notes [ASIC Design](https://gogul09.github.io/asic-design)

### Analog Design

* [The Designer's Guide® Community](https://designers-guide.org/) Analog, mixed-signal and RF circuit designers come to learn about simulation, modeling and design.
* [Using gm/Id methodology](https://eesurgeon.wordpress.com/2016/07/06/using-the-gmid-methodology-in-analog-circuit-design/)

### Books

* Constraining Designs for Synthesis and Timing Analysis \| A Practical Guide to Synopsys Design Constraints \(SDC\) - Gangadharan, Sridhar, Churiwala, Sanjay.
* Static Timing Analysis for Nanometer Designs: A Practical Approach - Jayaram Bhasker and Rakesh Chadha.

## Board Level Design

### Projects

### Tools

### Articles & Resources

#### Workshops and Conference Sessions on Open Source EDA

* WOSET: Workshop on Open-Source EDA Technology
  * [WOSET 2018](https://woset-workshop.github.io/), co-located with ICCAD, Nov 8, 2018; San Diego, CA, USA.
* OSDA: Workshop on Open Source Design Automation
  * [OSDA 2019](https://osda.gitlab.io/), co-located with DATE, March 29, 2019; Florence, Italy.
* [ORConf: The open source digital design conferece](https://orconf.org/)
  * ORConfs: [2018](https://orconf.org/2018/) \| [2017](https://orconf.org/2017/) \| [2016](https://orconf.org/2016/) \| [2015](https://orconf.org/2015/) \| [2014](https://orconf.org/2014/) \| [2013](https://orconf.org/2013/) \| [2012](https://orconf.org/2012/)
* DAC Birds of a Feather: Open Source Academic EDA Software
  * [DAC 2019 BOF](https://github.com/The-OpenROAD-Project/Birds-of-a-Feather-Open-Source-Academic-EDA-Software/wiki/DAC-2019-Birds-of-a-Feather:-Open-Source-Academic-EDA-Software), June 5, 2019; Las Vegas, NV, USA.
* [DAC 2019 Session 37, Unleashing Open Source EDA](http://www2.dac.com/events/eventdetails.aspx?id=267-37), June 4, 2019; Las Vegas, NV, USA.

