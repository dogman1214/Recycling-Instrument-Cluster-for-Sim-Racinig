# Recycling-Instrument-Cluster-for-Sim-Racinig
I am recycling a junked out car's instrument cluster, specifically Audi s5, and possibly an audi Q7, to work with digital racing games.


So first, we will have to source some parts. What we need is:
1: Instrument cluster (in this case, a B8.5 audi S5)
2: ESP32 WROOM Devkit
3: Dupont Cables of all male and female combinations
4: SN65HVD230 CAN Reciever
5: 12V DC power brick
6: A laptop (preferably windows)
7: A means of soldering wires together


To start off this project, first, we have to do the wiring.

On the back of the AUDI S5's instrument cluster, there is a 32 pin board. You will be able to tell which order the pins go based on tiny stamps that say the pin number on each corner. For me, it is upside down with Pin 32 on top left and pin 1 on bottom right.


Dupont cables can generally handle only 1 amp. Our audi cluster requires up to 1.5 amps. Luckily, the instrument cluster reservs 2 pins for positive, and 2 pins for negative so we don't have to worry about that. But, For the wiring for power delivery, we will have to create a 3-way junction that connects to the 12v power brick for negative terminal, and a 2-way junction for the positive. We will have to use a thicker wire to solder to the power source which then splits 3 ways to the Audi Cluster same for the 2 way

[INSERT IMAGE IF THE 3 WAY WIRING AND ALL]


With the DuPont cables, (BY THE WAY, THIS VARIES PER INSTRUMENT CLUSTER. PLEASE REFER TO YOUR WIRING DIAGRAM IF USING A DIFFERENT CLUSTER), 
