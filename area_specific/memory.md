# Memory and Storage Systems

- [Resources](#resources)
  - [Projects](#projects)
  - [Articles](#articles)
- [Persistent/Non Volatile Memory](#persistentnon-volatile-memory)
  - [Learning resources](#learning-resources)
  - [Projects/Frameworks](#projectsframeworks)
- [Research avenues](#research-avenues)

## Resources

- [Constantly updated thread on developments in memory by Ogawa on twitter](https://twitter.com/ogawa_tter/status/1341217903236923392)
- [SSD ELI5](https://www.youtube.com/watch?v=5f2xOxRGKqk)
- [TheMemoryGuy](https://thememoryguy.com/) and [TheSSDGuy](thessdguy.com)
- [Visualizations for cache and coherence](https://www.scss.tcd.ie/Jeremy.Jones/VivioJS/)

### Projects

- [HSE: Heterogeneous-Memory Storage Engine](https://github.com/hse-project/hse) - HSE is an embeddable key-value store designed for SSDs based on NAND flash or persistent memory. HSE optimizes performance and endurance by orchestrating data placement across DRAM and multiple classes of SSDs or other solid-state storage.

### Articles

- [DRAM Modeling](https://www.adityaagrawal.net/blog/architecture/dram)
- [Understanding and Implementing DRAM Timings](https://www.adityaagrawal.net/blog/architecture/dram_timing)

## Persistent/Non Volatile Memory

### Learning resources

- [Course lectures by Prof. Michael Swift on PMEM](https://pages.cs.wisc.edu/~swift/classes/cs839-fa21/wiki/pmwiki.php)
- [Optane DCPMM](https://www.intel.in/content/www/in/en/architecture-and-technology/optane-dc-persistent-memory.html) - Intel DC Optane technology
- [Persistent Memory Programming book](https://pmem.io/)
- [Overview of DCPMM presented by Arafa, Intel](https://www.youtube.com/watch?v=BShO6h8Lc1s)
- [NVDIMM Primer](https://thessdguy.com/an-nvdimm-primer-part-1-of-2/)
- [Emerging standalone NVM](https://community.arm.com/developer/research/b/articles/posts/emerging-standalone-nvm-moving-beyond-the-hype?utm_source=linkedin&utm_medium=social&utm_campaign=2019_na_na_na-&utm_term=na&utm_content=blog)
- [Quick overview of ordering](https://www.youtube.com/watch?v=VdTya_98tcA)

### Projects/Frameworks

- [PMDK](https://pmem.io/pmdk/) - Collection of libraries and tools. Tuned and validated on both Linux and Windows, the libraries build on the DAX feature of those operating systems (short for Direct Access) which allows applications to access persistent memory as memory-mapped files, as described in the SNIA NVM Programming Model.

## Research avenues

- [SYSTOR](https://www.systor.org/2021/) - ACM Storage and Systems Conference