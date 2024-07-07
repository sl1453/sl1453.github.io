---
layout: page
title: Cell Behaviors
subtitle: Cell Culture, Imaging, Statistics ++
---

## Introduction

Studying cells has been a essential part of both my Master's research and my Ph.D. projects. In my Master's project, I utilized mammalian cell cultures to investigate the mechanisms of small molecule-mediated tagged protein degradation. My Ph.D. research also heavily involves working with cells, this time, motile cells. I study a protozoan parasite called _Giardia_.

I will discuss my Master's project on the "Chemical Bio" page. This page focuses on the work from my Ph.D. research, exploring how _Giardia_ responds to physiological-relevant mechanical cues.


## General Goal of My Ph.D. Research  
    
I study _Giardia_ trophozoites in environments with varying viscoelastic properties that mimicing their host environments during infection. To investigate these motile cells, I developed micro-culture systems that enable systematic imaging of the culture over a time course of growth. This research required conducting live cell imaging using various advanced methods, including confocal and spinning disk microscopy.

![Giardia Cell Image](/assets/img/GeoSpatialCellResearh/GiardiaPic.gif)  
*Figure 1: Confocal image of a _Giardia_ trophozoite in culture.*

## GeoSpatial Analysis Approach

One of the challenges was to analyze the attachment patterns of _Giardia_ trophozoites. I adopted a method commonly used in GeoSpatial research to analyze point pattern distributions, applying these statistical techniques to study the spatial attachment patterns of the cells.

### R Language and Data Analysis  
  
One of my key strengths is my willingness to engage with people from different labs and departments, and my adaptability in taking on various roles. For this particular challenge, I was inspired by the methods often used by geo-scientists, which differ significantly from the traditional experimental approaches usually used by biologists. This adaptation led me to teach myself R programming for processing biological images and performing statistical analyses. Here are some examples of the analyses I conducted:

### Probability Heatmaps

Using point intensity probability heatmaps, I was able to visualize the attachment patterns, providing insights into cell responses to fluid mechanics. Example plot:

![Probability Heatmap](/assets/img/GeoSpatialCellResearh/SamplePlot_Point_Intensity_Probability.jpg)  
*Figure 2: Probability heatmap showing the intensity of cell attachments.*

### Image Quadrant Analysis and Chi-Square Test

I also performed Chi-Square tests to statistically determine cell distributions. Example:

![Quadrant Analysis](/assets/img/GeoSpatialCellResearch/Plots_Quadrant_Aggregates.jpg)  
*Figure 3: Quadrant analysis of cell distribution with Chi-Square test results.*

### Comparison with Manually Created Patterns

To further validate my findings, I manually created random and regular point patterns and compared them with the actual cell distributions. This comparison helped in understanding the degree of randomness in the cell patterns.

![Pattern Comparison](/assets/img/GeoSpatialCellResearh/sample_random_regular.jpg)  
*Figure 4: Comparison of actual cell distribution with manually created random and regular patterns.*

### Fitting Point Patterns to Distribution Functions

I also fit the point patterns into different statistical functions to analyze the significance of pattern differences.  

![Distribution Function Fitting](/assets/img/GeoSpatialCellResearh/point_distribution_functions_fitting_vs_Prois.jpg)  
*Figure 5: Fitting point patterns to various distribution functions.*

## Detailed Protocols and Scripts

My detailed scripts are available in my GitHub repository:
[Explore the GitHub Repository](https://github.com/sl1453/GeoSpatial-Point-Pattern-Analysis/blob/main/README.md)

---

*Images and plots are examples, the publication is currently in the review process.*
