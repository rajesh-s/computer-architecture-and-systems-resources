# Processors

- [Open-source digital design implementations of Processors](#open-source-digital-design-implementations-of-processors)
  - [RISCV based](#riscv-based)
- [Microarchitecture](#microarchitecture)
- [ISA](#isa)
- [Interesting resources](#interesting-resources)
  - [Must Reads](#must-reads)
- [GPU](#gpu)
  - [Learning Resources](#learning-resources)

Everything about processors

## Open-source digital design implementations of Processors

- [ZipCPU](https://github.com/ZipCPU/zipcpu) - A small, light weight, RISC CPU soft core
- [Microwatt](https://github.com/antonblanchard/microwatt/) - A tiny Open POWER ISA softcore written in VHDL for FPGAs
- [Simple Microcoded CPU](https://minnie.tuhs.org/CompArch/Tutes/week04.html)
- [OpenRISC Project](https://github.com/openrisc)
- [OpenPiton](https://github.com/PrincetonUniversity/openpiton) - OpenPiton is an open source, general purpose, multithreaded manycore processor. It is a 64-bit architecture using SPARC v9 ISA with a distributed directory-based cache coherence protocol across on-chip networks

### RISCV based

- [PicoRV32](https://github.com/cliffordwolf/picorv32) - A Size-Optimized RISC-V CPU
- [Vectorblox ORCA](https://github.com/VectorBlox/orca) - ORCA is an implementation of RISC-V. It is intended to target FPGAs and can be configured as either RV32I a RV32IM core.
- [Pulpino](https://github.com/pulp-platform/pulpino) - PULPino is an open-source single-core microcontroller system, based on 32-bit RISC-V cores developed at ETH Zurich. PULPino is configurable to use either the RISCY or the zero-riscy core.
- [Icicle](https://github.com/grahamedgecombe/icicle) - Icicle is a 32-bit RISC-V system on chip for iCE40 HX8K, iCE40 UP5K and ECP5 FPGAs. It can be built with the open-source SymbiFlow toolchain and currently targets several development boards.
- [RISCV-BOOM](https://github.com/riscv-boom/riscv-boom) - The Berkeley Out-of-Order Machine (BOOM) is a synthesizable and parameterizable open source RV64GC RISC-V core written in the Chisel hardware construction language.
- [Piccolo](https://github.com/bluespec/Piccolo) - Open-source RISC-V CPUs from Bluespec
- [RI5CY](https://github.com/pulp-platform/riscv) - RISCY is an in-order 4-stage RISC-V RV32IMFCXpulp CPU
- [VexRiscv](https://github.com/SpinalHDL/VexRiscv) - FPGA-friendly RISC-V implementation written in SpinalHDL
- [darkriscv](https://github.com/darklife/darkriscv) - opensouce RISC-V implemented from scratch in one night!
- [SiFive Freedom](https://github.com/sifive/freedom)
- [Ariane](https://github.com/lowRISC/ariane) - Ariane is a 6-stage, single issue, in-order CPU which implements the 64-bit RISC-V instruction set. It fully implements I, M, A and C extensions
- [Shakti Processors](http://shakti.org.in/processor.html)
- [Minerva](https://github.com/lambdaconcept/minerva) - Minerva is a CPU core that currently implements the RISC-V RV32IM instruction set. Its microarchitecture is described in plain Python code using the nMigen toolbox.
- [BlackParrot](https://github.com/black-parrot/pre-alpha-release) - BlackParrot aims to be the default Linux-capable, cache-coherent, RV64GC multicore used by the world.
- [PulseRain Reindeer](https://github.com/PulseRain/Reindeer) - RISCV RV32I[M] Soft CPU
- [Sodor](https://github.com/ucb-bar/riscv-sodor) - Educational microarchitectures collection for risc-v isa
- [BOOM](https://github.com/riscv-boom/riscv-boom) - The Berkeley Out-of-Order RISC-V Processor.
- [RSD](https://github.com/rsd-devel/rsd) - RISC-V Out-of-Order Superscalar Processor
- [BRISC-V Explorer](https://ascslab.org/research/briscv/explorer/explorer.html) - Generate RISC V Cores for different configurations
- [**RISCV Assembly visualizer**](http://tice.sea.eseo.fr/riscv/) - Visualize instruction flow through registers

## Microarchitecture

- [Microarch cheatsheet](https://docs.google.com/spreadsheets/d/18ln8SKIGRK5_6NymgdB9oLbTJCFwx0iFI-vUs6WFyuE/edit#gid=1076260513) - Centralised information about CPU μarch design such as caches, buffers, instruction width, etc

## ISA

- [Great ISAs](https://www.cs.cornell.edu/courses/cs7491/2020sp/)
- [Floating Point Visually Explained](https://fabiensanglard.net/floating_point_visually_explained/)

## Interesting resources

- [sandsifter](https://github.com/xoreaxeaxeax/sandsifter) - The sandsifter audits x86 processors for hidden instructions and hardware bugs, by systematically generating machine code to search through a processor's instruction set, and monitoring execution for anomalies.
- [The MultiCore Association](https://www.multicore-association.org/index.php) - To define and promote open specifications to enable multicore product development.
- [Skylake MicroArch](https://en.wikichip.org/wiki/intel/microarchitectures/skylake_(server))
- [Programmed Introduction to MIPS Assembly Language](https://chortle.ccsu.edu/AssemblyTutorial/index.html)
- [Myths Programmer's believe about CPU Cache](https://software.rajivprab.com/2018/04/29/myths-programmers-believe-about-cpu-caches/)
- [Great Microprocessors of the past and present](http://www.cpushack.com/CPU/cpu.html#tableofcontents)
- [Microarchitecture Block Diagrams of Intel, ARM and AMD processors](https://drive.google.com/drive/folders/1W4CIRKtNML74BKjSbXerRsIzAUk3ppSG)
- [Microarchitecture, Cache Organization and other details of Intel Processors](https://www.uops.info/cache.html)
- [The first ARM processor](https://spectrum.ieee.org/tech-history/silicon-revolution/chip-hall-of-fame-acorn-computers-arm1-processor)

### Must Reads

- [Modern Microprocessors: A 90-minute guide](http://www.lighterra.com/papers/modernmicroprocessors/)

## GPU

### Learning Resources

- [Graphics Processing Units (GPUs): Architecture and Programming](https://cs.nyu.edu/courses/fall15/CSCI-GA.3033-004/)
- [Floating Point visually explained](http://fabiensanglard.net/floating_point_visually_explained/index.php)
- [Why Floating Point?](https://engineering.fb.com/ai-research/floating-point-math/)
- [Bug free RISC core without simulation?](https://tomverbeure.github.io/risc-v/2018/11/19/A-Bug-Free-RISC-V-Core-without-Simulation.html)