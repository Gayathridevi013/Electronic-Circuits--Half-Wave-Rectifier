## AIM:
To simulate a half wave rectifier circuit and compare the outputs with and without filter:
## CIRCUIT DIAGRAM:
<img width="1599" height="1274" alt="image" src="https://github.com/user-attachments/assets/cf87e50d-4108-4344-bac2-8a1d9037ec12" />

## STEPS FOR SIMULATION:
1.	Open the Ltspice software
2.	
3.	FileNew Schematic
4.	
5.	Click component symbol  to browse and select the components
6.	
7.	Find the diode or diodes from the component list and place them.
8.	
9.	Click OK and place the component
10.	
11.	Search for resistor from component menu or from the tab icons
12.	
13.	Place the resistors
14.	
15.	Search for capacitor from the component menu or from the tab icons
16.	
17.	Place the capacitors
18.	
19.	Use ctrl + R to rotate the components
20.	
21.	Use wire symbol  to connect the components as per the circuit diagram
22.	
23.	Right click each components to give the values
24.	
25.	Use run button  to run the simulation
26.	
27.	Set the step time and click ok
28.	
29.	Output dialog box will open
30.	
31.	In the output dialog box right click and select add traces
32.	
33.	Node voltages and current of each components names will be displayed.
34.	
35.	Select the required node voltages (V(n001)) to get the waveforms.
36.
37.	To get the voltage across a component the name of the trace should represent both the nodes. example V(n001,n002))

## OUTPUT:
<img width="1599" height="1274" alt="image" src="https://github.com/user-attachments/assets/e7b50f09-d3f9-42b9-93cf-149c3113b4ae" />

<img width="1266" height="1600" alt="image" src="https://github.com/user-attachments/assets/54aea800-07af-4b00-a6ec-68d97ab0ee05" />

<img width="1003" height="1359" alt="image" src="https://github.com/user-attachments/assets/69ff3a7f-6540-4f51-87c3-6cdb51c9a3df" />

## RESULT:
The half wave rectifier circuit with and without filter were implemented and the output waveforms were obtained and the PIV were found to be
1.) With filter PIV = 3.8V
2.) Without filter PIV = 2.4V
