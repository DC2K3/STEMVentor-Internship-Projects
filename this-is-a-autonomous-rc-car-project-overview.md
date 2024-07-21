
## Overview

In this project we will be taking the chassis of a small toy car and converting it into a smart autonomous and bluetooth controlled car by adding micro-controller , sensors and bluetooth module.
The car will have 2 modes :
i - RC mode :

In this mode the car can be controlled using an app on the phone. Instructions such as forward , backward , left , right , stop , low/medium/high speed , exit mode can be sent via phones bluetooth to the micro-controller (to which a bluetoth module has been attatched). It will be a serial communication .

ii - Autonomous mode :

The car will be a lane following car . It will be able to stay in a single lane (the lane should be made out of black lines) using 2 IR sensors mounted at the front corners of the car chassis .
The car will also be able to detect distance of objects in front of it and stop if it senses one too close. After that it will scan left and right hand sides and take decision accordingly.
