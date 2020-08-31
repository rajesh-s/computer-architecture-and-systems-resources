# Interconnects

Everything about on-chip and inter-chip communication

- [OpenSource Implementations](#opensource-implementations)
  - [On-Chip](#on-chip)
  - [Inter-chip](#inter-chip)
- [Resources](#resources)
  - [Articles](#articles)
  - [Books](#books)
  - [Misc](#misc)
- [Industry Standards](#industry-standards)

## OpenSource Implementations

### On-Chip

- [Wishbone Interconnect](https://github.com/fossi-foundation/wishbone) - A well-documented, popular open source standard compatible with most open-source IP.
- [WishBone to AXI](https://github.com/ZipCPU/wb2axip) - A Pipelined Wishbone B4 to AXI4 bridge
- [AXI Stream Components](https://github.com/alexforencich/verilog-axis) - Collection of AXI Stream bus components. Most components are fully parametrizable in interface widths.
- [AXI Components](https://github.com/alexforencich/verilog-axi) - Verilog AXI components for FPGA implementation
- [AXI4](https://github.com/pulp-platform/axi) - AXI4 and AXI4-Lite interface definitions and testbench utilities
- [Building a custom yet functional AXI-lite slave](https://zipcpu.com/blog/2019/01/12/demoaxilite.html)
- [TNoC](https://github.com/taichi-ishitani/tnoc) - Network on Chip implementation written in SystemVerilog
- [AMBA AXI VIP](https://github.com/taichi-ishitani/tvip-axi) - TVIP-AXI is an UVM package of AMBA AXI4 VIP
- [OpenSoCFabric](https://github.com/LBL-CoDEx/OpenSoCFabric) - A Network-On-Chip Generator

### Inter-chip

- [Ethernet Components](https://github.com/alexforencich/verilog-ethernet) - Collection of Ethernet-related components for gigabit, 10G, and 25G packet processing \(8 bit and 64 bit datapaths\).
- [Corundum](https://github.com/ucsdsysnet/corundum) - Corundum is an open-source, high-performance FPGA-based NIC.
- [Compute Express Link aka CXL](https://www.computeexpresslink.org/) Compute Express Link \(CXL\) is a new breakthrough high-speed CPU interconnect that enables a high-speed, efficient performance between the CPU and platform enhancements and workload accelerators.

## Resources

- [Great resource on simulators, research reading etc for interconnects](https://networkonchip.wordpress.com/) - The Network-on-Chip blog
- [NSF funded projects on NoCs](https://www.nsf.gov/awardsearch/advancedSearchResult?PIId=&PIFirstName=&PILastName=&PIOrganization=&PIState=&PIZip=&PICountry=&ProgOrganization=&ProgEleCode=&BooleanElement=All&ProgRefCode=&BooleanRef=All&Program=&ProgOfficer=&Keyword=%22NoC%22+%22on-chip%22+%22network-on-chip%22+%22networks-on-chip%22+%22interconnection+network%22&AwardNumberOperator=&AwardAmount=&AwardInstrument=&ActiveAwards=true&OriginalAwardDateOperator=&StartDateOperator=&ExpDateOperator=) - Shows distribution of funds across universities and types of work being carried out
- [AXI3/4 Cheatsheet](https://github.com/rajesh-s/axi_chestsheet) - Handy quick reference for ARM on-chip protocol standards
- [Designing a Skid Buffer](http://fpgacpu.ca/fpga/skid_buffer.html) - Implementing a fundamental element in on-chip interconnects

### Articles

- [Flexibly Scalable High Performance Architectures with Embedded Photonics](https://insidehpc.com/2019/07/flexibly-scalable-high-performance-architectures-with-embedded-photonics/)
- [Interconnect Prominence In Fail-Operational Architectures](https://semiengineering.com/interconnect-prominence-in-fail-operational-architectures/)
- [AXI verification](http://zipcpu.com/formal/2019/09/06/axi-story.html)
- [Lessons learned while building crossbar interconnects](https://zipcpu.com/blog/2019/07/17/crossbar.html)
- [Eating The Interconnect Alphabet Soup With Intel’s CXL](https://www.nextplatform.com/2019/09/18/eating-the-interconnect-alphabet-soup-with-intels-cxl/)
- [Inside HPE’s Gen-Z Switch Fabric](https://www.nextplatform.com/2019/09/09/inside-hpes-gen-z-switch-fabric/)
- [Silicon-Interconnect Fabric](https://spectrum.ieee.org/computing/hardware/goodbye-motherboard-hello-siliconinterconnect-fabric)
- [Why on-chip networks are so critical to IP integration](https://semiengineering.com/not-enough-respect-for-soc-interconnect/)
- [The Gatekeeper of a Successful Design is the Interconnect](https://www.eetimes.com/the-gatekeeper-of-a-successful-design-is-the-interconnect/)
- [How to Measure and Optimize the System Performance of a RTL Design](https://community.arm.com/developer/ip-products/system/b/soc-design-blog/posts/how-to-measure-and-optimize-the-system-performance-of-a-smartphone-rtl-design)

### Books

- [On-chip Networks](https://www.morganclaypool.com/doi/abs/10.2200/S00772ED1V01Y201704CAC040) - Synthesis Lectures on Computer Architecture
- [A Primer on Memory Consistency and Cache Coherence](https://www.morganclaypool.com/doi/abs/10.2200/S00962ED2V01Y201910CAC049)
- [Principles and Practices of Interconnection Networks](http://cva.stanford.edu/books/ppin/) - A book by William J Dally

### Misc

- [Lightwave Research Laboratory](https://lightwave.ee.columbia.edu/) - Research programs on optical interconnection networks for advanced computing systems, data centers, optical packet-switched routers, and nanophotonic networks-on-chip for chip multiprocessors

## Industry Standards

- [CCIX Consortium](https://www.ccixconsortium.com/about/) - Develop and promote adoption of an industry standard specification to enable coherent interconnect technologies between general-purpose processors and acceleration devices for efficient heterogeneous computing.
- [ARM joins CXL](https://community.arm.com/developer/ip-products/processors/b/processors-ip-blog/posts/arm-joins-cxl-establishing-key-industry-standard-to-streamline-heterogeneous-compute?utm_source=arm&utm_medium=social&utm_campaign=2019_infrastructure-servers_mk03-2_na-&utm_term=cxl&utm_content=blog)
