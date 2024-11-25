# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.
![Screenshot 2024-11-23 154314](https://github.com/user-attachments/assets/79c474ed-8ebe-49c8-b0ce-534bdab53952)

#### Synthesis RTL Schematic :
![Screenshot 2024-11-23 154322](https://github.com/user-attachments/assets/52b3b034-15d6-4fd0-8dce-e481072a9264)

#### Area report:
![Screenshot 2024-11-23 154330](https://github.com/user-attachments/assets/52571f5a-cd66-4d57-8cf6-a8036351f5c6)

#### Power Report:
![Screenshot 2024-11-23 154337](https://github.com/user-attachments/assets/8da51949-b5cb-46df-b9ee-450d523feb98)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
