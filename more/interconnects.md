# Interconnects

Everything about:

- On-chip communication
- Inter-chip communication
- Computer Networks

- [Interconnects](#interconnects)
  - [Chip-level communication](#chip-level-communication)
  - [Inter-Chip communication](#inter-chip-communication)
  - [OpenSource Implementations](#opensource-implementations)
    - [On-Chip](#on-chip)
    - [Inter-chip](#inter-chip)
  - [Resources](#resources)

## Chip-level communication

- [Compute Express Link aka CXL](https://www.computeexpresslink.org/) Compute Express Link (CXL) is a new breakthrough high-speed CPU interconnect that enables a high-speed, efficient performance between the CPU and platform enhancements and workload accelerators.

## Inter-Chip communication

- [Flexibly Scalable High Performance Architectures with Embedded Photonics](https://insidehpc.com/2019/07/flexibly-scalable-high-performance-architectures-with-embedded-photonics/)

## OpenSource Implementations

### On-Chip

- [Wishbone Interconnect](https://github.com/fossi-foundation/wishbone) - A well-documented, popular open source standard compatible with most open-source IP.
- [WishBone to AXI](https://github.com/ZipCPU/wb2axip) - A Pipelined Wishbone B4 to AXI4 bridge
- [AXI Stream Components](https://github.com/alexforencich/verilog-axis) - Collection of AXI Stream bus components. Most components are fully parametrizable in interface widths.
- [AXI Components](https://github.com/alexforencich/verilog-axi) - Verilog AXI components for FPGA implementation
- [AXI4](https://github.com/pulp-platform/axi) - AXI4 and AXI4-Lite interface definitions and testbench utilities
- [Building a custom yet functional AXI-lite slave](https://zipcpu.com/blog/2019/01/12/demoaxilite.html)

### Inter-chip

- [Ethernet Components](https://github.com/alexforencich/verilog-ethernet) - Collection of Ethernet-related components for gigabit, 10G, and 25G packet processing (8 bit and 64 bit datapaths).
- [Corundum](https://github.com/ucsdsysnet/corundum) - Corundum is an open-source, high-performance FPGA-based NIC.

## Resources

- [AXI3/4 Cheatsheet](https://github.com/rajesh-s/axi_chestsheet) - Handy quick reference for ARM on-chip protocol standards