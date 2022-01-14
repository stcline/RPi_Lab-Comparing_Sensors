# :robot: Raspberry Pi Lab - Comparing Sensors

## 🤓 Overview and learning outcomes 

The goal of this lab assignment is to give an overview of several different sensor types based on the chart in Section [4.1.3 of our online text](https://roboticsengineeringcourse.github.io/mechanical-design.html#sensors).  Students will be able to distinguish between active and passive sensors as well as proprioceptive and exteroceptive sensors.🚀

## Lab Setup

### Electronics Components

You will need the following components from your kit for this assignment:
<ul>
  <li>Raspberry Pi</li>
  <li>Several Jumper Wires (see diagrams below)</li>
  <li>Resistors (see diagrams below)</li>
  <li><a href = "https://i.stack.imgur.com/emufv.jpg" target = "_blank">Limit switch</a></li>
  <li><a href = "https://cdn.sparkfun.com//assets/parts/1/3/5/0/8/15569-Ultrasonic_Distance_Sensor_-_HC-SR04-01a.jpg" target = "_blank">Ultrasonic sensor</a></li>
  <li><a href = "https://m.media-amazon.com/images/I/41+EOhGDWeL._SX342_.jpg" target = "_blank">Humiture sensor</a></li>
</ul>

### Prototpypes
Construct each of the prototypes using the diagrams below:

#### Limit Switch

![Limit Switch Circuit](https://github.com/stcline/RPi_Lab-Comparing_Sensors/blob/main/SPDT_Pull_up_RPi.JPG?raw=true)

#### Ultrasonic Sensor

![Ultrasonic Sensor](https://github.com/stcline/RPi_Lab-Comparing_Sensors/blob/main/HC-SR04_RPi.JPG?raw=true)

#### Humiture Sensor - NOTE that the module you will be given allows us to omit the 10k Ohm resistor. 

![Humiture Sensor](https://github.com/stcline/RPi_Lab-Comparing_Sensors/blob/main/DHT11_Sensor_RPi.JPG?raw=true)

### Procedure: Code Execution

1. Get the code and run the first two scripts:

- Clone the repository and change the working directory.

  `git clone https://github.com/stcline/RPi_Lab-Comparing_Sensors`

  `cd RPi_Lab-Comparing_Sensors`

- Each script is for a different prototype.  Run the first two scripts.

  `sudo python3 limit.py`

  `sudo python3 ultrasonic.py`

3. For the last part of the project using the humiture sensor, we will deviate from the python coding we have been doing and use the C language as our programming environment.  Follow the instructions on [this tutorial](https://www.circuitbasics.com/how-to-set-up-the-dht11-humidity-sensor-on-the-raspberry-pi/) to test out the sensor.  While you do not need to do the example that uses the LCD display, we have plenty of those if you would like to use one.
  
4. Compare the results of the three prototypes.

## 💻 Terms to know

**Active Sensors**: An active sensor is one which transmits a signal into the environment and then measures the response that comes back.

**Passive Sensors**: A passive sensor is one which just ‘listens’ to what is happening.

**Proprioceptive Sensors**: A proprioceptive sensor measures values internal to the system (robot).

**Exteroceptive Sensors**: An Exteroceptive sensor acquires information from the robot’s environment.

## 📝 Next steps (Graded)

Now that you have had a chance to play around with the different sensor types, answer the questions below in a markdown file in this repo called "responses.md".  Then describe how these sensors could be used in an autonomous robotic system.  Be sure to properly use **ALL** of the terms listed in this document in your responses.  Save those descriptions in a markdown file in this repo called "applications.md".

### Questions

1. What is the actual physical process that is allowing the Raspberry Pi to sense the environmnet?
2. What are some environmental factors that might influence the performance of these sensors?
3. What role does coding play in this process?

## 📚  Resources 

- [Robot Perception](http://www.cs.cmu.edu/~rasc/Download/AMRobots4.pdf)
- [DHT11 Temperature and Humidity Sensor and the Raspberry Pi](https://www.raspberrypi-spy.co.uk/2017/09/dht11-temperature-and-humidity-sensor-raspberry-pi/)
- [Using a Raspberry Pi distance sensor (ultrasonic sensor HC-SR04)](https://tutorials-raspberrypi.com/raspberry-pi-ultrasonic-sensor-hc-sr04/)
- [VIDEO:Pull up & Pull down Resistors in 5 mins](https://www.youtube.com/watch?v=hG_AVuuXatw)
