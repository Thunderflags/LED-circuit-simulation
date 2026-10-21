# LED-circuit-simulation REPORT

# Investigating the Effect of Resistance on LED Current

# 1. Aim

To investigate how changing resistance affects the current in a simple LED-circuit while keeping the supply voltage constant.

# 2. Tools

- Falstad Circuit Simulator
- Mac computer and web browser
- Basic electrical theory and Ohm's law

# 3. Theory

Ohm's law states that V = IR for an ohmic resistor.

In a series LED circuit, the approximate current can be estimated using:

I ≈ (V[supply] - V[LED]) / R 
Assuming V[LED]=2V

Increasing resistance should reduce the current, provided the other circuit conditions remain unchanged.

# 4. Circuit

Supply voltage: 5 V DC

Components: DC voltage source, resistor, LED and connecting wires.

Circuit screenshot: images/led-circuit.png

Simulation link: [Falsted simulation](https://www.falstad.com/s.py?s=LhRh49)
# 5. Method

1. Created a series circuit containing a DC source, resistor and LED.
2. Set the supply voltage to 5 V.
3. Recorded the simulated current with a 220 ohm resistor.
4. Repeated the test using 470 ohms and 1,000 ohms.
5. Compared the observed values with theoretical estimates.

## 6. Results

| Resistance | Simulated current | Theoretical estimate |
|---|---|---|
| 220 ohms | 14.5mA | About 13.6 mA |
| 470 ohms | 6.9mA | About 6.4 mA |
| 1,000 ohms | 3.3mA | About 3.0 mA |

The theoretical estimates assume an LED forward voltage of approximately 2 V as mentioned above. Actual simulator values may differ.

## 7. Discussion

Through the experiment when i changed resistance 220Ohm and observed the current with theoretically obtained one i can see variations such as 14.5 and 13.6mA,
where the difference is almost 0.9mA.While increasing the resistance as such to 470Ohm and 1000Ohm i can see this difference in current between theoretical and 
simulated reduce as such to0.5mA and 0.3 mA.
The absolute difference between the theoretical and simulated currents also became smaller in my observations as the resistance increased. One possible explanation 
is that the simplified calculation does not perfectly represent the LED's nonlinear voltage-current relationship or graph. However, this trend is not 
guaranteed for every LED model or circuit; it should be treated as an observation from this particular experiment rather than a universal rule.


## 8. Conclusion

The experiment demonstrated that increasing the resistance in a series LED circuit reduces the current when the supply voltage remains constant. 
The simulated results generally agreed with the theoretical prediction, although small differences were observed because the theoretical calculation 
used an approximate LED forward voltage.This investigation helped me understand how resistance controls current and why theoretical calculations 
may differ from circuit simulations.

## 9. Limitations

This experiment used a simulation rather than physical components.
Results depend on the LED model and the assumptions used in the calculations.

## 10. What I learned

Through this experiment, I learned how voltage, resistance and current are related in a simple electrical circuit. 
I applied Ohm's law to estimate the current and compared these calculations with simulated measurements.

I also learned that an LED does not behave exactly like a simple fixed resistor, so its forward voltage must be considered when estimating circuit current. 
Finally, I gained experience using a circuit simulator to investigate an electrical concept, record observations and explain differences between theoretical 
and simulated results.
