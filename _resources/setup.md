---
layout: page
title: Installing Python with Conda
permalink: /resources/setup/
---

`conda` is an open-source _package management system_ for Python. It is very widely used and there are a number of resources available online for Mac OS and Windows machines.

It allows you to easily install Python packages on your laptop using _environments_. A environment allows you to install packages for specific purposes and keep those packages isolated from any other Python packages that might be installed on your laptop. We will create an environment for use during this class that includes all of the Python packages you will need in the course.

In this course, we will use the Miniconda distribution of Python, which includes Python, `conda`, and a few other essential packages and dependencies. The Miniconda distribution is a lightweight version of the full [Anaconda distribution](https://docs.anaconda.com/anaconda/install/). It is the fastest way to install both Python and `conda` on your local computer.

The differences between the distributions are outlined [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html#anaconda-or-miniconda). The major difference is that the Anaconda distribution will install more than 1,500 of the most common scientific Python packages (many more than we need in this course) and will take up about 3 GB of disk space. Miniconda will only install core Python dependencies (as well as `conda`) and will only take up about 400 MB of disk space.

The first step is to download the Miniconda installer from the following link:

[https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

The latest installer for your computer's operating system should be used. It will install Python version 3.8 into an environment called _base_.

The rest of the installation instructions will vary based on your operating system.

#### On Windows

- Double-click the `.exe` file that you downloaded.
- Follow the instructions on the screen. If you are unsure about any setting, accept the defaults. You can change them later.
- Test your installation. From the \*_Start_ menu, open the "Anaconda Prompt" application. In the Anaconda Prompt, run the command `conda list`. A list of installed packages should be printed to the screen if the installation was successful.

#### On MacOS

- Open the Terminal application.
- Change the folder to the directory where the `.sh` installer file was downloaded (this is usually the "Downloads" folder) by running the following command in the Terminal app:

```
bash Miniconda3-latest-MacOSX-x86_64.sh
```

- Follow the instructions on the screen. If you are unsure about any setting, accept the defaults. You can change them later.
- To make the changes take effect, close and then re-open your terminal window.
- Test your installation. In the terminal window, run the command `conda list`. A list of installed packages should be printed to the screen if the installation was successful.

Full installation instructions are available here:

- [MacOS](https://conda.io/projects/conda/en/latest/user-guide/install/macos.html)
- [Windows](https://conda.io/projects/conda/en/latest/user-guide/install/windows.html)
- [Linux](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html)

#### A Note on Python 2 vs 3

We will use Python 3 in this course (version 3.7 to be exact).

The adoption of Python 3, first released in 2008, was very slow, and many users still choose to use Python 2. Python 3 has a lot of great new features, and beginning in 2019, new releases for the majority of the widely-used Python packages no longer support Python 2.

### Next step: see the [conda user guide](/guides/conda) for more information on managing environments and installing packages.
