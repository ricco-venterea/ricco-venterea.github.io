---
layout: interactive
permalink: /research/
title: "Current Research"
author_profile: true
redirect_from: 
  - /md/
  - /research.html
---

I have many interests at this point, but my main focus is at the intersection of planetary science and millimeter astronomy. See below for high level overviews of my research projects, and see where my research has taken me! (I only describe projects where some form of publication was made).

# Research In Progress

## Cosmic Rays
Cosmic rays are highly energetic particles produced from astrophysical events. The Sun also generates these particles, streaming through earth's atmosphere. Our goal is to increase access to solar cosmic ray particles by developing a website, my current goal. Building on work from my colleague, I am optimizing this website to run quicker, and I plan to implement new models developed by my colleagues. These models predict flux rates, which will be useful for determining radiation dosage rates for astronauts traveling in space. Due to the high energy of these particles, they pose health risks and can also compromise communications equipment when traveling outside earth's atmosphere.

## ACTeroids
Using data collected by the Atacama Cosmology Telescope, we are studying thermal emission flux from asteroids in millimeter wavelengths (from 1 - 3 mm). We have first demonstrated that using high-fidelity observatories to study asteroids is feasible. I generated light curves and phase curves, which demonstrate the change in asteroid flux over time and distance frome earth. Additionally, we found flux discrepancies between infrared and millimeter observations, suggesting an underlying physical process in asteroid subsurfaces. Specifically, we found a flux decifit in S-class asteroids compared to C-class when implementing an asteroid thermal model. While this is currently being investigated, possible reasons could be the presence of temperature gradients or a change in emissivity. More work is needed to better understand what is causing such a deficit. I am currently building a public database that contains nearly 200 asteroid observations.

## QuarkNet
QuarkNet is a program developed by the National Science Foundation to increase science accessibility in high school classrooms. QuarkNet (along with Fermilab) created cosmic ray detectors for high schoolers. As a senior in high school, I developed and performed an experiment to measure the cosmic ray flux of muons as a function of detector angle. We fit the flux data to empirical and theoretical models and found that the detector slightly underestimates flux rates. While this is important for calibrating and using QuarkNet detectors, we emphasize that high schoolers can perform this same experiment. The hope is that wider use of detectors leads to new insights into improving the accuracy of the QuarkNet detectors.

# Past Projects

## Aframe
[Aframe](https://github.com/ML4GW/aframe) is a machine learning pipeline that aims to detect gravitational waves (GW) from compact binary coalescences data. This is the first pipeline using neural networks to run online at low latency. The ultimate goal of Aframe is to make GW astronomy more efficient without compromising sensitivity. We hope Aframe will speed up developments and discoveries in GW astronomy. I created a user interface for future users to examine the distribution of Aframe training parameters, which helps with validating the Aframe algorithms. I was also briefly involved in extending this pipeline to run over a single detector, which would increase data since the current implementation of Aframe requires two running interferometers.
