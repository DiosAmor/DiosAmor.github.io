---
layout: page
title: A Prototype for Free-Space Molecular Communication
description: 2014 - 2020
img: assets/img/freespace_testbed.png
importance: 1
category: molecular communication
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/freespace_testbed.png" title="freespace mc testbed" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Free-space molecular communications: prototype. The transmitter (left) uses a spray to release alcohol, which propagates through the air to the receiver (right), an alcohol sensor. The microcontroller (<i>Arduino</i>) is used to interface the receiver to a computer.
</div>

📜 Molecular MIMO Communication Link (2015)

Develop MIMO testbed to enhance transmission speed of molecular communication {% cite Lee2015 %}.

A testbed was developed that uses alcohol as an information-carrying medium. A nozzle, which acts as the transmitter, uses compressed air to spray alcohol, and an alcohol sensor, which serves as the receiver, transmits the change in ambient alcohol concentration to a computer via an <i>Arduino</i>. The testbed was designed with two nozzles to improve the communication speed.

📜 Molecular MIMO with Drift (2015)

Develop MIMO testbed with fans and measure ILI of MIMO channel through MIMO testbed {% cite Lee2015b %}.

The testbed utilized two nozzles to enhance the communication speed. Additionally, a small fan was used to create fluid flow in the communication path to improve the performance of the communication system.

📜 Molecular MIMO: From Theory to Prototype (2016)

Improve the data rate, a novel multiple-input multiple-output (MIMO) design for molecular communication {% cite Koo2016 %}.

This paper discusses the implementation of a Multiple-Input Multiple-Output (MIMO) system for molecular communication. I was responsible for writing the testbed section of the paper, in which I demonstrated how the theory is realized through a practical working example.

📜 An Experimentally Validated Channel Model for Molecular Communication Systems (2019)

Consider receiver (alcohol sensor) characteristics for the modeling channel model {% cite Kim2019 %}.

When implementing molecular communication with a testbed, we use an alcohol sensor as a receiver. We have assumed that the relationship between the change in alcohol concentration and the change in the sensor's signal is linear, but in reality, there are discrepancies. This study aims to derive an accurate channel model by considering the characteristics of the sensor.

📜 ISI-Mitigating Channel Codes for Molecular Communication via Diffusion (2020)

Validate channel codes using the testbed {% cite Kislal2020 %}.

In communication, there are often instances where signals that fail to arrive on time affect the current signal, causing interference. Channel coding techniques to reduce this Intersymbol Interference (ISI) are essential for practical application.

This paper discusses channel coding techniques that can be applied to molecular communication, where such interference is particularly severe. It also demonstrates the improvement in communication system performance through a practical testbed.
