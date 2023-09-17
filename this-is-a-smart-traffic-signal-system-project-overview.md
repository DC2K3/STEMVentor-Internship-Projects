## Smart Traffic management

In this project we would be developing a smart traffic signal system.
There will be two traffic lights at an intersection - one to control the south-north flow and another to control the west-east flow. For simplicity, no turns will be allowed.

The objective of this project is to control the traffic lights based on a combination of time and traffic flow volume. There will also be a provision for an interrupt for pedestrian crossing and also a safety mechanism to detect if any object is standing on the pedestrian crossing.

One infrared sensor will detect how far the traffic has backed up on either side and optimize the lights such that the higher flow is cleared faster. This sensor can be moved to allow for more or less cars to be backed up.

There will be two pedestrian crossings (without signals) at one point across each path. If a push button switch is pressed the traffic lights in that flow will turn red within a few seconds to allow pedestrians to cross.

The second infrared sensor will be positioned along the pedestrian crossing. This cannot be moved and will act as the safety mechanism. The safety check should ensure that the traffic light should turn green only after no object is detected on the pedestrian crossing path.

The lights will switch from red to amber to green. The timing will be such that when one light has turned red the other one turns amber.

This project will use the Raspberry Pico board with microPython programming.
