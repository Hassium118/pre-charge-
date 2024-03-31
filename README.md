# pre-charge-
This page will be a documentation of all the steps and drafts completed to design the pre-charge circuit. 

**Main Function of pre-charge circuit**
The purpose of this circuit is to limit the inrush current that goes into the inverter. To put it simply, the basic configuration of a pre-charge circuit is a high powered resistor and a relay in series. 

**Things to consider when designing**
The time to charge the capacitor located in the inverter should be relatively small. 
The choice of using the BMS, the inverter itself, or hardwired electronics for the control circuit is entirely up to the designer and should be in accordance to the formula student rulebook. 

In my case, the use of programmable logic was not permitted, so using something like an arduino was not suitable. Also, the "intermediate voltage has to be measured", so the simpler timer-based approach was risky to pursue. I then resulted in going for a comparator-based approach. 
