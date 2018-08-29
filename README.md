# Traffic_Light_Controller_using_Microcontroller_89C51

Traffic signals are used to control the flow of vehicles. In the recent years, the need of transportation has gain immense importance for logistics as well as for common human. This has given rise to the number of vehicles on the road. Due to this reason, traffic jams and road accidents are a common sight in any busy city. Traffic Signals provide an easy, cheap, automatic and justified solution to the road points where the vehicles may turn to other directions e.g. roundabouts, culverts, busy walk through etc.

The project we have chosen is an 4-way traffic controller. The basic idea behind the design is to avoid the collision of vehicles by providing appropriate signals to different directions for a limited time slot, after which the next waiting drivers will be given same treatment. In this way a cycle will be established which will control the traffic. 

The control signals are 3-lights. Top light is Red(Stop), Middle light is Yellow(Wait) Bottom light is Green(Go). 

We used 89C51 microcontroller for this operation. In this project, we connect 4 7-seg LED display at port 2 of microcontroller and these are controlled by port 0. At port 0 we use pull up transistor. Port 1 &amp; Port 3 of microcontroller are used for signal indication.
