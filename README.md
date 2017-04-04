# AD9851
Arduino+AD9851 DDS LCR Meter/ Function Gen/ VFO

First objective: measure inductence with minium components.
Solution: Use Arduino with rotary encoder and OLED screen to countrol AD9851 DDS module and genetrate a frequency swip. Read the envelope value directly off arduino ADC. Read 10 times and get the average. Find the highest value related to the current frequency and caculate inductance.

In later developments, I will limit the upper and lower limits of the frequency swip. After the first swip, do another smaller swip around the high point to get more precition.

In later later developments, I will somehow make it easier to change the capacitor in the tank circuit. Add an op amp or external ADC. Improve the interfance.
