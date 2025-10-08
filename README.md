# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**
A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

image

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next. Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**
Open Quartus and create a new Verilog file.
Copy and paste the corrected code and save the file.
Compile the program to check for errors.
Generate the RTL schematic and timing diagram.
Simulate the design to verify the serial shift operation.

/* write all the steps invloved */

**PROGRAM**
<img width="355" height="275" alt="Screenshot 2025-10-08 190946" src="https://github.com/user-attachments/assets/536be129-d630-4ae6-b252-f39c91fe0d86" />

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:J.Ivan Abishek Benhananan

25006144

*/

**RTL LOGIC FOR SISO Shift Register**
<img width="1787" height="900" alt="Screenshot 2025-10-08 190903" src="https://github.com/user-attachments/assets/068efbb5-eed8-45e2-9ebf-f1824e9d064a" />


**TIMING DIGRAMS FOR SISO Shift Register**
<img width="1037" height="558" alt="Screenshot 2025-10-08 191636" src="https://github.com/user-attachments/assets/695d347a-ed3d-4752-885a-d0800c1361ee" />


**RESULTS**
Thus the Serial-In Serial-Out shift register is implemented and verified.
