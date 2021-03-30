# Memory and Storage Systems

- [Resources](#resources)
  - [Projects](#projects)
- [Persistent/Non Volatile Memory](#persistentnon-volatile-memory)
  - [Learning resources](#learning-resources)
  - [Projects/Frameworks](#projectsframeworks)

## Resources

- [Constantly updated thread on developments in memory by Ogawa on twitter](https://twitter.com/ogawa_tter/status/1341217903236923392)
- [SSD ELI5](https://www.youtube.com/watch?v=5f2xOxRGKqk)
- [TheMemoryGuy](https://thememoryguy.com/) and [TheSSDGuy](thessdguy.com)

### Projects

- [HSE: Heterogeneous-Memory Storage Engine](https://github.com/hse-project/hse) - HSE is an embeddable key-value store designed for SSDs based on NAND flash or persistent memory. HSE optimizes performance and endurance by orchestrating data placement across DRAM and multiple classes of SSDs or other solid-state storage.

## Persistent/Non Volatile Memory

### Learning resources

- [Optane DCPMM](https://www.intel.in/content/www/in/en/architecture-and-technology/optane-dc-persistent-memory.html) - Intel DC Optane technology
- [Persistent Memory Programming book](https://pmem.io/)
- [Overview of DCPMM presented by Arafa, Intel](https://www.youtube.com/watch?v=BShO6h8Lc1s)
- [NVDIMM Primer](https://thessdguy.com/an-nvdimm-primer-part-1-of-2/)

### Projects/Frameworks

- [PMDK](https://pmem.io/pmdk/) - Collection of libraries and tools. Tuned and validated on both Linux and Windows, the libraries build on the DAX feature of those operating systems (short for Direct Access) which allows applications to access persistent memory as memory-mapped files, as described in the SNIA NVM Programming Model.