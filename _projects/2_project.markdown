---
layout: page
title: Monocular Vision Double-container Controller
img: /assets/img/project2.png
comments: true
---

Traditional detection strategies have the dead-zone problem with mechanical sensors. Therefore, in this project, an improved Randomized Hough transform for circle detection using vertical gradients, was proposed to efficiently detect moving circular targets in a complex background with high accuracy, and an interactive program with C++ was designed.


<div class="img_pro">
    <img src="{{ site.baseurl }}/assets/img/overheadcranemodel.png" >
</div>
<div class="col three caption">
    Automatic overhead crane system model
</div>

The pipeline for the algorithm includes:
Cropped out an interest area including circular target according to depth map, followed by filtering and edge detection. Then the algorithm calculated the center of circle with module mentioned above and finally scaled the position to the real world. Compared with cv.HoughCircles, the runtime decline from 0.037s to 0.018s.

<div class="img_pro">
    <img align="center" src="{{ site.baseurl }}/assets/img/monocularcamera.png" >

</div>
<div class="col three caption">
    Position estimation with monocular camera
</div>
<br>
<div class="img_pro">
    <img  src="{{ site.baseurl }}/assets/img/interactivesys.png" >
</div>
<div class="col three caption">
    Interactive measurement with C++
</div>
We added linear interpolations between neighboring frames to support precise control for an overhead crane system while using less hard thresholds.
Finally, one paper was published and a Chinese patent of invention was granted on the basis of the above research.
<div id="disqus_thread"></div>
