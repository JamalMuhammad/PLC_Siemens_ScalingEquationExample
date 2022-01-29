# PLC_Siemens_ScalingEquationExample
PLC_Siemens Scaling Equation Example. 
This is an example program in ST simply showing a use cae of scaling equation. There are in total 4 valves in the system. Valve 1,2 an 3 are of Type A001 and valve 4 is of type A002. 
There is an HMI developed with simulation functions to test the code. Run the HMI in simulation mode, then run the PLC program in simulation mode. On the HMI screen
there is a dropdown list which enables user to select a valve. Select one valve out of 4 within the dropdown list. Then move the curson of the fields: "PV" and "Temperature". 
Observe the graph which is showing scaling function output. Check if the following criteria's met or not.  

Valve 1001 (Type A001):

input in between min 0 - max 27648 

scaled output needs to be in between min 0% - max 80%

Valve 1002 (Type A001):

input in between min 0 - max 27648 

scaled output needs to be in between min 0% - max 70%

Valve 1003 (Type A002):

input in between min 0 - max 32000 

scaled output needs to be in between min 0% - max 90%

when temperature > 69 deg Cen. then OUT_VAL:=100% 

Valve 1004 (Type A001):

input in between min 0 - max 27648 

scaled output needs to be in between min 0% - max 60%
