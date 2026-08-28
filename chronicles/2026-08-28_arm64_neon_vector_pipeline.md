# ARM64 NEON Vector Code Generator

**Author:** Dr. Ömer Faruk Aydın  
**Date:** August 28, 2026  
**Domain:** High-Performance Architecture  

## Vector Register Mapping
- Quadword floating-point registers: v0.4s - v31.4s
- Vector multiply-accumulate: fmla v0.4s, v1.4s, v2.4s
- Vector min/max saturation: fmaxnm v0.4s, v1.4s, v2.4s
