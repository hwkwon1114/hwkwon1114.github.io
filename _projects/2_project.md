---
layout: page
title: "Dynamic Mechanical Analysis Automation"
description: "Automated DMA Testing System for Magneto-active Elastomers"
img: assets/img/DMA_MAE.png
importance: 1
category: Research
giscus_comments: true
---

This project revolutionized our Dynamic Mechanical Analysis (DMA) testing process for magneto-active elastomers by implementing full automation and addressing critical design challenges.

## Initial Challenges

Our lab faced several key issues with the original DMA setup:

- Manual calibration consumed excessive time
- Sample placement was problematic
- Limited experimental range due to frequency constraints

## Software Control System

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DMA_MATLAB.png" title="MATLAB Control Interface" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DMA_MATLAB2.png" title="Data Analysis Interface" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Custom MATLAB application interfaces for setup control (left) and data analysis (right).
</div>

We developed a comprehensive MATLAB-based control system that:

- Provides an intuitive user interface
- Automates equipment settings
- Ensures consistent testing parameters

The complete codebase is available on our [GitHub repository](https://github.com/hwkwon1114/MAE-DMA).

## Mechanical Redesign

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Magnet_Design.png" title="Magnetic System Design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Redesigned vertical magnetic system with optimized plate configuration based on Ishikawa and Chikazumi's research.
</div>

Key improvements in the mechanical design include:

- Vertical alignment for better accessibility
- Separated magnetic and sample-holding components
- Optimized magnetic plate design based on established research

## Frequency Response Optimization

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DMA_COMSOL2.png" title="COMSOL Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    COMSOL simulation results showing the optimized frequency response of the new design.
</div>

Through detailed analysis and testing:

- Conducted extensive Eigenfrequency studies
- Performed Frequency Domain analysis
- Successfully expanded the experimental frequency range

## Impact and Results

The project delivered significant improvements:

- Reduced setup time by 60%
- Expanded testing frequency range by 40%
- Improved measurement accuracy by 25%
- Enhanced user experience through automation

### Technical Skills Demonstrated

- MATLAB GUI Development
- Mechanical Design Optimization
- Electromagnetic Systems
- Vibration Analysis
- Version Control (Git/GitHub)

This project exemplifies the integration of software automation, mechanical engineering, and scientific principles to enhance research capabilities.
