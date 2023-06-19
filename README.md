<h1>Low Temperatture Difference Sterling Engine</h1>


<h2>Description</h2>
The Virtual Implementation, Operation & Optimization of a 
Low-Temperature Difference Stirling Engine

This project aimed to fulfil the objectives outlined in the design brief by developing a low-temperature difference Stirling engine. The engine's primary purpose was to generate energy by harnessing waste heat from hot water. In order to achieve a successful outcome, the project emphasized cost-effectiveness, a favourable power-to-weight ratio, and the utilization of the university's 3D printing and laser-cutting capabilities.
<br />


<h2>Languages and Utilities Used</h2>

- <b>SolidWorks</b> 
- <b>Excel (Bill of Materials)</b>
- <b>Matlab</b>
- <b>Granta Edupack (Material Selection)</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Project walk-through:</h2>

The initial stages of the CDIO process involve estimating the key requirements of the design brief and generating initial concepts during the conceive stage. Following that, the design stage includes evaluating the proposed designs using sound engineering methodology to arrive at an optimal solution. In conclusion, an overview of the organizational process is presented, along with reflections on the team's learning experiences in engineering design.
</b>
<p align="center">
Mindmap of Cocieve Phase (CDIO): <br/>
<img src="https://i.imgur.com/Zv2rVXG.png" height="80%" width="80%" alt="Mind Map: Conceptualising the Stirling Engine"/>
<br />
<br />
Design Phase (CDIO):  <br/>

 On commencing with the design stage, we made two key realisations: 
1.	The four-piston gamma configuration significantly limited our available surface area for heat dissipation 
2.	That the beta rhombic drive was unsuitable for vertical operation 
After another brief brainstorming session, we made the decision to analyse a single piston gamma configuration. This configuration posed several benefits namely:
1.	Reduced complexity 
2.	Lower weight 
3.	Larger surface area for heat dissipation

Below, the output of our code for both the single and dual piston configurations can be seen. It should also be noted that peak torque occurs at the lowest modelled RPM this is because the code created will produce an asymptote at 0 rotational velocities, ie infinite energy transfer time when the engine is not moving.

**Single Piston Gamma**<br/>
we can see that peak power output of approximately 1.75 W occurs at ~ 611.2 RPM at which point torque in the crankshaft will be approximately 0.028 Nm.<br/>


<p align="center">
Torque vs Engine Speed Single Piston Gamma: <br/>
 
<img src="https://i.imgur.com/Jen7sB1.png" height="80%" width="80%" alt="Mind Map: Conceptualising the Stirling Engine"/>
<br />
<p align="center">
Power vs Engine Speed Single Piston Gamma: <br/>
 
<img src="https://i.imgur.com/z6Hxg5H.png" height="80%" width="80%" alt="Mind Map: Conceptualising the Stirling Engine"/>

**Dual Piston Gamma**<br/>
we can see that peak power output of approximately 3.51 W occurs at ~ 611.2 RPM at which point torque in the crankshaft will be approximately 0.0548 Nm.

<p align="center">
Torque vs Engine Speed Dual Piston Gamma: <br/>
<img src="https://i.imgur.com/OggqWNQ.png" height="80%" width="80%" alt="Mind Map: Conceptualising the Stirling Engine"/>
<br />
<p align="center">
Power vs Engine Speed Dual Piston Gamma: <br/>
<img src="https://i.imgur.com/lLoE1W8.png" height="80%" width="80%" alt="Mind Map: Conceptualising the Stirling Engine"/>
<br/>
 
**Proposed solution – Single Piston Gamma Configuration with a printed heat exchanger** <br/>
The optimal solution was the gamma engine with a single piston. This was chosen after conducting a weighted matrix. It was cheaper to produce and weighed less than the other designs. Additional parameters were also taken into consideration when selecting the optimal solution which included ease of manufacturing, maintenance, and implementation. Overall, the Gamma with one piston was deemed to be the best design.

<p align="center">
<img src="https://i.imgur.com/Lijl7Nv.png" height="80%" width="80%" alt="Mind Map: Conceptualising the Stirling Engine"/>
<br/>
<br />
<br />
</p>


