---
layout: splash
author_profile: false                                                                                             
classes:
  - landing

date: 2017-09-13
header:
  overlay_color: "#C0C0C0"
  overlay_filter: "0.5"
  overlay_image: /assets/screenshots/2017-07-31_V3.0.4_SignalProcessing.png
  cta_label: "Download"
  cta_url: "/#downloads"
  caption: "Screenshot: LIISim V3.0.4 BETA - SignalProcessing"
  
excerpt: "A modular signal processing toolbox for laser-induced incandescence (LII) measurements"


feature_row:
  - image_path: /assets/screenshots/2017-07-31_V3.0.4_SignalProcessing.png
    alt: "SignalProcessingEditor"
    title: "SignalProcessing"
    excerpt: "The modular signal processing toolbox allows processing of raw signals, 
    absolute signals and temperature traces. Processing steps can be individually 
    set and arranged. Intermediate processing results can be visualized and analyzed with various plot tools."
    url: "/assets/screenshots/2017-07-31_V3.0.4_SignalProcessing.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"


feature_row2:    
  - image_path: /assets/screenshots/2017-07-31_V3.0.4_AToolTemperature.png
    alt: "placeholder image 2"
    title: "AnalysisTool: Temperature Fit"
    excerpt: "Visualization of spectral temperature fitting using Planck's law. Temperature traces, 
    which are calculated in the SignalProcessing module can be analyzed and all fitting iterations can be visualized."    
    url: "/assets/screenshots/2017-07-31_V3.0.4_AToolTemperature.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"

feature_row3:        
  - image_path: /assets/screenshots/2017-07-31_V3.0.4_ParameterAnalysis.png
    title: "AnalysisTool: Parameter Analysis"
    excerpt: "Experimental data can be sytematically compared for different parameters
     (i.e., laser fluence, LII peak temperature, PMT gain voltage,...)."                                                        
    url: "/assets/screenshots/2017-07-31_V3.0.4_ParameterAnalysis.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"
    
feature_row4:
  - image_path: /assets/screenshots/2017-07-31_V3.0.4_FitCreator.png
    alt: "placeholder image 2"
    title: "FitCreator"
    excerpt: 'Use different heat transfer models and databases for simulation of LII signal
     traces and comparison with experimental data.'                                                                        
    url: "/assets/screenshots/2017-07-31_V3.0.4_FitCreator.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"
    
                     
                                                                                            
#feature_row4:
#  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#    alt: "placeholder image 2"
#    title: "Placeholder Image Center Aligned"
#    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
    
---



**Laser-induced incandescence (LII)** is a non-intrusive method of measuring 
time-resolved soot particle volume fraction and primary particle sizes in flames.
Not only restricted to flames, this technique is recently used for characterization
 of **car engine exhaust**, **atmospheric black carbon** and **synthetic 
nanoparticles**. These new applications require the same basic signal processing, 
but at the same time individual databases for material (soot or non-soot) and 
gas compositions as well as individual heat transfer models for the 
determination of particle sizes. **LIISim** is a framework for basic signal processing 
and analysis of experimental LII data to help researches across the world to compare their 
experimental data. 
                  
**LIISim is a project of** <br>
<a href="http://www.uni-due.de" target="_blank"><img src="/assets/logos/UDE_logo_claim_72dpi_rgb.jpg"
alt="University of Duisburg-Essen" style="height:70px"></a>
<a href="http://www.uni-due.de/ivg/rf" target="_blank"><img src="/assets/logos/IVG-Reactive-Fluids.png"
alt="Institute for Combustion and Gas Dynamics - Reactive Fluids" style="height:89px"></a>


