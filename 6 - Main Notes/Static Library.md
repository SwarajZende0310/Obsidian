2025-07-23 13:50

Status: [[Adult]]

Tags: [[Library]] [[C++]]

## Static Library

A **static library** is a collection of compiled object files (`.o`) bundled into a single archive file with extension `.a` (on Linux).  
When a program is linked with a static library, the library’s code is **copied into the final executable** at **compile/link time**.

- Linked **at compile time**
- Code becomes part of the executable
- No dependency on external files at runtime
#### Pros:
- No need to distribute external `.so` files
- Better portability for single-file deployment
- No runtime linking overhead

#### Cons:
- Larger executable (code is duplicated)
- Updating the library requires **recompiling all dependent executables**
## References

1. [Difference Between Static and Dynamic Library](https://stackoverflow.com/questions/2649334/difference-between-static-and-shared-libraries)


---

