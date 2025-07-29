2025-07-21 07:56

Status: [[Adult]]

Tags: [[Linux]] [[Memory]]

## Memory Utilisation

Memory usage is the amount of RAM utilised by various processes.
In Linux it is stored in a file " __/proc/meminfo__ ''

- Total used memory = `MemTotal` - `MemFree`
- Non cache/buffer memory (green) = Total used memory - (Buffers + Cached memory)
- Buffers (blue) = `Buffers`
- Cached memory (yellow) = `Cached` + `SReclaimable` - `Shmem`
- Swap = `SwapTotal` - `SwapFree`


## References

1. [htop author stackoverflow answer on calculation of Memory usage](https://stackoverflow.com/a/41251290)


---

