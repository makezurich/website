+++
title = "Getting started"
weight = 4
type = "info"
aliases = ["/de/start"]

[menu.footer]

+++

Make Zurich is a community event around civic tech and in particular, the [The Things Network](https://thethingsnetwork.org) community. It brings together the maker community and the city administration to devise creative solutions to our city's problems.

<!--more-->

**Slides:**

* [**Kick-off slides**<i class="fa fa-file-powerpoint-o ml-2"></i>](https://docs.google.com/presentation/d/1AZKdVwxiU523PqrmQYuqzSjM2JygpF8D8DViXHUglWo/edit?usp=sharing)
* [**Hackday #1 slides**<i class="fa fa-file-powerpoint-o ml-2"></i>](https://docs.google.com/presentation/d/1mC8KlbmocwPJFVHYnfn6kzGySW-yrMykdiWqQdlSTSs/edit?usp=sharing)

<img src="/images/challenges/howto.png" alt="Mini HOWTO" width="100%" />

## 1. Explore Challenges

Find out more about each challenge on the following pages:

* <span class="badge badge-pill blue darken-4"><a href="/start/1" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Granny Alert challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/2" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Move and Chill challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/3" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Breathe! challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/4" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Bicycle Parking challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/5" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Awesome Green Spaces</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/6" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Transformer Station Tub</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/7" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Open Challenge</a></span>

Contact details to ask questions directly to the challenge stakeholders are available on each of the challenge pages above.

## 2. Team up

Use Slack to find team members:

* Slack channel [#mz2020_team-formation](https://app.slack.com/client/T0CMJ6ESH/C01CXFN2TT7/thread/CB94UMQMC-1561794678.000600)
* Slack channel [#makezurich](https://app.slack.com/client/T0CMJ6ESH/C3XSZ7NTF/thread/CB94UMQMC-1561794678.000600)
* Need support finding team members? [#makezurich-support](https://app.slack.com/client/T0CMJ6ESH/C01CRBDCTE2/thread/CB94UMQMC-1561794678.000600)

## 3. Start/Join project

We use [Dridbat](https://now.makezurich.ch/), an open source tool for managing hackathon projects created by [@loleg](https://github.com/loleg).

1. First sign in, you can use your slack account for that or create a new one.
2. [See all challenges and existing projects](https://now.makezurich.ch/event/4)
3. Then either [Start a project](https://now.makezurich.ch/event/4/project/new)
4. ...or [join an existing team](https://now.makezurich.ch/event/4)

If you need more details, here's a [quick guide to Dribdat](../dribdat)

## 4. Hack and Make!

Now you're all set to **start making awesome stuff!**

Check the heaps of material we made available for you:

### Available hardware and resources

First of all, check the following two excellent guides:

* [Make Zurich hardware intro](https://github.com/make-zurich/makezurich-hardware-intro/)
* [Make Zurich software intro](https://github.com/make-zurich/makezurich-software-intro/)

[**Tech specs and datasheets for all hardware**<i class="fa fa-file ml-2"></i>](../techspecs)

### Inside the box

Each team gets a hardware kit with:

* Lots of basics (MB102 830 points breadboard + power supply + jumper wires, resistors, LEDs, switches, pots, level shifters, etc.)
* ST Discovery Board B-L072Z-LRWAN1 (Murata LoRaWAN chip)
* Miromico FMLR-72-U-STL0Z LoRaWAN module
* Sensirion Environmental Sensor Shield (temperature, humidity, gas sensor)
* LoRaWAN Indoors Tabs Hub gateway

And sensors (depending on the challenge):

* Adafruit AMG8833 8x8 Thermal camera: Awesome Green Spaces
* Flex bent and Force Sensing Resistors: Move and Chill
* U-blox PAM-7Q GPS module: Move and Chill, Breathe!, Open challenge
* Motion/PIR: Bicycle Parking, Awesome Green Spaces, Open Challenge
* Sensirion SPS30 Particulate Matter Sensor: Breathe!
* Steam sensor PIS-1271 and SEEED 101020018 Water level sensors: Granny Alert
* Water level sensor SEEED 101020018: Transformer Station Tub, Open challenge
* Relay DFR0017: Transformer Station Tub, Open challenge
* ToF Laser Distance ranging VL53L1X: Bicycle Parking, Awesome Green Spaces, Transformer Station Tub
* Ultrasonic distance sensor HC-SR04: Bicycle Parking, Awesome Green Spaces, Transformer Station Tub
* UV light/index VEML6070: Awesome Green Spaces
* Vibration sensor SEN0289: Open challenge

Shared materials:
* Arducam Mini 2MP+5MP Cameras (but beware of the privacy issues with filming people)
* Sensirion SCD30 CO2 and RH/T: check out the CO2 monitoring workshop on Thursday!
* ...and a lot of other useful stuff, like conductive tape, hook-up wire, some other basic microcontrollers, etc.

### Outside the box

The main microcontroller of the event is also the one in the badge!
Each participant gets an electronic badge with an [Arduino Nano 33 BLE Sense](https://store.arduino.cc/arduino-nano-33-ble-sense).

Besides packing a huge amount of integrated sensors, the board has a u-blox NINA B306 module that is so powerful that you can run inference at the edge with TensorFlow Lite Micro on it!

Resources:

* [Examples](https://github.com/yene/Nano-33-BLE-Sense)
* [Official getting started](https://www.arduino.cc/en/Guide/NANO33BLESense)
* [More examples](https://github.com/DaleGia/Nano33BLESensor)

### Around the city

Zurich has the biggest free, open and crowd-sourced LoRaWAN network of the world!

If you don't have coverage where you live, use the gateway in your hardware kit! Simply plug it to your network (LAN port) and it will start working!

#### LoRaWAN & The Things Network

Are you new to LoRaWAN? The best way to get started with it and The Things Network is the **LEARN** section of the website: https://www.thethingsnetwork.org/docs/

Additional resources:

* [Documentation](https://www.thethingsnetwork.org/docs/)
* [LoRa crash course by Thomas Telkamp](https://www.youtube.com/watch?v=T3dGLqZrjIQ)
* [The Things Network: Basics](https://speakerdeck.com/gonzalocasas/the-things-network-basic-presentation)

On Monday, there will be a LoRaWAN workshop at the lab.

## 5. Present your idea

On Saturday 31st, at the end of the second hackday, teams will present their projects. Make sure you documented yours on Dribdat and ideally also published code and assets you created with open source licenses!
