# LastRabbit
easy soldering and desoldering kit of surface-mount components for a badge of rabbit

## components

![rabbit](https://github.com/ndGarage/LastRabbit/blob/main/rabbit-back.png)

The only chip is the dual-inverter, NL27WZ04DFT2G. It is tiny. From the top to look at the chip, it has a mark of M5-XY. "XY" is 90-degree rotated. The pin under M5 to the left is the pin1. On the PCB, the pin1 is marked by a white dot.

The cathode of LED has a mark of half-circle.

| component | note |
| --------- | ---- |
| C1, C2 | 1uF |
| R1, R4, R5, R6 | 510K |
| R2, R3 | 68ohm |
| U1 | NL27WZ04 |
| D1, D2 | LED, reverse mount |

![rabbit annotated](https://github.com/ndGarage/LastRabbit/blob/main/rabbit-annotated.png)

## circuit

The circult of LastRabbit is simple. Two inverter forms a oscillator. The details could be found in the application notes of NL27WZ04.
