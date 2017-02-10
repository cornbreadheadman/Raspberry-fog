# Raspberry-fog
<strong>Martin® Magnum Pro 2000 Fog Machine controlled by Raspberry Pi</strong>

There once was a broken fog machine. This fog machine was originally designed to provide a constant stream of fog forever. Or until the resivour of fog juice was depleted. It could no longer do the job. The heating circuitry could still heat the unit up to "Ready to Fog" conditions but could no longer engage the pump to provide juice through-put. This is where the idea of the Raspberry Pi came into play.

The unit was able to heat the unit up to "ready" and regulate the power to the heater. The unit would give a green led when ready to produce fog. This gave me a starting point. I assumed the sensor that detected temp. was a thermistor. I was incorrect. I then hoped it was a thermal fuse. I was incorrect. Atlas I found it to be (still not 100% sure) a therocouple. I have yet to work out the exact procedure in returning a temp. from sucha component. This task is in the TODOs for version 2.

This project makes use of a digital themometer, 6k Ohm resister, raspberry pi, 4 channel relay, Martin® Magnum Pro 2000
