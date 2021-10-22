# Fluke-8505A Riser Board

A physical extension that allows Fluke 8505A and 8506A modules to be measured and tested
live. Originally produced for a repair described in an article at [1].

[1] https://xdevs.com/article/f8505a/

These instruments are based on a module system, but the boards are close-packed and
it's impossible to actually get to various points on a module while it’s powered up.
So the only way to do this is to have some kind of extender card or cable. The interface
to the DMM isn’t anything high-speed or pretentious, so just hooking up things with wires
and PCB traces is good enough.

This project contains the gerbers for the card-edge connector that plugs into the Fluke
mainboard. It is left as an exercise to the reader to construct the other end of the
connector that fits on the module cards. Both sides use an unusual 3.81mm pitch.
More common 3.96mm pitch connectors will NOT work without significant modification.
The xDevs article above shows one possible solution.
