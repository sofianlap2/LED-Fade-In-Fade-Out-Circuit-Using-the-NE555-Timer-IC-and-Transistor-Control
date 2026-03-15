# LED-Fade-In-Fade-Out-Circuit-Using-the-NE555-Timer-IC-and-Transistor-Control
LED Fade In – Fade Out Circuit Using the NE555 Timer IC and Transistor Control
This circuit creates a smooth LED fade-in and fade-out effect using a NE555 Timer IC combined with an NPN transistor amplifier stage.

The 555 timer generates a signal that gradually charges and discharges the capacitor C2 (100 µF) through R2 (10 kΩ). The voltage across this capacitor changes slowly over time, producing a varying control voltage that drives the base of transistor Q1.

As the capacitor charges, the voltage at the transistor base increases progressively. This causes Q1 to conduct more current, allowing the LED current to increase gradually. As a result, the LED brightness slowly increases (fade-in effect).

When the capacitor discharges, the base voltage decreases, reducing the transistor conduction. Consequently, the LED current decreases smoothly and the LED fades out.

