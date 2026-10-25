# AST Static Auditor & Resource-Bounded Execution Sandbox

**Author:** Dr. Ömer Faruk Aydın  
**Date:** October 25, 2026  
**Domain:** Systems Security & Safe AI  

## Defense-in-Depth Enforcement
1. **AST Whitelist Inspection:** Banning eval, exec, os.system, subprocess calls.
2. **POSIX Resource Limits:** RLIMIT_CPU capped at 10s, RLIMIT_AS capped at 256MB.
3. **Restricted Workspaces:** Isolated scratch directory per execution task.
