---
layout: page
permalink: /research/index.html
title: My Research
description: An overview of my research interests and experience.
tags: [research]
image:
  feature: satellites.jpg
---

I am interested in what satellite remote sensing can teach us about planetary atmospheres. 

To me, this topic occupies a natural interface between astrophysics and atmospheric science, the fields of my previous research. In the most basic terms, I am fascinated by the idea that we can learn new (and obscure!) things about a planet, just by looking at it from space.

Space-borne instruments have the unique ability to characterize entire planetary atmospheres in a matter of hours or days. As such, they grant access to abundances of information about the Earth and other planets that would otherwise be out of reach to us---but only if they can be reliably interpreted. Fortunately---or unfortunately, depending on how you look at it---the scientific value of satellite data is often mostly limited by our powers of interpretation, and there is still a great deal of progress to be made in this regard. This is what motivates me in my research.

<!-- Satellite data is like a mine; what you get out of it is largely dependent on how deep you can dig. Depth, in this analogy, is limited by our powers of interpretation. -->

Interpreting satellite data is an inverse problem; you start with some measurements of a system, and attempt to deduce what the state of the system must have been for you to have made those measurements. Often the problem is under-determined; there may not be a unique state that produces your measurements. However, as outlined in Clive D. Rodgers' textbook <i>[Inverse Methods for Atmospheric Sounding](https://books.google.be/books/about/Inverse_Methods_for_Atmospheric_Sounding.html?id=dW-0QgAACAAJ&redir_esc=y)</i>, it is possible to determine the most likely state of the system via Bayesian minimization of a cost function. 

When the system under scrutiny is an atmosphere and the measurements come from a satellite, there are two inverse problems that are of special interest to me. The first is the problem of inferring the global distribution of a trace gas from the satellite spectra, in which case the goal is to determine the concentrations of the gas at different locations around the planet, given some knowledge of how light interacts with chemicals in the atmosphere. The second is the problem of constraining emissions of the trace gas, given the map of concentrations produced in the first problem and a chemical transport model. I hope to explore both of these problems in depth during my PhD studies.

- - - 

### First steps in atmospheric science...

My first research project was also my introduction to atmospheric science. In the summer of 2011 I took an undergraduate RA position in [Professor Shaun Lovejoy's](http://www.physics.mcgill.ca/~gang/Lovejoy.htm) climate physics group at McGill, where I learned the importance of scale in understanding climate. Over the course of two years, I looked at how various general circulation models (GCMs) predicted temperature should fluctuate on different time scales, from hours to centuries. 

In principle, one should expect to see relatively large variability at time scales that are comparable to the lifetimes of typical weather systems (on the order of a few hours or days). Zooming out to the scale of months or a few years, however, and removing seasonal trends, variability should decline as fluctuations due to weather average out. Finally, on time scales from decades to centuries and millennia, temperature variability must rise again to reflect, for example, glacial-interglacial cycling. Professor Lovejoy calls these scaling regimes weather, macroweather, and climate, respectively, and each has different statistical properties, as demonstrated in this figure:

<figure>
	<img src="/images/macroweather.png">
	<figcaption>Different scaling regimes. Bottom two panels reflect weather variability, second from top macroweather variability, and top climate variability. Each time series is 720 points long, has had its mean subtracted, and is normalized by its standard deviation. Resolutions from bottom to top are 0.067 seconds, 1 hour, 20 days, and 100 years. From <a href="http://www.earth-syst-dynam.net/4/439/2013/esd-4-439-2013.html">Lovejoy et al. 2013</a>.</figcaption>
</figure>
