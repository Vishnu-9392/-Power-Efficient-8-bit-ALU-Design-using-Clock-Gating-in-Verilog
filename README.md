Power-Efficient-8-bit-ALU-Design-using-Clock-Gating-in-Verilog
This project implements an 8-bit Arithmetic Logic Unit (ALU) in Verilog using Xilinx Vivado. 
The design demonstrates power reduction techniques by comparing a normal ALU with a clock-gated ALU.
Normal ALU: Standard implementation without power optimization.

Clock-Gated ALU: Uses clock enable (CE) and operand isolation to reduce unnecessary switching activity, lowering dynamic power consumption.

8-bit ALU supporting operations:

Addition
Subtraction
AND, OR, XOR, NOT
Left Shift, Right Shift

Tools Used
Xilinx Vivado (WebPACK Edition)
Verilog HDL
ModelSim / Vivado Simulator for functional simulation

## 🔬 Simulation Results
### Normal ALU
![Normal ALU CODE](images/alu_8bit.png)


![Normal ALU TB CODE](images/alu_8bit_tb.png)


![Normal ALU WAVEFORM](images/alu_8_bit_op.png)

### Clock-Gated ALU

![Clock Gated ALU CODE](images/alu_8bit_clk.png)

![Clock Gated ALU TB CODE](images/alu_8bit_clk_tb.png)

![Clock Gated ALU Waveform](images/alu_8bit_clk_op.png)

## ⚡ Power Analysis
### Normal ALU Power Report
![Normal ALU Power](images/power_alu.png)

### Clock-Gated ALU Power Report
![Clock Gated ALU Power](images/power_alu_clk.png)
