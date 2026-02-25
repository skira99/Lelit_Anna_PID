The basic operating principle of a single boiler espresso machine is quite simple once you look into it a bit. The temperature of the boiler is controlled by two thermostats with fixed temperatures, one for brew water and one for steam. All electronics are powered by 120V AC so no complicated converting is required, and there are three switches that control how each component interacts. From top to bottom,

Switch 1: Power switch, controls whether the incoming current makes it to the rest of the components

Switch 2: Machine function with three positions, from top to bottom
-Top: steam, redirects the current to the steam thermostat
-Middle: Hot water, redirects current to the brew water thermostat
-Bottom: Brew, redirects the current to the brew water thermostat and connects the brew switch to the solenoid valve
Of note is that the heating element is also just powered by 120V AC; the current sent to the relevant thermostat is passed through the thermostat to the boiler as long as it reads a temperature below its set point, otherwise it cuts the connection and the heating element is disabled.

Switch 3: Pump switch, activates the pump which will push water into the boiler. If the function switch is in the bottom position, the solenoid valve will also receive current and open, allowing water to flow to the grouphead. Activating the pump when the function switch is in any other position will push new water into the boiler, but that water will not be able to reach the grouphead, and any extra pressure will dissipate through the overpressure valve back into the water tank.

Replacing the pump is quite straightforward, but installing the PID requires the following steps:
-Change the thermostat a thermocouple, which will be able to read the boiler temperature and relay the information to the PID controller
-Connect a solid state relay to the connections which used to go to the thermostat, so that the relay can power the heating element
-Connect a PID to power, the SSR, and the thermocouple
-Mount the whole thing to the machine
