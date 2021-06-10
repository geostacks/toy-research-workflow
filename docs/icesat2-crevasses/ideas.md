# Search for ideas

A good reseach always starts from a good idea. Finding a good idea requires a lot of reading and thinking, which is usually the first step for a research project.

## From an idea to a plan

One day we noticed this paper written by {cite:t}`Herzfeld2021`: https://www.sciencedirect.com/science/article/pii/S2666017220300122. It introduces an algorithm called **DDA-ice** for analyzing crevasse morphology using ICESat-2 laser altimetry data. This looks really useful because glacier crevasses can influence glacier hydrology, dynamics, and mass balance through multiple processes (e.g., {cite:t}`Colgan2016`). This paper seeks to prove that ICESat-2 data have a potential to derive crevasse evolution on glacier surface. We wonder if we can use DDA-ice or a similar tool and analyze the glaciers in our study area.

## Challenges

However, the authors didn't release a copy of their DDA-ice package along with the paper. We typically have two solutions for this issue:

1. Email to the corresponding author and ask for the software and the documentation. Perhaps for future collaboration as well. This might ensure that the software and the previous work can be best credited, as well as the research quality using this package. However, it takes time for researchers to communicate in person or over emails, and the development of software and the data analysis might be slow compared the data collection rate.
2. Adopt the ideas from the paper and develop your own code for the same purpose (crevasse analysis). This is usually more time-consuming than the first method, regardless of the skill level of the researchers. Also, there will be a lot of effort we need to do with this new package to avoid inventing the wheel the third time, such as publishing software, quality assessment, and writing document. Despite of this additional work, this approach might improve the research efficiency and community-based development for this particular tool if the right sharing scheme is established. 

Jupyter tools aims to provide such a scheme. The open-source tools in this ecosystem help make your work (including text, data, figures, and code) reusable, reproducible, and easily accessible to the other researchers. 

## Goals

For this toy workflow, we attempt to achieve these goals:

1. Using the ideas from {cite:t}`Herzfeld2021`, Develop a research workflow for analyzing glacier crevasse mophorlogy using Jupyter tools.
2. Reproduce Figure 6a of the same paper using exactly the same data source: ICESat-2 data over Negribreen, Svalbard, measured on August 5 2019.
3. Document each step in the workflow and make them as accessible and reproducible as posssible. 

```{figure} images/Herzfeld_etal_SciRemoteSens_2021_fig6a.PNG
---
height: 200px
name: Herzfeld_2021_fig6a
---
Figure 6a from {cite:t}`Herzfeld2021` showing the elevation profile along a particular ICESat-2 track and identification of glacier crevasses.
```