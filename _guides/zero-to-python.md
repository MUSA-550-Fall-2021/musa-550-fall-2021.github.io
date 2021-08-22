---
layout: page
title: From Zero to Python
permalink: /guides/zero-to-python
---

This guide walks you through the steps of getting set up to use Python in
{{site.title}}. It provides links for downloading and installing Python, getting
all of the Python packages, you'll need for the course, launching your first
Jupyter notebook, and using the notebook to write your own Python code.

## Steps

1. **Download and install Python** [[Instructions]](/resources/setup): We'll be
   using the `conda` package manager to install Python and manage dependencies.
   It comes in two flavors: Anaconda and Miniconda, but I recommend using
   Miniconda because the full Anaconda download will take up several GB of space
   on your computer.
1. **Create your first Python environment**
   [[Instructions]](https://musa-550-fall-2020.github.io/guides/conda#creating-your-initial-environment):
   The `conda` application will allows us to easily install new Python packages
   and keep track of which ones we've installed. I've put together a list of the
   packages we'll need in this course (a group of packages is known as an
   _environment_ in `conda`-speak). Note that you'll be using the command line (either
   the Anaconda Prompt in Windows or Terminal app in MacOS) to run `conda` and
   create your environment. More info on running `conda` commands from the command line
   is available [here](https://musa-550-fall-2020.github.io/guides/conda#starting-and-running-conda).
1. **Activate the course's environment**
   [[Instructions]](https://musa-550-fall-2020.github.io/guides/conda#activating-your-environment):
   Once you create your new environment and install of the Python packages, you
   need to tell `conda` to _activate_ it (more `conda`-speak) so that you can
   actually use the packages.
1. **Launch your first Jupyter notebook** [[Instructions]](https://musa-550-fall-2020.github.io/guides/jupyter#launching-a-jupyter-notebook): With Python set up, we can launch a Jupyter notebook
   server, open up a new notebook, and start doing some data analysis with Python!

### Note

To better familiarize yourself with the `conda` package manager, I encourage
you to go through the [Conda User Guide](guides/conda) as well.
