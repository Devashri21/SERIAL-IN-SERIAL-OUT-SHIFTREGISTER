**NAME: DEVASHRI.S**

**REF NO: 24001806**

# EXPERIMENT NO: 6 SERIAL IN SERIAL OUT SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram. 

**PROGRAM**

![Screenshot 2024-12-25 192629](https://github.com/user-attachments/assets/7847d0d9-c836-451a-916a-89cbf1e2f88f)



**RTL LOGIC FOR SISO Shift Register**

![Screenshot 2024-12-25 192638](https://github.com/user-attachments/assets/145d6e34-96d2-4703-acfc-661eb6f1b61f)


**TIMING DIGRAMS FOR SISO Shift Register**

![Screenshot 2024-12-25 192647](https://github.com/user-attachments/assets/ebfd0462-dc24-4628-9562-950246db4ab4)

**RESULTS**

The given Program for flipflops and verify its truth table in quartus using Verilog programming.
