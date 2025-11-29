# EE535-Implementation-of-Interrupt-controller-using-Verilog-HDL-Design-Source-Code

The given is the design source code used and tested on Vivado for the EE535 Course project.
The interrupt controller designed in this project is built entirely using a Finite State Machine (FSM) architecture. Its purpose is to serve as a programmable interrupt-handling unit that can operate in multiple modes—polling mode, priority-based servicing, and masking mode—depending on the commands issued by the processor. This FSM orchestrates the detection, transmission, acknowledgement, and completion of interrupt service requests, ensuring predictable and deterministic interrupt handling in a digital system.
The controller manages up to eight interrupt sources, supports run-time configurable priority levels, and communicates with a processor using a shared 8-bit bidirectional data bus, interrupt output line, and acknowledgement input.
