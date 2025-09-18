# Presentations on Programming Models

The morning session on Tuesday consists of talks introducing
HPC Programming Models. You are asked to prepare slides
demonstrating the topic together with some simple example live
example codes.

## Distributed programming with MPI

MPI is a distributed programming model going back to
1991. Even more than 30 years later it is still the dominant
model for parallelisation on large-scale HPC clusters.

## Shared memory paralellisation with OpenMP

OpenMP goes back to 1997 and is a leading model for
shared memory parallelisation on CPUs. In recent versions it
even supports some offloading to GPUs.

## CUDA for software development on NVIDIA GPUs

CUDA is the dominant programming model for NVIDIA GPUs. It is
a large ecosystem consisting of CUDA compiler , development
environments and scientific libraries.

## AMD HIP

HIP is AMD's programming model for AMD GPUs. It is fairly similar
to CUDA and allows for easy portability between CUDA and HIP code.

## OpenCL - Vendor independent GPU programming

OpenCL was originally developed as an open standard to compute
with the vendor dependent CUDA ecosystem. While it is less
used directly in scientific computing it is still very important
for development on embedded devices. And even for Scientific
Computing applications it still provides a powerful way to
write device independent GPU kernels.

## SYCL - A growing heterogeneous computing standard

SYCL has evolved from OpenCL to provide a modern heterogeneous
computing environment in C++. It is the programming standard
underlying modern Intel GPU accelerators but also supports AMD
and NVIDIA.

## Metal - Apple's take on GPU computing

Apple Metal is rarely used for scientific computing. But it is
a powerful model and the only way to access GPU cores on Apple
Silicon.

## SIMD - Low-level vector registers

SIMD is not really a programming model. It describes the set
of instructions found on most modern CPUs to efficiently execute operations on vector registers. Any CPU code targeted for
performance is optimised to make use of SIMD instructions as much
as possible.

## Parallel Programming with Jax

Jax is a library for efficient parallel array computations.
It is mostly used for Machine Learning but can also be used
to efficiently implement many other algorithms in scientific
computing.

