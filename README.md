# trekkersteer
This code is to vary sensitivity of steering control on a trekker personal scooter
the sensor checks the position of a tiller using a hall effect probe with two magnets
It has a 5V power supply and reads between about 1.5 V and 3.5v with tiller angles +/- 20 deg
the control system begins to actuate the wheels at a voltage of 2.8V (left turn) and 2.5V (right turn)
these correspond to -2 deg and +4 deg -- probably the one degree offset is an assembly error

This is quite big dead zone (6 deg) and the plan is to reduce that to increase responsivenes