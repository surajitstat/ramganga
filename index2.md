---
title: "Getting started with the Documentation Theme for Jekyll"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with the theme. The other topics in this help provide additional information and detail about working with other aspects of this theme and Jekyll.
---


![alt-text-1](images/uog.png){:height="50px"}  ![alt-text-2](images/uos.png){:height="50px"}  ![alt-text-2](images/ceh.png){:height="36px"} ![alt-text-2](images/jhi.png){:height="50px"} ![alt-text-2](images/iitk.png){:height="50px"} 

<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
   {% for item in site.data.samplelist.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>





<nav id="navbar" class="collapse navbar-collapse">
    <ul class="nav navbar-nav">
        {% assign links = site.data.navigation %}
        {% for link in links %}
            {% assign class = nil %}
            {% if page.url contains link.url %}
                {% assign class = 'active' %}
            {% endif %}
            {% if link.sublinks %}
                <li class="dropdown {{ class }}">
                    <a href="{{ site.url }}{{ site.baseurl }}{{ link.url }}" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">{{ link.title }} <span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        {% for sublink in link.sublinks %}
                            {% if sublink.title == 'separator' %}
                                <li role="separator" class="divider"></li>
                            {% else %}
                                <li>
                                    <a href="{{ site.url }}{{ site.baseurl }}{{ sublink.url }}">{{ sublink.title }}</a>
                                </li>
                            {% endif %}
                        {% endfor %}
                    </ul>
                </li>
            {% else %}
                <li class="{{ class }}">
                    <a href="{{ site.url }}{{ site.baseurl }}{{ link.url }}">{{ link.title }}</a>
                </li>
            {% endif %}
        {% endfor %}
    </ul>
</nav>



![Image](https://www.gla.ac.uk/media/Media_681177_smxx.jpg){:width="100%"} 

## Welcome to Ramganga Website

Empowering social inclusion through 'improving access to clean water and sanitation' for all requires a robust understanding of water-related ecosystems and the benefits that they can provide to society.

However, 'the global data currently collected through the SDG process do not reflect the general state or trends known about freshwater ecosystems'. Novel mathematical sciences research is essential to enable fusion of Earth observation and on-the-ground data sources to fill the knowledge gaps, provide improved understanding of water quality and address the water management challenges faced by developing countries. This proposal will deliver world leading statistical research supporting the development of a water quality monitoring and modelling framework for the Ramganga sub-basin of the Ganges river basin.

Traditional water sampling is based on a small number of sites, and is very labour intensive and expensive, and our proposal brings together data from new in-situ sensors, delivering data at high temporal frequency, coupled with intensive coupling high-end in-situ above and below water characterisation of the biogeo-optical properties of the Ramganga with measurements from calibrated miniaturised hyperspectral imaging radiometers deployed from drones, and data from new satellite missions (Sentinel 2). Together, these provide an efficient and unprecedented means of collecting significant data across a range of environments and pollution discharge scenarios of optical water types in the Ramganga basin. Coupling these data with conventional measures of WQ will provide the much desired framework for extrapolating WQ data at hitherto unachievable spatial and temporal resolutions.

Covering 26% of India's total landmass, water quality and water resources in the Ganges basin are vital

for the wellbeing of one of the largest and densest global populations (43% of India's population).

However, they are being compromised due to activities such as rapid industrialization and

urbanization, and mitigation efforts are hampered by lack of historical and contemporary discharge and quality data. This project will develop and implement new statistical methodology specifically for the Ramganga sub-basin to integrate the new and existing water quality data with remote sensing satellite data (both historical data from multiple sensors and new retrievals from recent Sentinel missions).



To address the water quality challenges in the Ramganga sub-basin and to fully utilise the new data streams, novel statistical downscaling and data fusion methodologies through a varying coefficient, hierarchical Bayesian modelling framework will be developed to incorporate river network structure and model quantiles of flow. These approaches support integration of disparate data sources to enable prediction of water resource condition and associated uncertainties to inform risk-based modelling under a range of socio-economic and climate change scenarios, and provide tools to inform future monitoring design. The output of catchment-wide WQ estimates will be made available to policy makers and future researchers to guide policy and design future sampling sites and temporal frequency.


## Collaborators
* Glendell, Dr M 	
* Hunter, Dr P D 	
* Sinha, Professor R
* Read, Dr DS 	
* Bowes, Dr M 	
* Scott, Professor M
* Miller, Dr CA 	
* Helliwell, Dr RC 	
* Tyler, Professor AN

## Meetings and Event

* First Meeting -- October 30th, 2019
* Second Meeting -- November 22nd, 2019

## Funder 

[Link to project on EPSRC-GOW](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/T003669/1)  


## Partner institutions

---
![alt-text-1](images/uog.png){:height="50px"}  ![alt-text-2](images/uos.png){:height="50px"}  ![alt-text-2](images/ceh.png){:height="50px"} ![alt-text-2](images/jhi.png){:height="50px"} ![alt-text-2](images/iitk.png){:height="50px"} 

---

## Supporting partners
---
![alt-text-1](images/iukwc.png){:height="50px"}  ![alt-text-2](images/nmcge.jpg){:height="50px"}   ![alt-text-3](images/aqua-watch-logo.png){:height="50px"}  ![alt-text-4](images/mahseer.png){:height="50px"}

---



