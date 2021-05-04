# Mini-Robot
Our robot will be moving around the village. There are parcels in various places, each addressed to some other place. 
The robot picks up parcels when it comes to them and delivers them when it arrives at their destinations.


The automaton must decide, at each point, where to go next. It has finished its task when all parcels have been 
delivered.

To be able to simulate this process, we must define a virtual world that can describe it. This model tells us where 
the robot is and where the parcels are. When the robot has decided to move somewhere, we need to update the model to 
reflect the new situation.

Since it's my first project in JavaScript I won't use so many classes because such programs are often hard to understand 
and thus easy to break.
