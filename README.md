# RPLidar---Arduino-DUE
Detection of obstacles using RPLidar on arduino DUE

As robopeak driver didn't work for me with the Arduino DUE (it works great with Arduino Mega thought), had to make a rudimentary driver myself. 

Arduino main code will allow the detection and description of objects, and then send them through a can bus.
Arduino main code bis send the filtered data (distance and angle) on the main serial
Matlab script provide a basic visualisation of the data sent on serial

Everything in this code in rudimentary and quite bad coded, but it worked flawlessly for me.


