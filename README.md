# UART protocol in SystemVerilog HDL.
There are two fsm modules - tx and rx, which work independently.
The uart_top module brings these together, allowing synthesis for OMDAZZ fpga board.
By controlling parameters, one can tranceive any number of frames, on any frequency,
with any size of data in one frame.
