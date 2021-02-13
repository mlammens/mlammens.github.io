---
title: Reading notes - Peterson et al. 2018
author: R package build
date: '2021-02-13'
slug: reading-notes-peterson-et-al-2018
categories:
  - Research
tags:
  - Reading
---

Here are some thoughts and ideas I had while reading - Peterson, M., Doak, D., & Morris, W. (2018). *Incorporating local adaptation into forecasts of species’ distribution and abundance under climate change*. Global Change Biology, 25. [https://doi.org/10.1111/gcb.14562](https://doi.org/10.1111/gcb.14562).

It feels like it has been a long time since I've given much thought to local adaptation, which is funny to me, as it was a major area of focus for me during grad school.
Nevertheless, I had bookmarked this paper some time ago, and was keen to read it as it relates to both local adaptation, and to some extent, species distribution modeling. 

The authors present both a review of how studies have incorporated local adaptation into forecasts (as the title says!) and perspectives and ideas regarding ways to advance the field.
With respect to SDMs (which I still very much think about on a regular basis), they offer some neat ideas.
I was particularly interested in the ideas regarding dealing with uncertainty in SDMs. 
In addition to the uncertainty that can be examined using multiple different modeling approaches (ensemble models), they also point out that utilizing different "functional forms for climate responses" may be a way forward, considering that different populations of the same species may have different functional responses to climate.

The authors also emphasize the need / utility of independent testing data. 
I couldn't agree more.
But one thing this made me think about is how, barring such independent data (or perhaps in conjunction with), how could the more recent advances in spatial cross-validation used in SDMs play a role here?
I think there are many applications and scenarios that could be investigated using the likes of the R packages [ENMeval](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12261) or [blockCV](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13107).



