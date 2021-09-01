---
layout: project
type: project
image: images/elevator.jpg
title: Elevator Project
permalink: projects/elevator
# All dates must be YYYY-MM-DD format!
date: 2021-08-30
labels:
  - Real-time programming
  - Network 
  - Go
summary: Created software for developing n elevators with a UDP peer-to-peer architecture. 
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>


In this project we implemented a real-time system for controlling n elevators in Golang. Further description and solution to the problem can be found [here](https://github.com/ninanye/TTK4145-Heis).

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```




