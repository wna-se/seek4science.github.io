---
permalink: /index.html
title: 'Seek4Science'
layout: splash
classes:
    - wide

row1:
  - image_path: /assets/images/ISA-feature.png
    alt: "ISA"
    title: "Organise and store data"
    excerpt: "SEEK has adopted an ISATAB style structure for organising experiments and data."
    url: "/organise.html"    
  - image_path: /assets/images/Excel-feature.png
    alt: "Explore and annotate"
    title: "Explore and annotate data"
    excerpt: "Excel spreadsheets can be explored and annotated without the need to download."
    url: "/explore_and_annotate.html"    
  - image_path: /assets/images/Model-simulation-feature.png
    alt: "Simulate SBML"
    title: "Simulate SBML models"
    excerpt: "Most models that conforms to the SBML format can be simulated within SEEK."
    url: "/simulate_sbml.html"
    
row2:
  - image_path: /assets/images/Who-feature.png
    alt: "Who is doing what"
    title: "Who is doing what, where?"
    excerpt: "We recognise that people, and their knowledge, are important."
    url: "/yellow_pages.html"    
  - image_path: /assets/images/Sharing-feature.png
    alt: "Sharing"
    title: "Flexible sharing controls"
    excerpt: "There is a lot of flexibility and control over who can see, download or edit your items."
    url: "/flexible_sharing.html"    
  - image_path: /assets/images/Rightfield-feature.png
    alt: "Rightfield"
    title: "Semantic templates"
    excerpt: "RightField enabled sheets allow rich semantic descriptions of data. Our Just Enough Results Model can be used with Rightfield."
    url: "/rightfield_templates.html"    
  

---

<div id='intro-text' markdown='1'>

![SEEK_logo](/assets/images/seek-logo.svg){: #front-screen-logo}


SEEK is a web-based cataloguing and commons platform, for sharing heterogeneous scientific research datasets, models or simulations, processes and research outcomes. 
It preserves associations between them, along with information about the people and organisations.


Underpinning SEEK is the [ISA infrastructure](http://isa-tools.org/), a standard framework for describing how individual experiments are aggregated into wider studies and investigations. 
Within SEEK, ISA has been extended and is configurable to allow the structure to be used outside of Biology.


Flexible and detailed sharing permissions are available to manage the catalogued items from early collaborations within projects, 
through to the publishing of final research results. At this point a DOI can be generated for individual items, or entire aggregates packaged as [Research Objects](http://www.researchobject.org/)


SEEK incorporates semantic technology, allowing sophisticated queries over the content. 
Metadata can be collected using standard Excel tools and processes, through the use of [RightField](http://rightfield.org.uk/).

A publically available instance of a SEEK commons is available - as the [FAIRDOMHub](https://fairdomhub.org).

[![Fairdomhub](/assets/images/fairdomhub-logo.svg){: #fairdomhub-logo}](https://fairdomhub.org)

</div>

{% include feature_row id="row1" %}

{% include feature_row id="row2" %}