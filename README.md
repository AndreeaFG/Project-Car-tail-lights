# Project-Car-tail-lights

This project involved developing a controller for a vintage Thunderbird’s sequential tail lights,
managing three left (LA, LB, LC) and three right (RA, RB, RC) lights using LEFT, RIGHT, and HAZARD
inputs. LEFT and RIGHT come from the driver’s turn signal switch and cannot be 1 at the same time.
According to the specifications, when LEFT = 1 the lights flash in a pattern LA on; LA and LB on; LA,
LB, and LC on; all off; and then the sequence repeats. When RIGHT = 1, a similar sequence appears
on lights RA, RB, and RC, as indicated on the right side of the picture. If a switch from LEFT to RIGHT
(or vice versa) occurs in the middle of a flashing sequence, the circuit should immediately go to the
IDLE (lights off) state and then start the new sequence. HAZ comes from the hazard switch, and when
HAZ = 1, all six lights flash on and off in unison. HAZ takes precedence if LEFT or RIGHT is also on.
The project was implemented in Vivado, ensuring the correct operation of the lighting sequences
based on the input signals and required logic.
