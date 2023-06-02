+++
title = "Getting started"
weight = 4
type = "info"
aliases = ["/de/start"]

[menu.footer]

+++

Make Zurich is a community event around civic tech and in particular, the [The Things Network](https://thethingsnetwork.org) community. It brings together the maker community and the city administration to devise creative solutions to our city's problems.

<!--more-->

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/832788146?h=5b3e1cd842&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Make Zurich 2023: Kick-off"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

**Slides:**

* [**Kick-off slides**<i class="fa fa-file-powerpoint-o ml-2"></i>](https://docs.google.com/presentation/d/1rYzPH4GS2FUBItV512o2aVRx134-k-Ogr8T5pfGxU20/edit?usp=drivesdk)


<img src="/images/challenges/howto.png" alt="Mini HOWTO" width="100%" />

## 1. Explore Challenges

Stay tuned for a series of exciting challenges that will be announced on June 2 and published on our hackathon platforms!

<!--Find out more about each challenge on the following pages:

* <span class="badge badge-pill blue darken-4"><a href="/start/1" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Granny Alert challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/2" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Move and Chill challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/3" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Breathe! challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/4" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Bicycle Parking challenge</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/5" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Awesome Green Spaces</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/6" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Transformer Station Tub</a></span>
* <span class="badge badge-pill blue darken-4"><a href="/start/7" class="white-text"><i class="fa fa-caret-right" aria-hidden="true"></i> Open Challenge</a></span>-->

Contact details to ask questions directly to the challenge stakeholders are available on each of the challenge pages above.

## 2. Start/Join project

We use [now.makezurich.ch](https://now.makezurich.ch/) - an open source tool developed by our own team - for teambuilding and pulling together the hackathon projects.

1. To sign in, use your existing [TTN-CH Slack](https://join.slack.com/t/ttn-ch/shared_invite/zt-8tw3zlol-KDaiqrKZ8ZdMbqWoC7EVXQ) account, or create a dribdat account.
2. [See all challenges and existing projects](https://now.makezurich.ch/event/5)
3. Then either [Start a project](https://now.makezurich.ch/project/event/5/project/new)
4. ...or [join an existing team](https://now.makezurich.ch/event/5)

If you need more details, here's a [quick guide to Dribdat](../dribdat)

## 3. Get hacking

You are welcome to use any collaboration tool, with emphasis on all platforms that can be freely shared with all team members. The central community Slack is available, everyone will be invited so you can easily have a chat with your team members:

* Announcements and team building in the [#makezurich](https://app.slack.com/client/T0CMJ6ESH/C3XSZ7NTF/thread/CB94UMQMC-1561794678.000600) channel
* Need other support at the event? [#makezurich-help](https://app.slack.com/client/T0CMJ6ESH/C01CRBDCTE2/thread/CB94UMQMC-1561794678.000600)

## 4. Hack and Make!

Now you're all set to **start making awesome stuff!**

<!-- Check the heaps of material we made available for you:

### Available hardware and resources

First of all, check the following two excellent guides:

* [Make Zurich hardware intro](https://github.com/makezurich/makezurich-hardware-intro/)
* [Make Zurich software intro](https://github.com/makezurich/makezurich-software-intro/)

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
* [More examples](https://github.com/DaleGia/Nano33BLESensor) -->

### Around the city

Zurich has the biggest free, open and crowd-sourced LoRaWAN network of the world!

If you don't have coverage where you live, use the gateway in your hardware kit! Simply plug it to your network (LAN port) and it will start working!

#### LoRaWAN & The Things Network

Are you new to LoRaWAN? The best way to get started with it and The Things Network is the **LEARN** section of the website: https://www.thethingsnetwork.org/docs/

Additional resources:

* [Documentation](https://www.thethingsnetwork.org/docs/)
* [LoRa crash course by Thomas Telkamp](https://www.youtube.com/watch?v=T3dGLqZrjIQ)
* [The Things Network: Basics](https://speakerdeck.com/gonzalocasas/the-things-network-basic-presentation)

## 5. Present your idea

On Saturday 10th, at the end of the second hackday, teams will present their projects. Make sure you documented yours on Dribdat and ideally also published code and assets you created with open source licenses!
