---
layout: page
title: Wireless Multi-agents Control Systems
description:
img: /assets/img/project3.png
comments: true
#redirect:
---

With Zigbee wireless nodes supported by TI Co. and some cheap sensors including ultrasonic sensors, laser sensors and magnetic sensors I built a home security system in the Third National IOT Competition in 2016. At the first stage, the sensors could measure the conditions of the house model and sent information to each other via Zigbee CC2420 modules. Then motors and buzzers would reacted in different patterns. Basically, the component-based operating system could be powered by embedded systems such as TinyOS, and was considered as low-power consuming system at that time. Although the codes were relatively short and boring, that was the first time I learned to use Ubuntu, and until now it is still my favorite open source system.


<div class="img_pro">
   <img  src="{{ site.baseurl }}/assets/img/node.png" alt="node"> &nbsp; &nbsp;
   <img  src="{{ site.baseurl }}/assets/img/project3.png" alt="wireless smart car"> &nbsp; &nbsp;
</div>
<div class="col three caption">
    Wireless node board and smart car
</div>
While TinyOS was written in nesC, a dialect of the C language optimized for the memory limits of embedded systems, the supplementary tools were mainly in the form of Java and shell script front-ends. So that competition was a super cool opportunity to make my knowledge of JavaScript solid. On the top of these knowledge, I used several nodes and built a simple leader-follower control system and many other cool stuff.
