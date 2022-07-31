## Objectives
- Define a radial power system
- Identify generator reaction to a lower system voltage
- Identify the factors leading to a long-term voltage collaps
- Recognize the effects of a long-term voltage collapse
- Identify the factos leading to a transient voltage collapse
- Identify the effects of a transient voltage collapse
---
### **Define a radial power system**
![Radial Power System](/nerc/Reactive-Power/images/Radial-Power-System.png)

- All generation resources in one electrical area
    - Connected strictly to load in another elec area
    - Connected to load with no additional in-service interconnections
    - Load consumes real and reactive power
        - Connected to generation with several 345Kv interconnections
        - Transformed down to 138, 69, and 34, and 13 kv
    - Shunt capacitors added to load to compensate for load reactance
        - Closed with voltage relays, timers, operators etc.
- Generators
    - Gas, oil, and coal-fired steam
    - Nuclear-powered steam
    - Hydro
    - Gas Turbines
    - Others
- AVR
    - Automative Voltage Regulator 
    - Raises and lowers reactive power when voltage is too high or too low

#### ***P-V, Q-V curves and voltage collapse***
- Recall Reactive power loss = i<sup>2</sup> * X<sub>L</sub>
---
![P-V, Q-V curves and voltage collapse](/nerc/Reactive-Power/images/pv-qv-curves.png)
- Declining voltage causes power angle to increase
- Declining voltage causes reactive power to increase
- The knee of the curve is the point where the power angle and reactive power are equal
    - Extended by adding reactive power to the load using shunt capacitors
- Shunt capacitor banks when larger than the load
    - Shunt capacitors are added to the load to compensate for load reactance
    - Shunt capacitors are added to the generator to compensate for generator reactance
    - Shunt capacitors are added to the AVR to compensate for AVR reactance

### Generator Reaction to a Lower System Voltage
- Transformer supplies voltage from the generator to the AVR
- generator bus voltage decline makes AVR to increase DC current
