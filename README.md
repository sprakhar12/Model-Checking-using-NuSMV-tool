# ModelChecking

Concentration - Software Engineering

Team Members - 3

**A traffic light control system**

Tool - **NuSMV** to verify that a small software system and satisfies certain desired properties specified in LTL (Linear Temporal Logic).

Model checking of Traffic lights control system at an intersection of 2 way street running north and south intersects a 2-way street running east and west using NuSMV tool.

The goals are to design the system so that collisions are avoided and no traffic waits at a red light forever. There are four sensors for detecting whether cars are approaching the intersection from the four directions.

• at_n: cars approach the intersection from the north, ready to enter the intersection

• at_s: cars approach the intersection from the south, ready to enter the intersection

• at_w: cars approach the intersection from the west, ready to enter the intersection

• at_e: cars approach the intersection from the east, ready to enter the intersection,

The traffic-light control system generates four outputs with Boolean values that indicate whether a green light should be given to traffic in each of the four respective directions.

• n_light green light for traffic from the north

• s_light green light for traffic from the south

• w_light green light for traffic from the west

• e_light green light for traffic from the east

**Minimum Conditions met-**

1. Cars from any direction will eventually be given green lights
2. The lights in cross directions are never green at same time

