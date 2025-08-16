---
layout: project
type: project
image: img/signglove/signglovesimulation.gif
title: "Sign Language Glove"
date: 2024
published: true
labels:
  - Arduino
  - Robotics
summary: "A wearable glove that can easily translate sign language and gestures."
---

<!-- <img class="img-fluid" src="../img/cotton/cotton-header.png"> -->

This wearable glove translates sign language gestures into spoken English in real-time, enabling deaf and speech-impaired users to communicate verbally without human interpreters. It overcomes the critical barrier of interpreter dependency, especially in emergency situations or hospitals.

<hr>

## The Problem

Speech and hearing impaired people have enjoyed the advent of standardized sign languages for communicating with each other. However, the main downside of this mode of communication is their inability to communicate with non-communicators of sign language, which is predominantly the population at large. World Federation of Deaf claims only 70 million people know sign languages (which is quite small, proportionally, when compared to the 8 billion population of our Globe!)

Communication with people who don't understand sign language would require interpreters (a person who is capable of translating sign language into voice and vice versa), presenting a significant challenge as interpreters are not available all the time, especially during an emergency situation or in hospitals, and can be quite costly.

<hr>

## The Solution

My project aims to address this issue through an affordable Arduino Nano-based wearable glove device. The user simply gestures hand signs, which the microcontroller translates in real-time into English or pre-programmed prompts. The output messages are delivered visually on a screen, like a 16x2 LCD or your smartphone, and orally via a connected smartphone or any other compatible device, eliminating the necessity of a translator and enabling easy, cost-effective and seamless communication with the general population. Moreover, people can use this glove to learn sign language as well!

My project aims to be as accessible and affordable as possible. My pair of gloves cost less than 10,000 PKR and wrote a few different codes for it.

One with pre-programmed gesture messages (like "I want to go to washroom," or "My name is [abc]") which is particularly helpful for patients in conditions where they cannot talk or listen but do not have the time and resources to learn a sign language. By removing the need for a sign language, this Arduino IDE (C++ based) program is suitable for providing all the essential information, including emergencies, and maintaining a decent level of communication with others. Users can easily change the pre-programmed messages as they want and require.

The other one is the one with real-time sign language translation, though it is a bit limited due to the lack of a gyrometer in my project (with small budgets come great obstacles!). Nonetheless, it is a good way to communicate without a costly interpreter as well as to learn or teach sign languages.

I wanted my project to be accessible and affordable for all people, so I challenged myself with a Rs 10,000 budget (~$35). I carefully planned my components and sensors: Arduino Nano, 16x2 LCD, a pair of gloves, and I found the breadboard, solder, wires and resistors from my club. However, buying flex sensor instantly threw me off budget--Rs 4,500 each, while I needed at least 5!

So I decided to turn to my reverse engineering and tinkering abilities. Following research papers, tutorials and physics books, I tested many different materials to make my own flex sensor. In the end, a thin paper covered thickly with graphite on both ends sandwiched between two aluminum foils worked the best. I covered my very own sensor with cardboard paper to avoid any current leakage and very carefully soldered the ends with wires. Making these sensors costed me a few hundred rupees.

With exhibition approaching, I had no choice but to stay over at the makerspace late into the nights, getting late from lights out at my hostel (and getting punished for being so late). At last, I was able to keep my gloves affordable, while also maintaining its functionality--it was worth it.

#### Hardware

'''
- Arduino Nano
- Flex Sensors (5x per hand)
  - (Or conversely you can...) Self-manufacture Flex Sensors
    - dada
'''

<hr>


<hr>

## References

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
