# ***Designing-a-Two-Stage-CMOS-operational-amplifier:***

----------
### *Abstract*:

----------



we have designed a Two Stage CMOS operational amplifier which operates at 3.3V power supply using the BSIM device models
of a representative 180nm CMOS technology. The OPAMP designed is a two-stage CMOS OPAMP to exhibit a unity gain frequency
of 50MHz and exhibits a gain of 120dB.

Simulation results are verified using LTSpice.

-------------
### *Specifications*:

-------------

- Gain: 106
- Bandwidth : 50 MHz
- Maximum Output Swing : Vdd/4
- Slew Rate: 1 V/μs
- Power Supply: 8 mW
- Vdd: 3.3 V

-------------
### *Introduction*:

-------------

Over the last few years, the electronics industry has exploded. The largest segment of total worldwide sales is dominated 
by MOS market. Operational Amplifier is the most common building blocks of most of the electronics system. 
In this project we have designed a two stage opamp in LTSpice with the above given parameters

-------------
### *Working*:

-------------

From the slew rate we have got the value of current in the nmos which gives current to the First stage differential amplifier.
Then, we have assumed a decent value of CC and designed the values of (W/L) ratios of all the mosfets by phase margin, 
decent Input Common Mode Range. Finally for the second stage, we have designed the values of (W/L) ratios of the mosfets
from the current mirrors and a decent phase margin.


-------------
### *Conclusion*:

-------------

We have obtained the following results :
Gain:105.5
Power consumption:4.4mW
Slew rate:1 V/μs

-------------
### *Usage*:

-------------
Run main.asc file in LT Spice to get resulting graph.
This project is edited using LT Spice schematic interface and simulated in LT Spice.



