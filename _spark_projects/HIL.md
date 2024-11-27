---
layout: project
title: Custom HIL System
featured_image: "/photos/SPARK/HIL_dev.png"
source_code: "https://github.com/SparkElectricRacing/BMSValidationBoard"
summary: "Purpose built HIL System for custom BMS validation."
---
> **_NOTE:_**  This project is still under development.

During the development of our [custom Battery Managment System](https://github.com/SparkElectricRacing/SparkBMS), I recognized the need for a consistent, repeatable way for us to test our BMS hardware and software.

This prompted the design of our custom HIL system, which utilizes two Analog Devices AD5204 Digital Potentiometers, as well as one of their AD5767 16-channel DAC chips. This allows us to inject arbitrary "cell voltages" and "thermistor temperature" readouts to our BMS, and validate both the accuracy of it's measurement as well as the fault handling taking place on our main BMS motherboard.

