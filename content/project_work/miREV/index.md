---
title: miREV
summary: Meta-analysis of EV isolates from human blood.
tags:
- PhD
date: "2020-08-19T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo of zeros and ones
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Click [**here**](http://141.40.217.80:3838/miREV/) to get to miREV app.

**Description:**
   
Extracellular vesicles (EVs) such as Exosomes are small membrane-enclosed vesicles that are released in all body fluids by a variety of cells. In addition to specific protein and DNA cargo, EVs have been shown to be specifically enriched in miRNAs . Due to their aberrant expression under different physio- and pathophysiological conditions, miRNA have emerged as a promising source of biomarkers.
miREV is an easy to use web tool especially designed to discover potential biomarker candidates as well as stable reference transcripts from miRNA Sequencing Data. Data from publicly available sources comprising a large variety of different species, tissues and diseases was collected and processed to exclude poor quality data and reads mapping to other RNA species (e.g. rRNA, tRNA).
In total 654 samples from 13 studies with 15 different physiological and pathophysological conditions were incorporated. 415 samples remained after the strict filtering procedure. To account for variable analysis setups, count lists were normalized by 6 commonly used normalization methods for abundance analyses and potential, stably expressed reference transcripts were evaluated by 3 different established algorithms. General information about individual normalization and stability strategies can be found in the corresponding tabs.
    
miREV is interactive. Users can define experimental and methodological input variables, to match the output as close as possible to their desired experimental setups. By specifying different ‘Species’ , ‘Biofluids’ , ‘EV-Isolation Methods’ or ‘Diseases’ , a user-specific sample set is created and abundant as well as stable miRNA are visualized.
    
How to use miREV: Start by defining your experimental conditions to select a sample set. Going to the next tab ‘PCA and Readcounts’ , you can download expression values and get a quick overview of your sample distribution by principal component analysis. Finally, on the last tab ‘Stable References’ , the most stable miRNAs in your data set are displayed. Differences and similarities between normalisations and stability algorithms are visualized as well to allow easier identification of reference candidates.