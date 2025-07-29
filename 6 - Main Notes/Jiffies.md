2025-07-04 12:09

Status: [[Adult]]

Tags:[[Linux]] [[OS]]

## Jiffies

The global variable “jiffies” holds the number of ticks that have occurred since the system booted. On boot, the kernel initializes the variable to zero, and it is incremented by one during each timer interrupt. 

Thus, because there are HZ timer interrupts in a second, there are HZ jiffies in a second. The system uptime is therefore jiffies/HZ seconds.

#### Background

Events called at periodic interval are implemented using [[system timer]].

Because the kernel knows the pre programmed tick rate, it knows the time between any two successive timer interrupts. This period is called a **_tick_** and **equals _one-over-the-tick-rate_ seconds**. This is how the kernel keeps track of both [[Wall TIme]] and system [[Uptime]].



## References

1. https://www.linkedin.com/pulse/linux-kernel-system-timer-jiffies-mohamed-yasser/


---

