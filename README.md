# GPS-positioning
This is a C++ programme. The programme is based on the basic principle of GPS pseudorange point positioning. First the receiver get the signal from four or more satellites. Then compute the position of satellites and the distances between satellites and the receiver according to the satellite ephemeris from signals. Finally, the position of the receiver is computed with resection method.  Most of time, the number of satellite in each epoch is more than four, so the least squares method is used to compute the position of the receiver.
