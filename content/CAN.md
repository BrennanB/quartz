A Controller Area Network more commonly known as CAN bus, is a communication Protocol used in many devices in the 21st century. A CAN bus connects a unlimited number of devices by 2 wires. The wires are generally coloured Green and Yellow. Yellow represents the High signal, while Green represents the Low signal. The secret to have so many devices connected on the same network is the baud rate and bit construction. 

## FRC Usage
In [[FRC]], CAN is one option for actuator control. Most devices such as motors and sensors have the option to connect to the CAN bus. The #RoboRio is the "head" of the network and will output/input all commands to change the operation of the robot. 

## Network Setup
For a network to function properly, there must be 120Ω resistor at every end of the network. Most devices in that are [[FRC]] legal already have the resistor inside them, such as ( #RoboRio ,[[Falcon 500]], #PDH ). This simplifies the wiring for those who are assembling the system. In the [[FRC Control System]], there are some rules for the CAN network. The CAN network must be terminated at the #RoboRio and the other end at the #PDH or #PDP . There is an exception if [[Pneumatics]] are being used (insert alternate description here). All other devices much be in between the two terminations. 

### Network Types
There are various different ways to setup a CAN bus. There are topologies that can be used that offer different advantages. 

Star
Ring
Line/Bus