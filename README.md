# Current shunt

This is a simple current-shunt board designed to make it easy to measure
current with an oscilloscope probe.

## Fabrication

See the releases section for gerbers suitable for building at JLCPCB.

## Building

Putting the device together is simple enough. The only thing that needs explaining is the small disconnected pads next to the 10Ω and 1Ω resistors. The intent is for a thin wire to be connected from the top of the resistor to this pad in order to provide something that approximates a 4-wire connection.

Now that I think about this a bit more, this is overkill, but I'm not planning on producing another copy of this board.

## Case

`case.FCStd` contains a 3d-printable, snap-in case for this board. For a .stl file, see the releases.
