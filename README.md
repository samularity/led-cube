## led-cube
===================

#### a 3x3 one color led-cube driven from a attiny2313

To compile run:

    make
To flash it with usbasp run:

    make load
Also:

    make clean
Fuses can be set with::

    make wrfuse8mhz
Edit **"PROGRAMMER"** in the Makefile to customize for your ISP Adapter.
