---
title: "CIERA REU Research"
excerpt: "My work at CEIRA"
collection: CIERA-REU
---

In a few weeks, the fourth Gravitational Wave Transient Catalog (GWTC-4) will be released. This includes the combined observations from O1, O2, O3, and O4 of the 
LIGO-Virgo-KAGRA, cite detectors. But what are gravitational waves?

When two black holes, two neutron stars, or a black whole and a neutron star combine and merge, there is an extreme distortion of space-time due to the immense gravity of these objects. This violent warping of space-time, along with the motion of the two celestial objects, results in ripples being sent out through the cosmos. These are called gravitational waves. The LVK detectors can observe these waves.

These gravitational wave observations include a multitude of merger events from binary black holes (BBHs) and binary neutron stars (BNs), however, for the purposes of this paper, we are only interested exploring  the BBH population, so BNs and NSBH are omitted . In this paper, we will use these BBH observations to infer properties about the BBH population in the broader Universe. (When the project is farther along, hopefully I can add things like how I've restricted observations to only those with less than a certain thresh-hold false alarm rate (FAR), to avoid inaccurate data. Hopefully I can also add how many events I'm actually using. We haven't done this yet but plan to)

Many models have been made to conduct population inference on BBHs; in this paper, we explore a newer and more flexible model. Understanding the distribution of mass ratios for BBH mergers provides key insights into how these mergers form. For example, models of isolated BBH merger events produce near-equal mass binaries whereas dynamical formation channels allow for more extreme mass ratio distributions. But what is hierarchical Bayesian inference? 

For readers unfamiliar with Bayesian inference, it is a framework for updating our knowledge (or beliefs) about a model given data  and prior expectations. 
Hierarchical Bayesian inference is a statistical framework that allows us to model the population distribution of binary black holes by combining information from individual events. We compute posterior distributions on population-level parameters using observed event posteriors and a selection function. Essentially, this approach lets us use what has been observed to constrain what is likely true about a more broad population within a well-defined confidence interval.

