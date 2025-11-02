---
layout: home
---

![headshot](headshot.JPG){: width="300" }

My name is Tom Twomey. I am a PhD student studying computer architecture at the University of Michigan. Below is a brief [bio](#bio), a description of my [research interest](#research-interests), some details on [current](#current-projects) and [past projects](#past-projects), and my [contact info](#contact).

# Bio

## Background
I got my undergraduate education at Virginia Tech attaining bachelor's degrees in computer science and economics. While I was a student I had the opportunity to do research with the [SyNeRGy Lab](https://synergy.cs.vt.edu/) under Dr. Feng looking into productivity of FPGAs in HPC environments. After graduating I spent a couple years with the [Montague Lab](https://fbri.vtc.vt.edu/research/labs/montague.html) developing with deep neural networks to gain insights into neurotransmitter dynamics in awake human brains.

## Resume
You can find my resume [here](Twomey_Resume.pdf).

# Research

I am advised by [George Tzimpragos](https://www.georgetzimpragos.com/) and [Ronald Dreslinski](https://eecs.engin.umich.edu/people/dreslinski-ronald/).

## Research Interests
I am broadly interested in creating intelligent machines and their power requirements. In the near term, I focus on how large data centers interact with the grid; in the longer term, on how brain-inspired architectures may enable more efficient machines.

### Computer Chips as Grid Resources
As data centers become a larger grid load and renewables expand supply, there's an opportunity to operate compute infrastructure as an active grid resource. I'm exploring how chip properties can provide grid services beyond peak shaving.

### Neuromorphic
I am interested in leveraging insights from neuroscience to create computer architectures with more of the brain's desirable characteristics. Specifically, I have been exploring hardware implementations of effective local learning rules and how sparse spatio-temporal encodings impact architectural decisions and 3D scaling.

## Current Projects:

### Dynamic Voltage and Frequency Scaling enabled Virtual Inertia
In this project I am exploring how manipulation of GPU (or other accelerator) frequency and voltage can be used to create virtual inertia services. Further, I aim to quantify the amount of virtual inertia that can be provided with minimal impact on service level objectives and the associated economic value.

## Past Projects:

### Race Logic in Image Sensing
This project explored race logic applications in vision sensors. Race logic encodes values using signal transition times, replacing costly analog-to-digital converters with simpler analog-to-time converters. The resulting temporal signals enable low-power time-domain processing before converting reduced information to binary digital form. We explored hand-tuned feature extraction (edge detection, FAST) and ML-based approaches (local binary comparison networks, binarized activation networks).

Relevant Publication:  
[SEAL: A Single-Event Architecture for In-Sensor Visual Localization (ASPLOS 2025)](https://dl.acm.org/doi/10.1145/3695053.3731034)

### Deep Learning for Fast Scan Cyclic Voltammetry
I was part of a long running project that is measuring neurotransmitter dynamics using probes in awake human participants during brain surgery. We used a technique called Fast Scan Cyclic Voltammetry (FSCV) that induces a specific voltage waveform and measures the resultant current. During my time on the project I lead development and testing of new machine learning architectures for the task as well as the use of existing models for inference on new experiments.

Relevant Publications:  
[Deep Learning Architectures for FSCV, a Comparison (Preprint 2022)](https://arxiv.org/abs/2212.01960)  
[Noradrenaline tracks emotional modulation of attention in human amygdala (Current Biology 2023)](https://www.cell.com/current-biology/fulltext/S0960-9822(23)01355-6)  
[Dopamine and serotonin in human substantia nigra track social context and value signals during economic exchange (Nature Human Behaviour 2025)](https://www.nature.com/articles/s41562-024-01831-w)  

## Publications

A full list of my publications is available on [my google scholar page](https://scholar.google.com/citations?user=p5aVCyIAAAAJ&hl=en).

# Contact

You can reach me by email at [ttwomey@umich.edu](mailto:ttwomey@umich.edu).
