---
layout: page
title: CNN for Age & Gender Prediction
img: /assets/img/project1.png
comments: true
---

This project serves as age & gender prediction plugins for 'AI Led Mirror' which is an embedded system that interacts with its user via speech, and combines face detection, age & gender prediction and other awesome functions as a whole.

The age prediction, an ordinal regression problem, is addressed with deep Convolutional Neural Network. The pipeline for training is shown as the diagram below.

<div class="img_row">
    <img src="{{ site.baseurl }}/assets/img/pip1.png">
</div>
<div class="col three caption">
    Pipeline for multiple outputs convolutional neural network
</div>

The code powered by tensorflow is available <a href="https://github.com/pengbohua/AI-Led-Mirror" target="blank">here</a> on my <a href="https://github.com/pengbohua/AI-Led-Mirror" target="blank">github page</a>. It is forked and overrided from another open src smart speaker project called dingdang-robot where I am a contributor!  

An end-to-end learning architecture for automatic speech recognition is proposed with the overrode code of Transformer. Character error rate (CER) of Mandarin ASR on <a href="http://166.111.134.19:8081/data/thchs30/README.html" target="blank">THCHS-30</a> has been reduced a lot compared to the HMM based benchmark method. I am writing a paper to summarize my work.

<div id="disqus_thread"></div>
