# Diode Model Comparison – Ideal vs Real Diode

## Overview
In this assignment, the same diode circuit was analyzed in LTspice using two different diode models:
1. An ideal diode model
2. A practical (real) diode model using the 1N4148 diode

The circuit consists of a DC voltage source, a 1 kΩ resistor, and a diode connected in series to ground. A DC sweep was performed on the voltage source in both cases to obtain the diode I–V characteristics.

## Difference in Turn-On Voltage
The ideal diode turns on immediately when the voltage becomes positive. In the simulation, this means the diode starts conducting with almost zero forward voltage.  
In contrast, the real diode (1N4148) requires a forward voltage of approximately 0.6–0.7 V before significant current begins to flow. This behavior matches real physical diodes and is clearly visible in the I–V plot.

## Difference in Current Behavior
For the ideal diode, the current increases very sharply once the diode is forward biased, limited mainly by the series resistor. There is no gradual transition region.  
For the real diode, the current increases more gradually due to the diode’s internal characteristics, such as the junction potential and internal resistance.

## Why Ideal Models Are Still Used
Ideal diode models are useful because they simplify circuit analysis. They are helpful for learning basic concepts, doing quick calculations, and understanding overall circuit behavior without complex details.

## When Ideal Models Become Inaccurate
Ideal models become inaccurate when precise voltage drops, power dissipation, temperature effects, or high-speed behavior are important. In real electronic designs, practical diode models must be used to obtain accurate and reliable results.
