# trekkersteer
This code is to vary the sensitivity of steering control on an EcoRider personal scooter using an Arduino UNO. 
The development was originally carried out on a Trekker, which is very similar, but some of the details are changed.  In particular the steering signal runs in the opposite sense to the Trekker
The sensor checks the position of a tiller using a hall-effect probe with two magnets. 
It has a 5.1V power supply and reads between about 1.5 V and 3.5v with tiller angles of +/- 20 deg.
The control system begins to actuate the wheels at a voltage of 2.8V (right turn) and 2.5V (left turn).  The mid point is at 2.65V.  (The Trekker had the voltages for left and right reversed)

This is quite a big dead zone (6 deg) -- and the plan is to reduce that to increase responsivenes
