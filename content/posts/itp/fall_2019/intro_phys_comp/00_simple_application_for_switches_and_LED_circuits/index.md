+++
slug = "simple_application_for_switches_and_LED_circuits"
title = "Simple Application for Switches and LED Circuits"
date = "2019-09-17T21:19:43-04:00"
author = "Noah Kernis"
tags = ["itp", "intro_physical_computing"]
description = "Learning basic circuits and a valuable lesson."
showFullContent = false
+++

## The Thinking Part

For the assignment, "build a simple application for switches and LED circuits", I built a switch that is *handshake* activated. Although, it does require both hands to be wearing metal rings attached to alligator clips attached to a variable power supply... 

I was interested in creating something that required two people to interact to turn the LED on. Silly, but the handshake idea came from me looking down at my hands and seeing the ring I always wear. 

My ring is gold, so I knew it would conduct electricity. I just needed to make sure I found someone who had a gold or silver ring (friends who are married often have wedding rings made of good metals - for whatever thats worth).

## Building a Simple Circuit 

For the most part, building the simple circuit went well. There is one moment worth mentioning.

**Important lesson #1**: When using the cheap wires that come with breadboards, test them for continuity

It took me forty minutes to realize that the issue was not my wiring, but rather it was a single, evil wire. I have provided a photo of this evil wire so I can be reminded of this lesson. 

{{< figure src="img/01_evil_wire.JPG" alt="short, orange wire on table. up close" caption="[ Evil Wire ]" >}}

After testing all the wires for continuity, and replacing the evil one, I got the LED to turn on. 

{{< figure src="img/00_led_setup.JPG" alt="Yellow LED that is on. Wired up to a breadboard that is connected to a variable power supply." caption="[ Variable Power Supply and LED On ]" >}}

## Other Simple Circuits

For fun, I tested to other components. A button and a motor.

### Button

I added a button in series with the LED. 

Here is a very scientific table showing how the button effects the state of the LED:

| Action  | LED State           
| ------- |----------- |
| Press Button | *ON* |
| No Press Button | *OFF* |

And here is the button in action:

{{< figure src="img/02_button_led.gif" alt="Finger pushing button on breadboard. When the button is pressed, a yellow LED turns on." caption="[ Pressing The Button ]" >}}

### Motor

For this, I replaced the LED with a motor and kept the button. The button turns on the motor. 

When on, the motor moves and vibrates a bunch when turned on. For fun, I wanted to see if I could make something quickly that moved. 

The motor's plastic encasing has a loop end on the back. I poked that into the small cardboard box the motor came in. When I turned on the motor, the box vibrated and moved a way from me. 

{{< figure src="img/03_button_motor.gif" alt="Finger pressing button to turn on motor. The motor is poked into a cardboard box, and when turned on, the box moves away. A flag on top also twirls, and when stopped, reveals the caption 'hello, motor'" caption="[ Hello, Motor ]" >}}

## The Process of Building - Handshake Activated LED

To create the switch for the handshake, I used the same breadboard setup I had been using for learning basic circuits. 

First I build the circuit for just an LED. I added two long wires extending out from the breadboard. This was done using wires that had alligator clips.

Next, I asked my friend Jake, who has a silver ring, if he would help me with my circuit (*THANK YOU JAKE*).

Then I connected one clip to my ring, and the other clip to Jake's ring.

{{< figure src="img/04_ring_wired_up.JPG" alt="Foreground: Alligator clip connected to gold ring. Background: Breadboard setup for LED." caption="[ The Setup - My Ring ]" >}}

To active the LED, our rings hand to make contact. To do this, Jake and I shook hands (yes - left hands - whatever). 

{{< figure src="img/05_handshake.gif" alt="Hands with rings connected to wires. The hands shakes and the yellow LED on the breadboard turns on." caption="[ Shake To Turn The LED On ]" >}}

## Conclusions 

- Test your wires for continuity (worth saying twice)