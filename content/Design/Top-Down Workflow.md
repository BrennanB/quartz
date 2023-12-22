For those who have used SolidWorks before, you'll have created parts individually, then used mates to create an assembly of parts. This is called the **bottom-up approach** where the dimensions of the parts are defined individually, so changing the geometry of parts once the assembly has been built can be a challenging and time consuming process. 

Alternatively, SolidWorks also supports use of a **top-down approach** where parts are defined in relation to each other. The workflow goes roughly as follows:

1. Create a part file containing only a layout sketch
2. When creating parts of an assembly, insert the layout sketch part before creating any geometry so that you can base your parts off the sketch
3. Insert custom parts into an assembly (very few mates are required)
4. Insert COTS parts into the assembly
5. Edit the layout sketch whenever geometry needs to be changed, and watch the parts and assembly update accordingly

Now, a deeper dive into each step:

## Layout Sketch Part

![[Pasted image 20231222004902.png]]

The layout sketch dictates all crucial geometry of a subsystem. Examples of things to sketch out at each stage are as follows:

1. Define requirements of the system
	- Chassis
	- Extension limits
	- Pickup and scoring locations
	- Climbing bar height
2. Define desired geometry
	- Location of rollers on an intake
	- Shooter wheel location, hood compression on a shooter
	- Arm length and pivot locations on an arm
3. Define connecting geometry
	- Connecting bars on an intake
	- Structural extrusion/plates on a conveyor
4. Define powering mechanisms
	- Gearboxes
	- Belt an chain systems