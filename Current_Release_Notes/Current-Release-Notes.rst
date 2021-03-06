
.. _Current-Release-Notes:

=====================
Current Release Notes
=====================

ROCm 1.6 What New?
###################

    *  2.0 compatible kernel language support with OpenCL 1.2 compatible runtime
    * OpenCL compiler also has assembler and disassembler support, inline assembly support.
    * Supports offline ahead of time compilation today; during the Beta phase we will add in-process/in-memory compilation.
    * Big improvements in the base Native LLVM code generator with new large number of optimization.
    * HCC Compiler Upgrade with New Gid Dispatch foundation
    * HIP new APIs: hipMemcpy2DAsync, hipMallocPitch, hipHostMallocCoherent, hipHostMallocNonCoherent
    * New Low Level Performance Library Interface
    * ARM AArch64 and IBM Power 8 support in the core driver
    * MIOpen 1.0 Deep Learning Solver.
    * Binary package support for Ubuntu 16.04 and Fedora 24
    * Debian and Yum Package for Math Libraries (rocBLAS, rocFFT, hcFFT, hcRNG, hcBLAS, hibBLAS)
    * ROCm-SMI update to check current Power Utilization of GPU
    * `Radeon Compute Profiler <https://github.com/GPUOpen-Tools/RCP>`_ (formally called the ROCm Profiler)
    * New Package Server repo.radeon.com to give you better download performance


