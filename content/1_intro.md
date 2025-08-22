---
title: Introduction
nav: Introduction
gallery: true
---

<br>

Hello, my name is Andrew Weymouth and I have worked with the University of Idaho Library as the [Digital Initiatives Librarian](https://www.lib.uidaho.edu/about/people/aweymouth.html){:target="_blank" rel="noopener"} in the [Center for Digital Inquiry and Learning ](https://cdil.lib.uidaho.edu/){:target="_blank" rel="noopener"}(CDIL) department since the fall of 2023. My work generally consists of creating and maintaining our digital collections, collaborating on projects with fellowship recipients, helping to rethink processes and introducing new digital scholarship tools to the department.

<br>

## Digital Scholarship Database Application

<br>

One example of a digital scholarship project I've worked on using a database that we will talk more about in a moment is using [Web of Science](https://www.webofscience.com/wos/woscc/basic-search){:target="_blank" rel="noopener"} to create Bibliometrics. This was prompted by my work creating a digital collection for the [U of I's Taylor Wilderness Research Station](https://www.lib.uidaho.edu/digital/taylor-archive/){:target="_blank" rel="noopener"}, a scientific refuge that students have been visiting in the remote Frank Church River of No Return Wilderness since the 1970s.

**Bibliometrics** are the use of statistical methods to analyze books, articles and other publications. The concept for this project was to see if there was some way to visualize all of the academic work that was produced by students and faculty members after conducting research at the station to convey a sense of the institution’s “research impact” over time. 

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

{% include gallery-figure.html img="taylor.jpg" alt="Group of six standing in front of the Taylor Wilderness Research Station wearing clothes indicative of the late 1970s or early 1980s." caption="Arlow Lewis, the caretaker of Taylor Ranch for several years, far left with glasses. Kneeling on left is Jim Bennett, then a PhD student working on bighorn sheep. Carol Bennett is in the yellow top, courtesy U of I Special Collections (DSC_0360)" title="Arlow Lewis, the caretaker of Taylor Ranch for several years, far left with glasses. Kneeling on left is Jim Bennett, then a PhD student working on bighorn sheep. Carol Bennett is in the yellow top, courtesy U of I Special Collections (DSC_0360)" width="100%" %}

<br>

## Approach

<br>

This led me to consider some questions: 

* _What does it mean for a paper to be the direct product of a specific place?_ 

* _Does a work need to mention Taylor by name?_ 

* _Are we only looking at research produced by U of I?_ 

* _How long after the author visits Taylor is it still considered a product of that place?_ 

With this in mind, I decided to zoom out a bit and look at authors from U of I who were simply present in the archive, rather than specific titles.

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

## Network Visualization

<br>

**After creating an author name equation** so I only needed to search for authors in seven batches of 100 names rather than a bleak 737 individual searches, this compiled Web of Science data was then exported in CSV format and then imported into [VOSviewer](https://www.vosviewer.com/), a Dutch, open-source network visualization platform with excellent documentation and an intuitive interface.

{% include gallery-figure.html img="biblio_01.gif" alt="Data visualization of multi-colored nodes against a black background labeled with the names of authors." caption="Visualization of citation impact over time of authors that contributed to work found in the Taylor Wilderness Research Station digital archive. Node size indicates the number of times the work has been cited, color and distance indicates groups formed by subject and keyword likeness and lines connecting nodes indicates shared citations."  title="Visualization of citation impact over time of authors that contributed to work found in the Taylor Wilderness Research Station digital archive. Node size indicates the number of times the work has been cited, color and distance indicates groups formed by subject and keyword likeness and lines connecting nodes indicates shared citations." width="100%" %}

I wanted to analyze: 

* [future citations](https://www.lib.uidaho.edu/digital/taylor-archive/citation.html) of specific documents 

* [co-authorship of papers](https://www.lib.uidaho.edu/digital/taylor-archive/coauthorship.html), and 

* [fields of interest](https://www.lib.uidaho.edu/digital/taylor-archive/keywords.html) over time. 

Once these three visualizations were completed, further customization was done adjusting node color to represent scientific discipline, size to represent the number of times the work has been cited, and arrangement according to when they were published. Selecting a node brings up a pane on the lower right hand corner of the screen which reveals more details on the title and, if available, creates a link to the research paper itself.

These visualizations were then embedded into our CollectionBuilder site using the [VOS-Viewer Online](https://github.com/neesjanvaneck/VOSviewer-Online) function. While these do take a short while to process the JSON data on loading, the bibliometrics add a colorful and interactive element that reduces a daunting amount of scholarly work into a single visualization.

<br>

## Goals

<br>

The intention of this workshop is to walk you through all of the resources the library has to offer, the best search strategies to use with them and end with some recommendations for how to store, annotate and preserve your research for future reference. While the previous example might be more complicated, I hope it illustrates how you can not only find research material with these databases, **but also generate research**. 

<br>

