---
layout: meeting
title: FLAME User Meeting - 23rd Feb 2012

user_talks:
  - talk:   SPICE Project
    instut: USFD
    author: Twin Karmakharm
    pdf:
    
  - talk:   Computational Modelling of Galaxy Formation using FLAMEGPU
    instut: USFD
    author: Laurence James
    pdf:

  - talk:   "Playing with Fire: putting FLAME on the XBox"
    instut: UWE
    author: Simon Scarle
    pdf:    /meetings/pdf/FLAME_SCARLE.pdf

  - talk:   Modelling the IL-1 Stimulated NFkB Intracellular Signalling Pathway using FLAME
    instut: YORK
    author: Richard Williams
    pdf:
    
  - talk:   The Effect of Ras-mediated Cytoskeletal Alterations on Dynamics of the NFkB pathway
    instut: USFD
    author: Gavin Fullstone
    pdf:    /meetings/pdf/Gavin.pdf
    
  - talk:   Developing Models of the Blood Brain Barrier
    instut: USFD
    author: Gavin Fullstone
    pdf:    /meetings/pdf/Gavin.pdf
    
  - talk:   "Regulation of Erk1/2 and p38 MAPK pathways via Trb protein family: an agent based approach"
    instut: USFD
    author: Aban Shuaib
    pdf:    
    
  - talk:   Modelling Natural Killer cell interactions with Tumour cells
    instut: USFD
    author: Dave Rhodes
    pdf:    /meetings/pdf/Rhodes.pdf
    
  - talk:   Modelling the epidermis
    instut: USFD
    author: Shannon Li
    pdf:    /meetings/pdf/Modelling_the_epidermis.pdf
    
  - talk:   AirPROM Project
    instut: USFD
    author: Mark Burkitt
    pdf:   
    
  - talk:   SUMO Project
    instut: USFD
    author: Afsaneh Maleki-Dizaji
    pdf:  
    
  - talk:   Tissue Engineering and Bioprocessing
    instut: OXFD
    author: Himanshu Kaul
    pdf:  
    
  - talk:   SIR Model
    instut: STFC
    author: David Worth
    pdf:    /meetings/pdf/SIR_model.pdf

  - talk:   Development of novel 3D MND model by use of aligned polymer fiber scaffolds
    instut: USFD
    author: Candy Ho
    pdf:    /meetings/pdf/CandyHo.pdf
   
  - talk:   Economic and Environmental Policy Modelling
    instut: XIAN
    author: Bob Lee
    pdf:    /meetings/pdf/BobLee.pdf

---

#### Location: Enterprise Zone, Sheffield University

### Programme

**Now starting at 11am to allow travel time**

## 11am
* Coffee and Tea
* Welcome - Mike Holcombe (USFD)
* FLAME HPC Project Objectives - Chris Greenough (STFC)
* The Future of FLAME - Lee-Shawn Chin (STFC)

----

## 12.30pm
* Lunch which will be provided

----

## 1pm

**User Tools:**

* Simon Coakley (USFD) - 'FLAME Editor and FLAME Visualiser demos'
* Sander van der Hoog and Philipp Harting (UNIBI) - 'An extensive GUI for FLAME: experiment setup and data visualisation'
* Julio Gallardo and Chris Wright (USFD) - 'The MASTER testing framework'


**FLAMEGPU:**

* Daniela Romano (USFD) - 'Pedestrian and Traffic Simulation using FLAMEGPU'

----

## 2pm

**Short User Talks:**

<ul>
{% for talks in page.user_talks %}
        <li>
        {% if talks.pdf %}<a href='{{ talks.pdf }}'><img src="/media/blueprint/plugins/link-icons/icons/pdf.png" alt="pdf" width="16" height="16" /></a>{% endif %}
        {{ talks.author }} ({{ talks.instut }}) - '{{ talks.talk }}'
        </li>
{% endfor %}
</ul>

----

## 3pm

* Coffee and Tea
* Feedback to developers
* Conclusions and summing up

----

> **Key:**
> * USFD - University of Sheffield  
> * STFC - Science and Technology Facilities Council - Rutherford Appleton Laboratory  
> * UNIBI - University of Bielefeld, Germany
> * YORK - University of York  
> * UWE - University of the West of England  
> * OXFD - University of Oxford  
> * XIAN - Xi'an Jiaotong University, China  

---

Updated: 2012/02/22