The old LIISim.com web interface (by Max Hofmann) can be found [here](http://web.liisim.com/){:target="_blank"}. 
{: .notice--warning}
                  
## Motivation

LIISim is designed to provide transparent and flexible tools, which allow individual 
setting of processing parameters, visualization of intermediate processing steps, and 
comparison of multiple experimental data sets.

Main features:
- modular choice of user-defined material properties (soot, silicon, germanium,...)
- comparison of experimental data with different pre-implemented heat-transfer models
- easy-to-use import (TXT/CSV) and export (TXT/CSV/MATLAB) functionalities
- copy/paste of signals and analysis results into spreadsheet software (MATLAB, Excel, Origin,...)
- software architecture allows processing and comparison of large data sets (> 4 GB) 
- various analysis tools help visualizing dependencies between experimental data sets (plots, parameter comparison, statistical information)


## Screenshots
                                                                                                              
{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}



## Documentation

| Document | Version | File|
| ------------------------------------------- | ----------------------------------------------------- |
| User manual | 0.0.0  | [not yet available](){: .btn .btn--primary } |
| Developer's guide | 0.0.0 | [not yet available](#){: .btn .btn--primary } |


## Downloads

We are currently in BETA development phase, release is scheduled for Spring 2018. Please feel free to request a BETA release for testing purposes.
{: .notice--info}

Pre-compiled binaries are available for Windows 7/8/10 platforms (32bit and 64bit). 

| Platform | Version | File|
| ------------------------------------------- | ----------------------------------------------------- |
| Windows 7/8/10 (x64) | 3.0.4 (BETA) | [Request BETA version](mailto:raphael.mansmann@uni-due.de?subject=LIISim%20BETA%20request%20&body=Hi%20Raphael%2C%0A%0Aplease%20send%20me%20a%20BETA%20version%20of%20LIISim%20for%20testing.){: .btn .btn--info } |
| Windows 7/8/10 (x32) | 3.0.4 (BETA) | [Request BETA version](mailto:raphael.mansmann@uni-due.de?subject=LIISim%20BETA%20request%20&body=Hi%20Raphael%2C%0A%0Aplease%20send%20me%20a%20BETA%20version%20of%20LIISim%20for%20testing.){: .btn .btn--info }|


## Source
The latest source code can be obtained from [GitHub](https://www.github.com/LIISim/LIISim3). Please see the developer's guide for further instructions on compiling the source code and required libraries.


## About

**LIISim is a project of** <br>
<a href="http://www.uni-due.de" target="_blank"><img src="/assets/logos/UDE_logo_claim_72dpi_rgb.jpg"
alt="University of Duisburg-Essen" style="height:70px"></a>
<a href="http://www.uni-due.de/ivg/rf" target="_blank"><img src="/assets/logos/IVG-Reactive-Fluids.png"
alt="Institute for Combustion and Gas Dynamics - Reactive Fluids" style="height:89px"></a>
<br>

**History**<br>
LIISim was so far known as **console application (LIISim 1.5)** and **web interface (www.liisim.com)**, developed by Max Hofmann 
between 2001 and 2007. The console application was written in C and the web interface was based on Perl. 
Modeling settings and file names for experimental data could be defined in DAT files and after execution of the console 
application, DAT output files containing the modeling results are created.         <br>
Later the console application was extended by a C++ based graphical user interface (GUI) by Tobias Terheiden and Martin Leschowski, which allowed the visualization of 
 the modeling results from the DAT files (**LIISim Desktop 1.02** and **LIISim Console 2.14**). While the console application was distributed
 among the community, the desktop version was not published and was only internally used.  <br>
In 2013 the development of **LIISim 3** a new framework with object-oriented structure based on C++ was started by Raphael Mansmann 
designed for the application on individual material systems (soot and non-soot) with a modular implementation of signal 
processing steps and choice of heat-transfer models.
                                                                          
The old LIISim.com web interface (by Max Hofmann) can be found [here](http://web.liisim.com/){:target="_blank"}. 
{: .notice--warning}
  
<b>Authors</b> <br>
Raphael Mansmann [<img src="/assets/logos/In-2C-14px.png" style="height:15px">](https://www.linkedin.com/in/mansmann){:target="_blank"}
[<img src="/assets/logos/RG_square_green.png" style="height:24px">](https://www.researchgate.net/profile/Raphael_Mansmann){:target="_blank"}
[<img src="/assets/logos/orcid_16x16.png" style="height:16px">](https://orcid.org/0000-0003-0071-5252){:target="_blank"}
<br>
Tobias Terheiden 
[<img src="/assets/logos/RG_square_green.png" style="height:24px">](https://www.researchgate.net/profile/Tobias_Terheiden){:target="_blank"}
<br>
Philip Schmidt <br>



## License
LIISim is free software: you can redistribute it and/or modify it under the terms 
of the GNU General Public License as published by the Free Software Foundation, 
either version 3 of the License, or (at your option) any later version.

LIISim is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; 
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. 
See the [GNU General Public License](http://www.gnu.org/licenses/){:target="_blank"}  for more details.