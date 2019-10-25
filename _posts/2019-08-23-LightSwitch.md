---
layout:     post
title:      "Dorm Light IR Switch"
subtitle:   "Arduino + IR Sensor + IR Remote"
author:     "bythew3i"
header-img: "img/post/20190823/IR_arduino.png"
tags:
    - Arduino
    - robot
    - sensor
---

> During my first week of life at Yale, I was so tired of walking all the way to turn off the light in the dorm. Because the bed is soooo far away from the light switch. Then, guess what? I built a remote switch!!!

Oh! By the way, you can not find my dorm... because it is 404...hahaha
<img src="/img/404.jpeg" alt="404" width="40%">

### Brainstorming
My initial plan was using `bluetooth`. But it might be time-consuming to write a interface for the front end for iPhone. Another alternative is using PS4 controller to connect the Arduino, but I felt it was such a waste on PS4 controller. 

Then I think the optimal plan is `IOT` (Internet of Things) by `Wi-Fi` or `Ethernet` port. By setting up a server, I can control the light switch on web in any device. But bad news is that the Ethernet port seems broken in my dorm. I called the Yale IT service, I was told I can not set up my own server in dorm. 

Finally, I realized I can set up a remote control with IR components. So I used `arduino`, `IR sensor` and `IR remote` to build a light switch . Check out the video below...


#### Showcase
<iframe src="https://www.youtube.com/embed/QKVqRtLmnKw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


---