# CPP Performance and Hardware

This repository is some notes about performance and hardware.

## Notes

- Be conscious whether you're bound by data or computation
- Prefer data configuos in memory; If you can't, prefer constant strides (pattern) to randomness
- Keep data close together in space
- Keep accesses to same data close together in time
- Avoid dependencies between successive computations
- Avoid dependencies between two iterations of a loop
- Avoid hard-to-predict branches
- Be aware of cache lines & alignment
- Minimise nr. of cache lines accessed by multiple threads
- Don't be surprised by hardware weirdness (cache associativiy, denormals, ...)
