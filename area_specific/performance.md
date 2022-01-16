# Performance Analysis

- [Chip-level](#chip-level)
  - [Tools](#tools)
  - [Good Reads](#good-reads)
  - [Resources](#resources)
    - [Articles](#articles)
- [System-level](#system-level)
  - [Articles](#articles-1)
  - [Tools](#tools-1)
  - [Benchmarks](#benchmarks)
- [Programming & Optimization](#programming--optimization)
  - [Tools](#tools-2)
  - [Resources](#resources-1)

## Chip-level

### Tools

- [MachSuite](https://github.com/breagen/MachSuite) - MachSuite is a benchmark suite intended for accelerator-centric research.

### Good Reads

- [Prof. Mark Hill note argues for more use of simple models beyond Amdahl's Law: Bottleneck Analysis, Little's Law, and a M/M/1 Queue.](https://arxiv.org/abs/1901.02926)

### Resources

#### Articles

- [Analyzing and Debugging Performance Issues with Advanced ARM CoreLink System IP Components](https://ip.cadence.com/uploads/251/white-paper-interconnect-solutions-debugging-issues-advanced-ARM-CoreLink-pdf)
- [SoC Interconnect Analysis](https://community.cadence.com/cadence_blogs_8/b/ii/posts/designer-view-soc-interconnect-analysis-what-we-re-doing-what-s-still-needed)
- [Why on-chip networks are important?](https://semiengineering.com/not-enough-respect-for-soc-interconnect/)
- [How to measure System Performance?](https://community.arm.com/developer/ip-products/system/b/soc-design-blog/posts/how-to-measure-and-optimize-the-system-performance-of-a-smartphone-rtl-design)

## System-level

### Articles

- [How much bandwidth does the L2 have to give, anyway?](https://github.com/travisdowns/uarch-bench/wiki/How-much-bandwidth-does-the-L2-have-to-give,-anyway%3F)
- [Every 7.8μs your computer’s memory has a hiccup](https://blog.cloudflare.com/every-7-8us-your-computers-memory-has-a-hiccup/)
- [Computer Latency at a Human Scale](https://www.prowesscorp.com/computer-latency-at-a-human-scale/)
- [Latency numbers every programmer should know](https://people.eecs.berkeley.edu/~rcs/research/interactive_latency.html)
- [Performance variations in 2386 identical processors](http://shape-of-code.coding-guidelines.com/2020/01/05/performance-variation-in-2386-identical-processors/)
- [Memory Bandwidth: Napkin math](https://www.forrestthewoods.com/blog/memory-bandwidth-napkin-math/)

### Tools

- [nanoBench](http://www.uops.info) - A tool for running small microbenchmarks on recent Intel and AMD x86 CPUs using hardware performance coutners. [Github](https://github.com/andreas-abel/nanoBench)
- [CPU Benchmark results](https://www.anandtech.com/bench/CPU-2019/2605)
- [kerncraft](https://github.com/RRZE-HPC/kerncraft) - This tool allows automatic analysis of loop kernels using the Execution Cache Memory (ECM) model, the Roofline model and actual benchmarks. kerncraft provides a framework to investigate the data reuse and cache requirements by static code analysis. In combination with the Intel IACA tool kerncraft can give a good overview of both in-core and memory bottlenecks and use that data to apply performance models.

### Benchmarks

- [CHAI](https://chai-benchmarks.github.io/) - Chai is a benchmark suite of Collaborative Heterogeneous Applications for Integrated-architectures. The Chai benchmarks are designed to use the latest features of heterogeneous architectures such as shared virtual memory and system-wide atomics to achieve efficient simultaneous collaboration between host and accelerator devices.

## Programming & Optimization

### Tools

- [TAU Performance System](https://www.cs.uoregon.edu/research/tau/home.php) - A portable profiling and tracing toolkit for performance analysis of parallel programs written in Fortran, C, C++, UPC, Java, Python.
- [Scalene](https://github.com/plasma-umass/scalene) - A high-performance CPU, GPU and memory profiler for Python

### Resources

- [Understanding Complexities](https://www.bigocheatsheet.com/)
- [Performance Analysis of Multi-threaded applications for beginners](https://easyperf.net/blog/2019/10/05/Performance-Analysis-Of-MT-apps)
- [Multithread vs Multiprocess](https://blog.floydhub.com/multiprocessing-vs-threading-in-python-what-every-data-scientist-needs-to-know/)