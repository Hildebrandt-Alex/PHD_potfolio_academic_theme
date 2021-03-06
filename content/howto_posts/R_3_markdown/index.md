---
title: R Markdown
summary: Writing reports, presentations and dashboards with R Markdown
tags:
- R
date: "2020-08-19T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
#  caption: Photo of zeros and ones
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



### R Markdown:
   
R Markdown can be used to produce good looking documents, reports, presentations and dashboards. Thereby you can use muliple languages like R, Python adn SQL. [__Here__](https://rmarkdown.rstudio.com/) is the official site.

### Cheat Sheet

[__Click here__](https://raw.githubusercontent.com/rstudio/cheatsheets/master/rmarkdown-2.0.pdf) to be forwarded to the R Markdown cheat sheet

### Producing a .html document with tabs

If you want to present your report as a .html file you can use tabs to structure the content.
![Fig. 1. Content of HTML document structured with tabs.](/R_pictures/rmarkdown_html_tabs.PNG)

This is the code for the rmarkdown file: 

    ---
    title: "structure your content with tabs"
    subtitle: ""
    author: "Author"
    date: "`r format(Sys.time(), '%d %B, %Y')`"
    output: html_document
    ---
    
    
    
    ### First Title of the report
    
    ##  {.tabset}
    
    ### First Tab 
    
    **Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.** 
    
    ***
    
    ### Second Tab 
    
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
    
    
    ### Third tab
    
    **Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.**
    
    
    
    ##{-}
    
    ### Second title of the report
    
    ##  {.tabset}
    
    ### First tab
    
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    
    
    ### Second tab
    
    __Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.__
    
    ##{-}
      