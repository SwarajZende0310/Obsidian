2025-07-23 13:56

Status: [[Adult]]

Tags: [[Library]] [[C++]]

## Dynamic Library

A **dynamic library** (also called a **shared library**) is loaded by a program **at runtime**, not at compile time.  
The executable **contains references** to the `.so` file, which is shared among multiple programs.

- Linked **at runtime**
- Code is **not copied** into the executable
- Multiple programs can use the same `.so` in memory

#### Pros:
- Smaller executables
- Easy to update libraries without recompiling apps
- Reduces memory usage when used by multiple apps simultaneously

#### Cons:
- `.so` must be present at runtime (or app fails to start)
- Slight overhead for dynamic symbol resolution at startup

## References
1. [Difference Between Static and Dynamic Library](https://stackoverflow.com/questions/2649334/difference-between-static-and-shared-libraries)



---

