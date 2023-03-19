# Current_Protection
The project is about current projection for a system that does not known. 

Firstly, I desccripted the problem on the system. Then, I searched and found this solving. 
The problem is that the system shuts down before a problem occurs due to high current in the system.
Secondly, I have identified the appropriate components. The main components are current transformer and OpAMP.

In the solution of this problem, we first provide isolation from our circuit with the voltage follower with the signal coming from the current transformer. 
Then, with the ongoing signal, we ensure that the system works with a comparator opamp with the appropriate output according to the voltage level we want.
