# International Nodebots day 2015

## Getting started

Our Nodebots journey for today looks like this

* Nodebots intro using wheels and lights
* Sensor intro using light and lights
* More 'advanced' sensors - distance and motion
* Built your own sensor by combining your knowledge

##Nodebots intro using wheels and lights

Start here: http://node-ardx.org

### Control movement

To control the robot you can use the keypress module.

More details here:

* https://github.com/TooTallNate/keypress
* https://www.npmjs.com/package/keypress

### Continuous Servo

To power the nodebot using a continuous servo is the easist option. A servo is a complex component that gives your fine grained control over movement. Sending it pulses you can command how many degrees it should turn. The Johnny-5 API gives us an easy way communicate with servos.

More details here:

https://github.com/rwaldron/johnny-five/wiki/Servo

To get things moving in different directions you will need to combine the movememt of your servo's

Using the Servo in conjunction with the keypress module to move around.

### Built a bot powered by a DC motor:

It is easy to connect a battery to a DC motor to get it to turn in one direction. To let it turn in the other direction you just swap the wires around. But how to switch the wires when your robot is running around the room? H-Bridge to the rescue, a H-Bridge is an IC (Integrated Circuit) that allows one to switch the current flow. Basically switching the wires programatically.

See more information here : https://github.com/avermeulen/InnovationDay/blob/master/MotorDriver.md

##Sensor intro using light and lights

##More 'advanced' sensors - distance and motion

### Sensing motion

A PIR (passive infrared) sensor can sense movement.

See how to use it here:

* https://github.com/rwaldron/johnny-five/blob/master/eg/ir-motion.js
* https://github.com/rwaldron/johnny-five/wiki/IR.Motion

Go ahead and use it!

### Distance

An ultrasonic sensor can sense distance.

See how to use it here:
*   https://github.com/rwaldron/johnny-five/blob/master/eg/ping.js
*   https://github.com/rwaldron/johnny-five/wiki/Ping

## Combining your knowledge

Now that you have a solid understanding of Nodebots basics, let's combine everything and built things that combines your knowledge. Nodebots is like bricks you add sensors and actuators and then you connect them with code.

Here is some project ideas:
* Combine motion and your LED knowledge to rate the level of movement in the room
* Combine distance and your LED knowledge to see how far away someone is standing from your desk
* Combine combine your movement, light sensing and LED knowledge and  built a line following robot.


## Intro

Get going by looking at this tutorial

http://node-ardx.org/

## Built basic bot using continuous servos


## Background

https://github.com/avermeulen/InnovationDay
https://github.com/codex-academy/NodebotsOpenDay


