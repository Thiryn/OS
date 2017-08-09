* 16-bit real mode : During the boot process, the CPU emulates a 16-bit CPU to be compatible with older OS
    * This mode emulate the oldest CPU of the (intel) family : 8086
    * No notion of memory protection whatsoever
    * After compatibility mode enabled, require the CPU to switch to a safer mode (32/64 bits)
* n-bit mode : The CPU can handle n-bits instructions at most
* ISR : Interrupt Service Routing : Interrupt the system to run other routines
* Register :  for the 32 bit register `ax`, `ah` represents the 16 higher bits, `al` represents the 16 lowe bits
* Interrupt codes : [Wikipedia link](https://www.wikiwand.com/en/INT_10H)
