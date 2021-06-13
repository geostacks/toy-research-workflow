# Write a report

We have finished our analysis and plan to conclude it with a written report. We may select to write an academic paper (for scientific findings), a technical report (for details of ICESat-2 data processes), a software documentation (for guides to use this new algorithm), or other kinds of format. Despite having various purposes, there are common key parts during academic writing, and Jupyter tools can also help expedite this process. Here we have listed some examples.

## Mixing all components together: Jupyter Notebook and beyond

As you may have seen a lot during the EarthCube meeting, Jupyter Notebook (as well as [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html), Jupyter’s Next-Generation Notebook Interface) lets researchers present their workflows and results in one place, including text, code, equations, and figures. We also wrote some of the pages in this workflow (specifically {doc}`getdata`, {doc}`explore`, {doc}`analysis`, and {doc}`results`) using Notebook. You can find a link to the source Notebook file by hovering over the download icon in the upper right of the page ({ref}`fig:find_ipynb_link`). 

```{figure} images/find_ipynb_link.PNG
---
height: 200px
name: fig:find_ipynb_link
---
The link to the source Jupyter Notebook file.
```

You can also go to our [Github repository](https://github.com/geostacks/toy-research-workflow/tree/main/docs) and access those Notebook files. The [nbviewer](https://nbviewer.jupyter.org/) service can help read and display them on a web browser; see {doc}`reproduce` for more information.

### Use Jupyter Book to organize and present your work

Each section in this toy workflow is written in either Notebook or Markdown format. To organize different pieces in a research project, we use [Jupyter Book](https://jupyterbook.org/) and render these Notebook and Markdown files as a bunch of interconnected html files. This process is simple and does not require much additional work. All we need are a few additional files to let Jupyter Book know how to complie this book:

- `_config.yml` : general settings of the book, such as layout, Notebook execution, and launch buttons.
- `_toc.yml`: table of content. Defines book structure, chapters, and sections.
- references as `.bib` format: for managing references. Optinal.

Once we have these files ready, install `jupyter-book` and run the following commands 

```bash
jupyter book build ./docs
```
and the html output (as you have seen on these web posts) will be generated under `./docs/_build/html`.

### Write in the `MyST` markup format

There are three mainstream choices for academic writing: Word-like apps (Microsoft Word, Google Docs, OpenOffice Writer, etc.), LaTeX-based packages/apps (TeX Live, Overleaf, etc.), and other markup languages such as Markdown and reStructuredText. Many academic journals accept the first two as the preferred submission format, while Markdown and reStructuredText are widely used for technical documents. 

When we are writing Jupyter Book pages in either `.md` or `.ipynb` format, we are acutally using a new type of markup languages called [MyST](https://myst-parser.readthedocs.io/en/latest/) (Markedly Structured Text). MyST combines the advantages of Markdown and reStructuredText and supports other necessary elements in academic writing, including LaTex math and citation syntax. You can find examples {doc}`getdata` and other pages in this toy workflow shoing how these elements are implemented. 

## Collaborate using Jupyter 

As long as the Jupyter book documents are hosted on an open repository such as Github, we can invite collaborators to contribute and work on the same project. `git` and the Github service used to be popular in only certain programming-related communities, but now it becomes a useful tool for academic collaborators with the help of Jupyter Notebooks. 

One of the future directions for collaborating using Jupyter is the [Jupyter RTC](https://jupyterlab-rtc.readthedocs.io/en/latest/) (real time collaboration) project. It will allow users to edit the same Notebook at the same time, and the changes can be immediately reflected to the other users, just like the way we use Google Docs. 

<!-- Despited still being activaly developing, the [Jupyter RTC](https://jupyterlab-rtc.readthedocs.io/en/latest/) (real time collaboration) project aims to provide collaborative components of writing a Notebook. -->

