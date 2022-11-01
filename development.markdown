---
layout: page
title: Development
permalink: /development/
---

The RAMP project is currently undergoing extensive further development, jointly led by TU Delft, the Reiner Lemoine Institut and the VITO Research center. 

The ambition is to make available a **'next-gen' version** of the tool: more user-friendly, installable via pip, more easy to customise for different [applications](/applications)!


<div style="background-color: #EAEAEA; text-align:left; vertical-align: middle; padding:20px 20px;" width="350">
<h style="color: "><b>Highlights from the ongoing next-gen development process</b></h>
<img src="/assets/logos_dev.png" width="150" align="right" class="pad-top-left"/>

<br>
<br>
<p>Already done and available in the <a href="https://github.com/RAMP-project/RAMP/tree/development">'development'</a> branch of the main RAMP repository:
<br>
<ul>
  <li>inputs can be defined in an Excel spreadsheet</li>
  <li>input parameters are better defined and described in the code</li>
</ul>
</p>

<p>Done in the <a href="https://github.com/rl-institut/RAMP/tree/feature/change-output-format">RLI fork</a>, soon to be merged in the main RAMP repository:

<ul>
  <li>profiles can be generated for a whole year with monthly seasonality</li>
  <li>it is possible to provide a date range (start, end) to generate a profile within it</li>
  <li>outputs can be automatically resampled to hourly resolution based on either min, max, or mean resampling rules</li>
</ul></p>

<p>Work-in-progress:
<br>

<ul>
  <li>expanded documentation</li>
  <li>parallel processing</li>
  <li>code speedup (vectorising operations)</li>
  <li>MonteCarlo simulation to get input parameter uncertainty ranges</li>
  <li>figure of merit to compare two ramp runs</li>
  <li>making the code a Python package installable via pip</li>
  <li>bringing back together the various RAMP applications (e.g., RAMP-mobility) as customisation options that all build on the same stochastic 'engine'</li>
</ul></p>
</div>
<br>

Do you have great ideas about further things to implement? Do you want to join the next-gen developmet? 
Then get in touch on our [Gitter chat](https://gitter.im/RAMP-project/community)!

