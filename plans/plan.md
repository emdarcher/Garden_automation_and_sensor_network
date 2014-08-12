
MAIN THINGS:
===========

    * Create wireless temperature guage for garden greenhouse, possibly measure humidity as well. Send data to central hub/station (Raspberry Pi probably).

    * Make a soil moisture measurement node?

    * Set up for two way communication between nodes, so the hub/station controller can send back commands to the nodes, enabling possible automation. 

    * Using two way comm, make the nodes activate only when asked to ( when they recieve a packet ), and then switch to PTX mode so they can return data to the hub, then they could switch back to PRX, awaiting another packet. In this case, the MSP430s could go into LPM4 and wake when an external interrupt is triggered by the nRF24L01+ module.

    * I could maybe add some contraption to allow controlled opening and closing of the greenhouse opening to let out air when temperatures are too hot within. 

    * Try to add solar power capability as much as possible, maybe use modified cheap solar garden lights. 


LESS LIKELY TO HAPPEN SOON:
--------------------------
	
    - remote or automatic irrigation ( could work together with soil moisture node)

    - something to keep bears from stealing peaches ( a very specific user case/request ) and other things from trees and gardens.
