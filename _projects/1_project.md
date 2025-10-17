---
layout: page
title: A Prototype for Free-Space Molecular Communication
description: 2014 - 2020
img: assets/img/mc/freespace_testbed.png
importance: 1
category: molecular communication
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mc/freespace_testbed.png" title="freespace mc testbed" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Free-space molecular communications: prototype.The transmitter uses a spray to release alcohol, which propagates through the air to the receiver, an alcohol sensor. The microcontroller (<i>Arduino</i>) is used to interface the transmitter/receiver to a computer.

</div>

<br>

<h3><b>📜 Molecular MIMO Communication Link {% cite Lee2015 %} (2015)</b></h3>

<br>

Develop MIMO testbed to enhance transmission speed of molecular communication.

A testbed was developed that uses alcohol as an information-carrying medium. A nozzle, which acts as the transmitter, uses compressed air to spray alcohol, and an alcohol sensor, which serves as the receiver, transmits the change in ambient alcohol concentration to a computer via an <i>Arduino</i>. The testbed was designed with two nozzles to improve the communication speed.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/mNjV_GEWRF8?si=LHk5rF3P_4VvECXN" title="Demo video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="display: block; margin: 0 auto;"></iframe>
   </div>
</div>
<div class="caption">
    Demo video of molecular MIMO communication testbed
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mc/infocom_demo_scene.jpg" title="Infocom demo scene" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Demonstrate molecular MIMO communication testbed at IEEE INFOCOM 2015.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mc/infocom_best_demo_award.jpg" title="Infocom best demo award" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    IEEE INFOCOM Best Demo Award
</div>

<br>

<h3><b>📜 Molecular MIMO with Drift {% cite Lee2015b %} (2015)</b></h3>

<br>

Develop MIMO testbed with fans and measure ILI of MIMO channel through MIMO testbed.

The testbed utilized two nozzles to enhance the communication speed. Additionally, a small fan was used to create fluid flow in the communication path to improve the performance of the communication system.

<br>

<h3><b>📜 Molecular MIMO: From Theory to Prototype {% cite Koo2016 %} (2016)</b></h3>

<br>

Improve the data rate, a novel multiple-input multiple-output (MIMO) design for molecular communication.

This paper discusses the implementation of a Multiple-Input Multiple-Output (MIMO) system for molecular communication. I was responsible for writing the testbed section of the paper, in which I demonstrated how the theory is realized through a practical working example.

<br>

<h3><b>📜 An Experimentally Validated Channel Model for Molecular Communication Systems {% cite Kim2019 %} (2019)</b></h3>

<br>

Consider receiver (alcohol sensor) characteristics for the modeling channel model.

When implementing molecular communication with a testbed, we use an alcohol sensor as a receiver. We have assumed that the relationship between the change in alcohol concentration and the change in the sensor's signal is linear, but in reality, there are discrepancies. This study aims to derive an accurate channel model by considering the characteristics of the sensor.

<br>

<h3><b>📜 ISI-Mitigating Channel Codes for Molecular Communication via Diffusion {% cite Kislal2020 %} (2020)</b></h3>

<br>

Validate channel codes using the testbed.

In communication, there are often instances where signals that fail to arrive on time affect the current signal, causing interference. Channel coding techniques to reduce this Intersymbol Interference (ISI) are essential for practical application.

This paper discusses channel coding techniques that can be applied to molecular communication, where such interference is particularly severe. It also demonstrates the improvement in communication system performance through a practical testbed.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mc/humantech_award.jpg" title="Humantech award" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Bronze Medal at the Samsung 26th Humantech Paper Contest
</div>
