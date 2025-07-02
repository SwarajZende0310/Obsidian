2025-07-01 11:47

Status: [[Adult]]

Tags:[[Communication]] [[PC_PLC_communication]]

## Modbus Communication

MODBUS Protocol is a messaging structure, widely used to establish master-slave communication. A MODBUS message sent from a master to a slave contains the address of the slave, the 'command' (e.g. 'read register' or 'write register'), the data, and a check sum (LRC or CRC).  
It is independent of the underlying physical layer. 

***The Request***
The function code in the request tells the addressed slave device what kind of action to perform. The data bytes contains any additional information that the slave will need to perform the function.

***The Response***
If the slave makes a normal response, the function code in the response is an echo of the function code in the request. 
##### Transmission Modes
1. ASCII mode
	1. The main advantage of this mode is that it allows time intervals of up to one second to occur between characters without causing an error.
2. RTU mode
	1. The main advantage of this mode is that its greater character density allows better data throughput than ASCII for the same baud rate. 
	2. Each message must be transmitted in a continuous stream.
	
## References
1. [[https://www.modbus.org/docs/PI_MBUS_300.pdf]]
2. https://www.modbustools.com/modbus.html



---

