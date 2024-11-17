# EX NO.6: Design-Implementation-of-2-Bit-Multiplier-using-Cadence-Tools
## Aim:
To design and implement a 2-bit multiplier circuit using Cadence EDA tools, simulate its functionality, and to understand its application in digital arithmetic operations.
## Tools Required:
*	Personal Computer
*	Cadence Virtuoso Software
## S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence
1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
## Procedure for Schematic simulation using Cadence
1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window (CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre
### i)	Procedure for Creating New Library.
*	File –New – Library
*	Name: Give name for ur library Ex: VLSILAB_EXP_1
*	Enable Attach to an existing technology library, Click OK
*	Attach the library to the technology library gpdk045.Click OK
### ii)	Create Schematic Cell view.
*	Go to 1st window i.e virtuoso (CIW)
*	File-New-Cell view
*	Setup the new file form
 -	Library: Select the one you created.
 -	Cell: Give the experiment name Ex: Inverter ViewSchematic
 -	Type: Schematic press OK
•	Add the required components from the libraries and make the connections.
 -	Go to instance fixed menu or use shortcut key “I” from keypad to go instances
 -	Click on browse. This opens the library browser
 -	Now select the appropriate library for components like 
 -	Gpdk45 ------------------------nmos1v, pmos1v
 -	Create Input and Output pins
 -	Make the connections by using fixed narrow wire key
 -	Click Check and Save button
![image](https://github.com/user-attachments/assets/7265612c-1281-41ee-9723-ab4bb43af475)
### iii)	Creating the Symbol for schematic Cell view
*	In the schematic window, execute 
 -	Create – Cell view – From Cell view
 -	The cell view from cell view window appears
 -	Check Lib Name, Cell Name, From View name must be schematic Press ok
*	Now Symbol generation form appears. Click Ok If No changes required
*	A new window with with default symbol is created.
*	Edit the symbol if you want to give actual symbol shape else continue.
*	Execute Create-Cell view-from cell view
*	Library Name and Cell Name must be same which you have used for schematic. Press OK
*	Check for the position of pin side.Prss OK
*	Edit for the shape by Create-Shape-Choose required options to edit.
![image](https://github.com/user-attachments/assets/472885a6-fb6a-49e0-a476-25aab10a3b58)
### iv)	Creating the new test cell view
*	Go to CIW window, Execute File-New-Cell view
 -	Setup the new file form
 -	Library: Select the one you created.
 -	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
 -	View: Schematic
 -	Type: Schematic press OK
*Follow the step 3(ii) d to make the required connections
![image](https://github.com/user-attachments/assets/c3d50e11-5bf2-4595-aa33-965f2f3df674)
## Analog simulation by SPECTRE.
*	In test cell view window
*	Launch – ADE L(Analog Design Environment)
 -	Execute Setup—Simulation/directory/Host A new window opens
 -	Set the simulation window to spectre and click ok
 -	Execute Analysis – Choose. A window opens.
 -	Select the type and set the specifications and press OK
 -	Execute Output s—to be plotted – Select on Schematic
 -	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
*	Execute Simulation -- Net list and Run
![image](https://github.com/user-attachments/assets/252da2c7-e3e0-4114-ba07-500860aeb39b)
## For Transient Analysis Settings and Output
![image](https://github.com/user-attachments/assets/0b89dfcb-b2de-49f9-961f-8cd2bd1862e3)
![image](https://github.com/user-attachments/assets/b8b29c47-a732-4f27-b9cf-df9fbabff36a)
## Results:
The design and implementation of the 2-bit multiplier using Cadence EDA tools were successfully carried out. The simulation results confirmed the correct operation of the multiplier for all input combinations. 
