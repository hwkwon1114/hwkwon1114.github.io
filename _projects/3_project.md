---
layout: page
title: Automated Medium Refreshment for Cells Growth
description: Circuit Based Automation Project with Raspberry Pi Control
img: assets/img/Total_View.jpg
importance: 2
category: Research
giscus_comments: true
---

This project aims to automate laboratory tasks such as media refreshment while preventing contamination risks by reducing human contact. We developed an automated system using peristaltic pumps, a Raspberry Pi, stepper drivers, and a flow sensor. The gantry system was created in collaboration with Ph.D. students.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pump.jpg" title="Peristaltic Pump Setup" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Circuit.jpg" title="Circuit Implementation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Peristaltic pump setup for automated media delivery. Right: Circuit implementation showing control system integration.
</div>

## Operation Modes

The machine supports two sophisticated types of operations:

### 1. Continuous Media Refreshment

- Maintains a fixed flowrate using PID control
- Flow rate sensor readings provide feedback
- Stepper driver adjusts speed based on real-time measurements

### 2. Fixed Volume Refreshment

- Operates at a set motor speed
- Integrates flowrate readings over time
- Automatically stops when desired volume is reached
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1" controls autoplay loop>
            <source src="/assets/video/media_refreshment.mp4" type="video/mp4"/>
        </video>
    </div>
</div>
<div class="caption">
    Demonstration of the automated media refreshment process in action.
</div>

## Key Features

- Automated media refreshment
- Contamination risk reduction
- Real-time flow monitoring
- PID-controlled precision
- Flexible operation modes
- User-friendly interface

## Technical Implementation

The system integrates various components:
- Raspberry Pi for central control
- Peristaltic pumps for fluid handling
- Flow sensors for precise measurements
- Stepper drivers for motor control
- Custom-designed gantry system