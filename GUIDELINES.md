- Do not use `for .. of` loops.
- Isolate runtime type checks to src/api code for maintenance/performance sake. Static types should cover everything else.