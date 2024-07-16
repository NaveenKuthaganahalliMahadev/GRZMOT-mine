# Grzmot-mine

### INTRODUCTION:

Grzmot mine was built to help military personnel during tactical missions. The Grzmot mines can be thrown and stuck to any surface (like walls, floors, or even furniture). Inspired by a video game called "Rainbow Six Siege" in which the Grzmot mine is used to kill or disorient the opponent players. The mine after sticking to the surface and armed, can detonate if it is triggered. The mine can also be used for non-lethal purposes like concussing, flashing to blind for a short period of time, etc. The military personnel can place these mines on the walls behind them while entering a building (or a tunnel or a cave) so that they don't get flanked by the enemies.

<p align ="center">
   <img src="https://user-images.githubusercontent.com/97881084/209578302-def1e542-f8f6-4e18-a4eb-90db7124c3c4.jpg"  width="200" height="420">
</p>

### CAED Designs:

* The outer body of the mine was designed using Fusion 360 and 3D printed using durable material.
* The figure below shows the 3D design of the three modules (top, center, and bottom).

<p align ="center">
   <img src="https://user-images.githubusercontent.com/97881084/209579013-e36b0814-1359-4851-ad48-21196822265f.png">
</p>

### WORKING

1) The mine consists of a PIR (Passive Infrared) sensor which detects an infrared emitting body when in the detectable range. Human beings emit heat (infrared radiation) from their body. The PIR sensors are fundamentally made of pyro-elctric sensors, which can detect levels of infrared radiation. It has a detection range of 10m. Most PIR sensors have a 3-pin connection at the side or bottom. Used for ground, signal, and power connections. It also has a single output pin.

2) The output of the PIR sensor is connected to a 555 timer IC which is set to operate in monostable mode. The time-period for the timer is set by choosing the right values of the resistor and the capacitor.

3) The output of the 555 timer is connected to a relay which is then connected to the output/load. The relays act as an electrically controlled on-off switch between the high-voltage circuit and the low-voltage input. 

The figure below shows the circuit diagram.

![image](https://user-images.githubusercontent.com/97881084/209580074-127cd7c7-111d-4905-8837-3b3e86f9547e.png)




