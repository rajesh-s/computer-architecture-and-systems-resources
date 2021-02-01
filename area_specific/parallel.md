<!-- no toc -->

# Parallel Computing

- [1. Hardware](#1-hardware)
- [2. Software (Parallel programming)](#2-software-parallel-programming)
  - [2.1. Platforms](#21-platforms)
  - [2.2. Languages](#22-languages)
    - [2.2.1. CUDA](#221-cuda)
      - [2.2.1.1. Learning](#2211-learning)
      - [2.2.1.2. Utilities](#2212-utilities)

## 1. Hardware

## 2. Software (Parallel programming)

- [Deep Learning from Scratch to GPU](https://dragan.rocks/articles/19/Deep-Learning-in-Clojure-From-Scratch-to-GPU-1-Representing-Layers-and-Connections) - A series on getting started with parallel programming
- (Article) [HPC is more parallel than ever](https://medium.com/tebs-lab/the-age-of-parallel-computing-b3f4319c97b0)

### 2.1. Platforms

- [Radeon Open Compute](https://rocm.github.io/) - Platform for GPU-Enabled HPC and Ultrascale Computing

### 2.2. Languages

- [Futhark](https://futhark-lang.org/) - Futhark is a small programming language designed to be compiled to efficient parallel code. It is a statically typed, data-parallel, and purely functional array language in the ML family, and comes with a heavily optimising ahead-of-time compiler that presently generates either GPU code via CUDA and OpenCL, or multi-threaded CPU code.

#### 2.2.1. CUDA

##### 2.2.1.1. Learning

- [CUDA 101](https://hackaday.com/2018/03/19/cuda-is-like-owning-a-supercomputer/)
- [An Even Easier Introduction to CUDA](https://developer.nvidia.com/blog/even-easier-introduction-cuda/)
- [CUDA documentation](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html)

##### 2.2.1.2. Utilities

- [CUDA Occupancy Calculator](https://docs.nvidia.com/cuda/cuda-occupancy-calculator/index.html) - Compute the multiprocessor occupancy of a GPU by a given CUDA kernel