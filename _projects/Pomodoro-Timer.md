---
layout: project
title: Arduino Pomodoro Timer
featured_image: "/photos/Tomato.png"
source_code: "https://github.com/CameronTrumpy/PomBox"
summary: A productivity timer designed to aid in studying and focusing on one's tasks, following a well-researched productivity method
---
Let's face it. Between social media, games, videos, news, etc... our phones are a huge barricade in the way of us focusing on getting work done. This is something I struggled with, and I attempted multiple approaches to curbing my phone use while studying. In the end, I decided I needed a physical aid that would hold me in check and help me study.
 
The *[pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique)*, is a well-researched productivity method, where one hyper-focuses on their assignment/work for 25 minutes, and then takes a five minute break. After 4 pomodoros, a 15-30 minute break is taken. The end result of this method applied with the timer is easier application of this technique, with a layer of responsibility taken off of the user.

To combine this reasearched technique with my desire for a physical study aid, I designed a physical pomodoro timer which also monitors if you are distracted by your phone.

The timer features ESP-8266 arduino microcontroller along with a 16x2 character LCD display and a few buttons for user interaction. The timer displays your work and break time for you, and beeps to notify completion of a pomodoro cycle. It also monitors if you have picked up your phone during work time, and beeps to notify the user that they are distracted.
 
I designed the housing in Fusion360, and programmed the project in Arduino.
 
Overall, it ended up being an effective application of a well-researched productivity method, and helped me study for the SAT and my schoolwork with less distractions. My GitHub Repository includes a README which explains how to make your own PomBox.