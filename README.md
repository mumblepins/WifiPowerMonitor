# Particle power monitor

Uses the [Particle](http://particle.io) Photon by default, but probably would work with a Core or one of the other Particle type devices.

Interfaces with a ST STPM34 ADC power-monitoring front-end and is designed for 2 CTs and 2 voltage inputs.  Resistors are sized in general for a 100A → 50mA current transformer, and 120V (US) voltage source.  Unlike the [OpenEnergyMonitor](https://openenergymonitor.org/emon/), we're using a seperate 24-bit ADC, and no voltage transformer. 


###License
#### Hardware
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
