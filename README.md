# Zeus


#Inspiration
We thought of designing a Power Supply Unit (aka PSU) for our high-watt RGB LED setup to work. It was a set of addressable LEDs and by calculating theoretically it was supposed to consume 9 Amps at 5V a total Power of 45 Watts. But unfortunately, we didn't have such a high-watt power source, also at 5V. 

# What it does
It is a High Watt Power Supply Unit rated 60W, 5V output at a max current draw of 12 Amps, and that too in a small form factor.

# How we built it
First, we tinkered with TI’s Webench Power Supply Design and found some really decent designs, as a perfect match for our requirements. After a while, by getting a balanced result from all ways, i.e a small size, high current draw (12A) ample to source our LEDs, high efficiency; we started making the schematic in EasyEDA. Next, we designed the PCB and rechecked every connection thoroughly. 

**Main Components Used**
- Bridge Rectifier
- Coupled Transformer
- CV CC UCC28740 flyback controller by TI
- UCC24630 Synchronous Rectifier Controller by TI
- Optocouplers
- Power Mosfets
- TL431 adjustable Zener
- Schottky Diodes
- Power Inductors
- Complementary Passive components

#Challenges we ran into

#Accomplishments that we're proud of

#What we learned

# What's next for Zeus
Later this week we are thinking of fabricating this PCB along with component sourcing, to make it real.
Meanwhile, it was a good experience, about learning about the flyback controller, which not only provides isolation but also has great efficiency.

# Warning
This Circuit deals with AC mains (aka High Voltage that can kill you). Take precautions before performing. You have been warned.
