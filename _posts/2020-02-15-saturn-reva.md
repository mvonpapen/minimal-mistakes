---
title: "Why Space Physics is Awesome"
excerpt_separator: "<!--more-->"
categories:
  - Saturn
tags:
  - Saturn
  - Cassini
---

The awesome thing about space physics is that from just three lines you can determine the state and dynamics of a distant planet's magnetosphere. Just look at this figure showing Revolution A of the Cassini spacecraft from October 2004.

{% capture fig_img %}
![Foo]({{ "/assets/images/saturn_case_study_revA.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Magnetic field measurements (top; total magnetic field strength |B| with radial, polar and azimuthal components) and their wavelet spectral densities (below; parallel and perpendicular fluctuations) of Cassini during an inbound leg in October 2006. Shown are measurements from about 17 Rs up to 9Rs (Rs = Saturn radii) that can be separated into three regions. A: Current sheet crossings, B: Quiet magnetosphere, and C: Flux-tube interchanges.</figcaption>
</figure>

Here we can actually see that Cassini first flies through a very turbulent region (A), which is the current sheet of the magnetosphere crossing over Cassini multiple times (sign changes in B_phi). Then it gets a little quiter (B) as Cassini remains above the magnetic equator. Closer to the planet we then observe fluxtube interchanges (C), where dense plasma that is frozen-in with the magnetic field lines is thrown outside.

How cool is that? If you're really interested, you can read

von Papen, M., Saur, J., & Alexandrova, O. (2014). Turbulent magnetic field fluctuations in Saturn’s magnetosphere. Journal of Geophysical Research: Space Physics, 119(4), 2797–2818. https://doi.org/10.1002/2013JA019542
