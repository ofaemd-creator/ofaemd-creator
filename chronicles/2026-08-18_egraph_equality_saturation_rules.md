# E-Graph Equality Saturation Rewriting Engine

**Author:** Dr. Ömer Faruk Aydın  
**Date:** August 18, 2026  
**Domain:** Compiler Optimization  

## Rewriting Axioms
E-Class congruence closure ensures expressions maintain semantic equivalence without phase ordering hazards:
- Associativity: (a + b) + c == a + (b + c)
- Distributivity: a * (b + c) == a * b + a * c
- FMA fusion: (a * b) + c == fma(a, b, c)
