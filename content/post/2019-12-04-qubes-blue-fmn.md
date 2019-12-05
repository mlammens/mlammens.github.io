---
title: QUBES BLUE FMN
author: Matthew Aiello-Lammens
date: '2019-12-04'
slug: qubes-blue-fmn
categories:
  - Teaching
tags:
  - Biodiversity Literacy
---

This fall I participated in my second [QUBES Faculty Mentoring Network](https://qubeshub.org/community/fmns), this time working along side several other educators to implement and/or develop learning modules associated with the [Biodiversity Literacy in Undergraduate Education (BLUE) network](https://www.biodiversityliteracy.com/). I chose to adapt an existing module to implement in my Introduction to Statistics for Life Science course, and still have intentions of creating a new module for our last week of new material coming up. 

## Data is the New Science - remixed

The module I chose to implement was the [Data is the New Science](https://qubeshub.org/qubesresources/publications/1138/1) module, which was designed to introduce students to biodiversity data sources and encourage them to interact with the information that can be acquired from these sources. I remixed this module to have my students also become familiar with these sources, to practice working with basic summary statistics, and to work with visualizing data in multiple ways. One major distinction between my module (which I turned into an in class assignment) is that I had the students carry out each of the data acquisition and analysis steps using the R statistical computing language. To do so, I took advantage of several opensource packages, including [`ridigbio`](https://cran.r-project.org/web/packages/ridigbio/index.html) and [`rgif`](https://cran.r-project.org/web/packages/rgbif/index.html).

### Why an R remix?

The course that I implemented this module in, as noted above, was a biostats course. One of the main outcomes of the course is that the students become familiar with using R (via RStudio) to perform the analyses common in the fields of biology and environmental science. As such, I try to use R in just about all of our class assignments. Also, I use R in my personal research to gather, visualize, and analyze biodiversity data all of the time. So part of my motivation was to show my students that they too can use the same techniques as someone else they see as a "scientist". 

## Class Logistics

The class that I implemented this module in had approximately 20 students, who were primarily undergraduate biology, health science, and environmental science majors. The class is required for these degree programs. Nearly all of the students had minimal to no programming experience. Approximately half of the students had already taken an ecology or environmental science course, or courses. Nearly all will be expected to take at least one of these courses to complete the degree. That said, there is not an overwhelming interest in biodiversity studies among the students in this class, as most are interested in health sciences. The majority of class assignments, including the remix of the Data is the New Science module, were completed in groups of two to three students.

## Successess

I was most pleased to see that nearly all of the students fully engaged with the activity, and were excited to look at available data for a whole array of species. They really got into thinking about very different and exciting species, which I think gave them a sense of "ownership" over the assignment.

All of the groups were able to acquire biodiversity data from iDigBio and GBIF, and visualize those data and make observations about species ranges and distributions. They were able to combine these data with environmental data to say something specific about the environmental conditions that there species of interest were observed in. 

Based on informal conversations with the students during the activity, and assessing their completed module/assignment, I'm confident that the students learned about the existence of and how to access biodiversity data bases. Considering the iDigBio data base in particular, the students were surprised and curious to find out that institutions *actually* store specimens for future use!

## Challenges

I found that by adding the R content to the existing module (and cutting some of the original module material to make room for this), I inadvertantly deemphasized the biodiversity-related thinking exercises. I think this is in part because students were focused on the tasks they thought were both most challenging and most related to the rest of the course - i.e., implementing the R code. In the future, I will try to address this by having the students work on developing hypotheses about species distributions.

There were a few technical difficulties that we had to overcome, some that can be addressed with changes to the module. First, some groups initially chose species that were either **very** small or **very** large in number. In the former case, they visualizations were not really effective. In the latter, the R GBIF functionality was slow, or failed, leading students to restart the assignment with a different species. In a future version of this module, I will suggest some guidelines about choosing species based on the numbers of observations returned in the graphical user interface (website) exercises.

## Content Links

Here are the Rmd and DOCX file formats for the module. Make sure to go look at the original [Data is the New Science](https://qubeshub.org/qubesresources/publications/1138/1) module as well.

* [Data is the New Science - R Remix - Rmd format](https://github.com/mlammens/mlammens.github.io/blob/master/misc_files/Data-is-the-new-science-R-Remix.Rmd) 
* [Data is the New Science - R Remix - DOCX format](https://github.com/mlammens/mlammens.github.io/blob/master/misc_files/Data-is-the-new-science-R-Remix.docx)  
