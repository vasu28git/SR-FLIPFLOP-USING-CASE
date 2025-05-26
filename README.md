
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


1.Type the program in Quartus software.


2.Compile and run the program.


3.Generate the RTL schematic and save the logic diagram.


4.Create nodes for inputs and outputs to generate the timing diagram.


5.For different input combinations generate the timing diagram.


**PROGRAM**

Program for flipflops and verify its truth table in quartus using Verilog programming. 

Developed by: VASU VIGNESHWARAN P
RegisterNumber: 212224220119


![Screenshot 2024-12-09 132506](https://github.com/user-attachments/assets/7daa3bd1-37e9-4fef-9179-ae36e9805406)


**RTL LOGIC FOR FLIPFLOPS**


![Screenshot 2024-12-09 132640](https://github.com/user-attachments/assets/21f9bb4b-4119-473b-8965-79e3d1bb4542)


**TIMING DIGRAMS FOR FLIP FLOPS**


![Screenshot 2024-12-09 132755](https://github.com/user-attachments/assets/896c7183-87a0-4d1c-bfba-0877a6f4033a)



**RESULTS**


The observation of the simulation results and confirm the successful execution of the program.
