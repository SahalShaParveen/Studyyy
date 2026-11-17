astable oscillator.

Astable : Doesn't settle in one state

Continously switches between HIGH and LOW, without manual triggering. 
Provides the "Rhythm".

| 555 Pin | Connection                       |
| :-----: | -------------------------------- |
|    1    | Ground                           |
|    2    | Connected to pin 6               |
|    3    | Output to trigger the second 555 |
|    4    | +5V                              |
|    5    | 10 nF capacitor to ground        |
|    6    | Connected to pin 2               |
|    7    | Between R1 and R2                |
|    8    | +5V                              |
- R1 (10 kΩ): +5V to pin 7.
- R2 (140 kΩ): pin 7 to pins 2 and 6.
- C1 (0.1 µF): pins 2/6 to ground.