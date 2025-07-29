2025-07-04 12:14

Status: [[Adult]]

Tags:[[Linux]][[OS]]

## system timer

programmable piece of hardware that issues an interrupt at a fixed frequency.

Interrupt handler for this timer called the _timer interrupt_ updates the system time and performs periodic work.

system timer goes off (often called _hitting_ or _popping_) at a pre-programmed frequency, called the _tick rate_. When the system timer goes off, it issues an interrupt that the kernel handles via a special interrupt handler.

frequency of system timer is set on boot up and based on static preprocessor directive. The value of HZ differs for each supported architecture

The kernel defines the value in <asm/param.h>. The tick rate has a frequency of HZ hertz and a period of 1/HZ seconds.

## References

1. https://www.linkedin.com/pulse/linux-kernel-system-timer-jiffies-mohamed-yasser/


---

