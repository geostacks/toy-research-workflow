# Search for ideas

Good reseach always starts from a good idea. And good idea does not come from nowhere -- it requires a lot of reading and thinking. Searching for good ideas is the first step we need for any research project.

## From an idea to a plan

One day you notice this paper: https://www.sciencedirect.com/science/article/pii/S2666017220300122. It introduces an algorithm called DDA-ice for analyzing crevasse morphology using ICESat-2 laser altimetry data. 

You think this is cool because crevass density on a glacier is thought to be an important factor to glacier hydrology, stability, etc. This paper shows that ICESat-2 data are capable for detecting crevass density, and DDA-ice is capable for that. You want to try DDA-ice immediately and analyze the glaciers in your study area.

## Challenges

However, the authors didn't release a copy of their DDA-ice software with the paper. You typically have two ways to do:

1. Email to the corresponding author and ask for the software and the documentation.
2. Develop your own code for the same thing, although it is to invent the wheel twice.

Unfortunately, both ways take a lot of time. 

Jupyter tools can help resovle this. These open-source packages make your work reusable, reproducible, and easily accessible to the other researchers. 

## Goal of this workflow

1. Follow the work of Herzfeld et al. (2021) and analyze crevasse density using Jupyter tools
2. To test our new algorithm, we will use ICESat-2 data over Negribreen, Svalbard, measured on August 5 2019, and reproduce Figure 6a of this paper.