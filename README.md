# Dual Transceiver RF-Sensing Switch

I have in mind a design for a two-port device where both ports are RF-sensing, and on sensing RF on a port, does two things:

1. interrupt the PTT line of the transceiver on the other port

2. ground the pin of the coax connector of the transceiver on the other port

It could also contain circuitry to split the receive signal properly, if it turned out to be required.

This is different from the MFJ RF-sensing SDR switch in that it takes two transceivers, rather than a transceiver and a receiver.
