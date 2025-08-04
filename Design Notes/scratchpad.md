# Nixie Clock Design Notes

## Simulated Driver in LTSpice:
![nixie driver circuit](ltspice-sim.png)

[Simulation File](../simulations/Nixie%20Driver.asc)

## Calculations
### Pulse mode characteristics
![Pulse mode characteristics](./Screenshot%202025-08-03%20062218.png)


#### 2mA target
$$\frac{190V - 150V}{2mA}=20k\Omega$$
0.08W required power

Commas need 1mA
$$\frac{190V-150V}{1mA}=40k$$

So add another 20k on the comma cathode


## References
[Threeneuron's Pile o'Poo](https://threeneurons.wordpress.com/nixie-power-supply/) -VERY USEFUL

[IN-14 Datasheet](https://tubehobby.com/datasheets/in14.pdf)
