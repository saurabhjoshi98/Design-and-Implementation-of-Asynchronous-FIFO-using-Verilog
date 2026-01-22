# Design_and_Implementation_of_Asynchronous_FIFO_using_Verilog
* Designed and implemented a parameterized asynchronous FIFO supporting independent read and write clock domains.
* Applied Gray-code pointer technique with dual-flop synchronizers to safely handle clock domain crossing (CDC).
* Implemented robust full and empty flag generation using synchronized pointer comparison.
* Developed separate read and write logic ensuring correct FIFO ordering and data integrity.
* Verified functionality using a self-driven testbench with asynchronous clocks and edge-case scenarios.
* Ensured synthesizable, modular RTL suitable for high-speed SoC and inter-clock data transfer applications.
