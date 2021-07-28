# :robot: Raspberry Pi Lab - Comparing Sensors

## 🤓 Overview and learning outcomes 

The goal of this lab assignment is to give an overview of several different sensor types based on the chart in Section [4.1.3 of our online text]put proper link here.  Students will be able to distinguish between active and passive sensors as well as proprioceptive and exteroceptive sensors.🚀

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

#### Humistor Sensor

![Humistor Sensor](https://github.com/stcline/RPi_Lab-Comparing_Sensors/blob/main/DHT11_RPi.JPG?raw=true)

### Code Execution
    1. `git clone https://github.com/stcline/RPi_Lab-Comparing_Sensors`
    2. `cd RPi_Lab-Comparing_Sensors`
    3. `sudo python3 limit.py`
    4. `sudo python3 ultrasonic.py`
    4. `sudo python3 humiture.py`
    
Looks like it might need some Adafruit to work: https://www.raspberrypi-spy.co.uk/2017/09/dht11-temperature-and-humidity-sensor-raspberry-pi/

Each script is for a different prototype.  Run each script and compare the results.

## 💻 Terms to know

## 📝 Next steps (Graded)

Now that you have had a chance to play around with the different sensor types, answer the questions below in a markdown file in this repo called "responses.md".  Then describe how these sensors could be used in an autonomous robotic system.  Be sure to properly use **ALL** of the terms listed in this document in your responses.  Save those descriptions in a markdown file in this repo called "applications.md".

## 📚  Resources 
