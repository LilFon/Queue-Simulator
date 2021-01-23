# Queue_Simulator
I use Queueing theory to develop this simulator

How to run :

In the project folder you must create a folder call "Archivo"
You must use a txt format files in the program

Legend file : 

0        <----------- Time Unit /0 Minute /1 Hour /2 Day /3 week /4 month /5 year                                                                                                   
100800   <----------- Total time in the simulation
10000000 <----------- Clients allowed in the system
1 	<----------- Total servers
5	<----------- Server cost
2	<----------- Client wait cost
InicioLlegada					<----------- Arrival times tables
Lunes:[{1,0.5};{2,0.2};{3,0.2};{4,0.05};{5,0.05}]
Martes:[{4,0.1};{5,0.1};{7,0.3};{8,0.35};{9,0.15}]
Miercoles:[{4,0.15};{6,0.2};{8,0.45};{9,0.2}]
Jueves:[{4,0.1};{7,0.2};{9,0.35};{11,0.35}]
Viernes:[{1,0.5};{2,0.2};{3,0.2};{4,0.05};{5,0.05}]
FinLlegada
InicioServicio					<----------- Service times table
[{5,0.2};{7,0.3};{8,0.35};{9,0.15}]
FinServicio
1       <----------- Event table (yes:1 no:0)
1	<----------- Generate file (yes:1 no:0) 




