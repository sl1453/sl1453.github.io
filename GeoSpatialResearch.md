---
layout: page
title: Cell Behavior
subtitle: culturing, imaging, statistics & more
---

## Introduction

In my Master's research project, I utilized mammalian cell cultures to study the mechanisms of small molecule inhibitors, which I will discuss in detail on the "Chemical Bio" page. Here, I will introduce the cell work from my Ph.D. research, focusing on the behaviors of _Giardia_ cells in varying environments.

## Ph.D. Research Focus

### Study of _Giardia_ Cell Behaviors

A significant part of my dissertation involved investigating the behaviors of _Giardia_ cells in environments with different viscoelastic properties. To study these motile cells, I developed micro-culture systems that enabled systematic imaging of the culture over a time course of growth. This required conducting live cell imaging using various advanced methods, including confocal and spinning disk microscopy.

![Giardia Cell Image](/path/to/your/image1.jpg)
*Figure 1: Confocal image of _Giardia_ cells in culture.*

## GeoSpatial Analysis Approach

After obtaining high-quality images, the next challenge was analyzing the attachment patterns of _Giardia_ cells. I adopted a method commonly used in GeoSpatial research to analyze point pattern distributions, applying these statistical techniques to study the spatial attachment locations of the cells.

### R Language and Data Analysis

This project provided an opportunity to teach myself R programming for processing biological image data and conducting statistical analyses. Here are some examples of the analyses I performed:

### Probability Heatmaps

Using point intensity probability heatmaps, I was able to visualize the likelihood of cell attachments across different regions. These heatmaps help identify areas of high and low cell density, providing insights into cell behavior and environmental interactions.

![Probability Heatmap](https://github.com/sl1453/GeoSpatial-Point-Pattern-Analysis/blob/main/Sample_Plots/SamplePlot_Point_Intensity_Probability.jpg)
*Figure 2: Probability heatmap showing the intensity of cell attachment points.*

### Image Quadrant Analysis and Chi-Square Test

I divided the images into quadrants and performed cell counting and Chi-Square tests to determine if the cells exhibited aggregated patterns. This statistical approach allowed for a rigorous analysis of cell distribution.

![Quadrant Analysis](https://github.com/sl1453/GeoSpatial-Point-Pattern-Analysis/blob/main/Sample_Plots/Plots_Quadrant_Aggregates.jpg)
*Figure 3: Quadrant analysis of cell distribution with Chi-Square test results.*

### Comparison with Manually Created Patterns

To further validate my findings, I manually created random and regular point patterns and compared them with the actual cell attachment distributions. This comparison helped in understanding the degree of randomness or aggregation in the cell patterns.

![Pattern Comparison](https://github.com/sl1453/GeoSpatial-Point-Pattern-Analysis/blob/main/Sample_Plots/sample_random_regular.jpg)
*Figure 4: Comparison of actual cell distribution with manually created random and regular patterns.*

### Fitting Point Patterns to Distribution Functions

I also fit the point patterns into different distribution functions and compared them with a Poisson distribution to analyze the underlying statistical properties of the cell attachment patterns.

![Distribution Function Fitting](https://github.com/sl1453/GeoSpatial-Point-Pattern-Analysis/blob/main/Sample_Plots/point_distribution_functions_fitting_vs_Prois.jpg)
*Figure 5: Fitting point patterns to various distribution functions.*

## Detailed Protocols and Scripts

For those interested in the technical details, my detailed script protocols are available in my GitHub repository. These scripts include loops for processing a series of images taken over time, as well as individual image data loading and analysis.

[Explore the GitHub Repository](https://github.com/sl1453/GeoSpatial-Point-Pattern-Analysis/blob/main/README.md)

## Conclusion

Through these analyses, I have gained valuable skills in bioinformatics and statistical analysis, contributing to a deeper understanding of _Giardia_ cell behaviors. These methods can be applied to various other cell types and research questions, highlighting the interdisciplinary nature of modern biological research.

If you have any questions or would like to discuss my work further, please feel free to [contact me](mailto:your-email@example.com).

---

*Images and plots are just examples, the publication is currently in review.*
