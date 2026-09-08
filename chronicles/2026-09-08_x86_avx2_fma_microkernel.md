# x86_64 AVX2 Fused Multiply-Accumulate Microkernel

**Author:** Dr. Ömer Faruk Aydın  
**Date:** September 8, 2026  
**Domain:** High-Performance Architecture  

## AVX2 Implementation
- 256-bit wide registers: ymm0 - ymm15
- 8-wide single precision FMA3: _mm256_fmadd_ps
- Loop unrolling and software pipelining reaching high theoretical roofline throughput.
