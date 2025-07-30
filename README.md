# quarto_template_ugent

A starting point for making courses with Quarto at Ghent University with a focus on using Python code. 

## Installation instructions

First, make a local copy of this repository using

```
git clone https://github.com/olivierbonte/quarto_template_ugent.git
```

or download as zip file and unzip. In each case, make sure to navigate inside the `quarto_template_ugent` folder before executing any of the command line interface (CLI) instructions below.

Go to the [Quarto download page](https://quarto.org/docs/download/) and download Quarto for your operating system (OS). This repository was built using Quarto 1.6.40.

Next, make sure you have (Mini)Conda installed (download links found [here](https://docs.anaconda.com/miniconda/)) to handle virtual environments in Python. Next open your CLI (or Anaconda prompt) and type:

```
conda env create -f environment.yml
conda activate quarto_template
```
This ensures that the correct version of Python is used in your CLI.

Next, it is recommended that following Quarto tools are installed:

- In this repository, a final output is rendered to pdf. Therefore, [a LaTeX distribution is needed](https://quarto.org/docs/output-formats/pdf-basics.html#prerequisites). Install the [TinyTex distribution](https://yihui.org/tinytex/), a lightweight version of [TeX Live](https://www.tug.org/texlive/), with following command in the CLI: `quarto install tinytex`. This should be more straightforward than managing your own [Tex distribution](https://www.latex-project.org/get/#tex-distributions).
- To render the diagrams, made with [Mermaid](https://mermaid.js.org/intro/), [quarto needs the Chrome or Edge browser](https://quarto.org/docs/authoring/diagrams.html#chrome-install). It is again easiest to use the Quarto tooling by installing a lightweight version of crhome with `quarto install chromium`



