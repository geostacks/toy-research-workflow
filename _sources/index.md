# Jupyter Meets the Earth - A toy research workflow

This is a simple workflow showing how Jupyter and Pangeo tools help develop a research project and share scientific results, specifically for the field of geoscience. 

## Summary

We use the ICESat-2 data (measurements of a satellite later altimeter) and conduct a glacier crevasse analysis. We use tools in the Jupyter and Pangeo ecosystem, including Icepyx, to query data, explore ideas, visualize findings, and publish results. This workflow provides a generic scheme for earth science research projects, although some of the tools used here might be specific to cryospheric studies. We aim to tackle the following challenge: one has some data and ideas for a scientific analysis and wants to make the results as reproducible as possible to the other researchers. Might be even better to have some educational purposes. Here we show that the Jupyter and Pangeo tools can provide an easy approach to achieve the goals.

<!-- The data and the tools may be replaced by some other stuff -->

## Seven stages of a research workflow 

We break this toy workflow down into seven conceptual stages which are present in most research activities:

<!-- In this toy research workflow, we are going to use ICESat-2 data to analyze glacier crevasses on the surface of a specific Arctic glacier. Although it sounds very specific to link to a certain domain of earth science, it does have the common stages for most research activities. We break these stages into the following seven concepts: -->

1. {doc}`icesat2-crevasses/ideas`: You did a lot of studies for some interesting arguments. Now you have your own ideas and want to test them. How to develop a solid and practical plan for that? What are other challenges during this stage?
2. {doc}`icesat2-crevasses/getdata`: You have pinned down a strategy and a data set you are going to use. If the data set is big and contains a lot of less related information to your ideas, How to query, access, slice, and retrieve the most valuable part with effeicency for your research project?
3. {doc}`icesat2-crevasses/explore`: Before carrying on detailed analysis of the data, it is often necessary to evaluate them first so we know their potentials. We wonder if there is a way to dissect the data quickly and get a broad picture of them.
4. {doc}`icesat2-crevasses/analysis`: The choice of tools determines how you work with the data. The Jupyter and Pangeo projects provide an arsenal full of software packages that have been well aggregated together. This is what we call an "ecosystem". For each software "niche" that includes the most appropriate tools for a particular research case, the Jupyter ecosystem aims to simply support it.
5. {doc}`icesat2-crevasses/results`: It is nearly always necessary to revisit a particular analysis, update the results, and modify figures and tables. How to make this step as less painful as possible? Furthermore, we want to move one step forward: how to interactively present your results for the readers to make sense?
6. {doc}`icesat2-crevasses/writeup`: Academic writing is tough, partly because you have to organize all the material you have, such as text, figures, tables, equations, code, and references. How can Jupyter help with this?
7. {doc}`icesat2-crevasses/reproduce`: The last step of the workflow is an important step to advance scientific exploration. Your work has been published, and now it is part of the knowledge base to the other researchers. When they want to test your results or build their workflows based on your work, what are the ways you can do to expedite this knowledge sharing process on the Jupyter Landscape?


<!-- ## Summary of the workflow

We will use the ICESat-2 data (elevation measuments from a satellite altimeter, stored as per measurement basis (point cloud data)) and conduct a crevasse density analysis. We use Icepyx as the main tool to search and access the data. Note this is meant to provide a generic workflow any earth science researchers may encounter. The data and the tools may be replaced by some other stuff, but the general scheme isn't changing: you have data and a specific tool to query/access/manipulate the data. You want to share your results and make them as reproducible as possible to the other. What can Jupyter/Pangeo tools do for that? -->