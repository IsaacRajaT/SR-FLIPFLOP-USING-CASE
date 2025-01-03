# SR-FLIPFLOP-USING-CASE

**AIM:**

To implement  SR flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/0f710028-ad52-4d3e-9276-8714cf023a25)

 
This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dabfc4f4-87e3-4cbc-9472-f89ee1b5ed30)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dd90d16c-aec5-4290-a586-e2346b1e9eb5)

 
By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/473efad6-d70b-4ca7-aeb7-898bbfca319f)

 
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

**Procedure**


Open Quartus Prime and create a new Verilog project.

Write the Verilog code for the SR flip-flop.

Compile the design to check for syntax errors.

Generate the RTL schematic to visualize the flip-flop structure.

Create a testbench to simulate the behavior of the SR flip-flop.

Apply test cases for S and R inputs and observe the transitions in Q based on the characteristic table.

Generate the timing diagram to confirm correct timing behavior.

Validate the simulation results with the expected next state as per the truth table.
**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: T Isaac Raja  RegisterNumber: 24900178
*/

![image](https://github.com/user-attachments/assets/294f676d-be0b-4285-b430-577ba67ebcce)


**RTL LOGIC FOR FLIPFLOPS**

![image](https://github.com/user-attachments/assets/f9a8c6a4-3ef3-4ae4-a95b-c8ae586f7daa)


**TIMING DIGRAMS FOR FLIP FLOPS**

![image](https://github.com/user-attachments/assets/b141f5f1-2da3-4af8-a436-3419da52848b)


**RESULTS**

The SR flip-flop was successfully implemented in Verilog, and its functionality was validated using the truth table and timing diagrams. The output correctly responds to Set and Reset inputs as expected.
