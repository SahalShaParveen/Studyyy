Generates a pulse of adjustable duration whenever the first timer triggers it. 

| 555 Pin | Connection                                        |
| :------ | :------------------------------------------------ |
| 1       | Ground                                            |
| 2       | Trigger input from Timer 1 pin 3                  |
| 3       | Servo signal output                               |
| 4       | +5 V                                              |
| 5       | Adjustable control voltage from the potentiometer |
| 6       | Timing capacitor connection                       |
| 7       | Discharge/timing resistor connection              |
| 8       | +5 V                                              |
R3 : Between +5 V and the junction of pins 6 and 7

C2 (0.1 µF) : Between the pins 6/7 junction and ground

10 kΩ potentiometer : One outer terminal to +5 V, the other outer terminal to ground, and the middle terminal (wiper) to pin 5