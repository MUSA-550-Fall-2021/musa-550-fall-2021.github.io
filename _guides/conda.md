---
layout: page
title: Conda User Guide
permalink: /guides/conda
---

<nav class="toc">
  <header><h4 class="nav__title">Guides: Navigation</h4></header>
  <ul class="toc__menu">
    <li>
      <a href="/guides/conda">Conda User Guide</a>
    </li>
    <li>
      <a href="/guides/conda-issues">Common Conda Issues</a>
    </li>
    <li>
      <a href="/guides/jupyter">Jupyter User Guide</a>
    </li>
  </ul>
</nav>

On this page, I'll outline some of the [key concepts](#key-concepts) and [common
uses](#common-uses) to get you up and running with `conda`. A `conda`
cheatsheet is also [available](/cheatsheets/conda.pdf) under the "Cheatsheets"
section in the main navigation bar.

To fully familiarize yourself with `conda`, I **strongly recommend** going through the official 20-minute [Conda User Guide](https://docs.conda.io/projects/continuumio-conda/en/latest/user-guide/getting-started.html).

## Key Concepts

<nav class="toc">
<header><h4 class="nav__title">Sub-Sections</h4></header>
  <ul class="toc__menu">
    <li>
      <a href="#conda-commands">Conda Commands</a>
    </li>
    <li>
      <a href="#starting-and-running-conda">Starting and running conda</a>
    </li>
    <li>
      <a href="#conda-channels">Conda Channels</a>
    </li>
    <li>
      <a href="#conda-environments">Conda Environments</a>
    </li>
    <li>
      <a href="#conda-vs-pip">Conda vs pip</a>
    </li>
  </ul>
</nav>

### Conda Commands

We'll be using the `conda` tool through its command-line interface rather than a
typical graphical user interface (GUI) application. If you are unfamiliar with
the command line, this will take some getting used to but once you get the hang
of it, it will make working with `conda` and Python much easier.

The `conda` command is the main interface for using the `conda` tool for managing
your Python packages. From the command line, you simply run:

```bash
conda command [optional arguments will go here]
```

where "command" is the name of the command you want to run. Commands exist to install new packages,
create new environments, and much more.

### Starting and running conda

We will run `conda` from the command line but the specifics of this will depend
on your operating system.

#### Windows

Open the **Start** menu, search for and open the "Anaconda Prompt". This
application provides a command line interface where the `conda` tool is properly
load, initialized, and ready to be used. Note that you **cannot** use the
default "Command Prompt" application to use `conda` because it doesn't know how
to load `conda` properly.

#### MacOS

The Terminal app should be used on MacOS to use `conda`. You can also use any
Terminal emulator (such as [iTerm2](https://iterm2.com/)). Simply open the Terminal
application and the `conda` command should be ready to use.

### Conda Channels

Conda "channels" are the locations where packages are located. Channels are
typically remote, hosted in the cloud, and when you specify a channel, conda
will search the remote database for the right package and download it to your
local computer.

By default, packages will be downloaded from the _defaults_ channel, which hosts
thousands of packages and is managed by the makers of the Anaconda distribution.
A full list of packages is available
[here](https://repo.anaconda.com/pkgs/main/).

There is also a community-managed channel known as
[_conda-forge_](https://conda-forge.org/) that hosts thousands of packages. It
includes many of the packages on the "defaults" channel but also popular
packages that are widely-used but not quite essential enough for the "defaults"
channel. A list of maintained packages is available
[here](https://conda-forge.org/feedstocks/).

For less well known packages, there is a higher likelihood the package will be
hosted on conda forge. For that reason, we will prefer downloading and
installing packages from conda forge in this course.

### Conda Environments

The `conda` tool not only lets you download and install packages, but you can
group those packages together into _environments_. By default, the `Miniconda`
Python distribution creates an environment named _base_. We will create a new
environment specifically for this course that will hold all of the packages
needed for the entire semester.

Environments become particularly useful when working with lots of packages,
packages that have a lot of dependencies, or packages that are difficult to
install. When environments become too large, it can be difficult to install a
new package that satisfies all of the existing package dependencies. For that
reason, we will create a fresh, new environment to install the packages we need
to use during this course.

### Conda vs pip

The other widely used method for installing packages is via the [`pip`
command](https://pip.pypa.io/en/stable/). The commands are similar in a lot of
ways but with some key differences. The `pip` command installs packages from the
[Python Package Index](https://pypi.org/) and is designed to install Python-only
packages.

The main advantage of `conda` is that it is _cross-platform_ and can handle
dependencies that are written in C (or other languages) and will automatically
handle the compiling process during installation. Many of the packages we use in
this course have complex dependencies written in C, and `conda` will make
installation of these packages _much easier_.

_In this course, we'll be using `conda` to install packages._ Generally speaking, if you
already are using `conda` to manage environments, it's best to try to install packages
with `conda` and if the package is not available, then try using `pip`.

See [this article](https://www.anaconda.com/blog/understanding-conda-and-pip)
for more information about `conda` and `pip`.

## Common Uses

<nav class="toc">
<header><h4 class="nav__title">Sub-Sections</h4></header>
  <ul class="toc__menu">
    <li>
      <a href="#getting-help-with-the-conda-command">Getting help with the conda command</a>
    </li>
    <li>
      <a href="#making-sure-you-are-running-the-latest-conda-version">Making sure you are running the latest conda version</a>
    </li>
    <li>
      <a href="#listing-the-available-environments">Listing the available environments</a>
    </li>
    <li>
      <a href="#creating-your-initial-environment">Creating your initial environment</a>
    </li>
    <li>
      <a href="#activating-your-environment">Activating your environment</a>
    </li>
    <li>
      <a href="#finding-the-active-environment">Finding the active environment</a>
    </li>
    <li>
      <a href="#listing-the-installed-packages">Listing the installed packages</a>
    </li>
    <li>
      <a href="#activating-the-base-environment">Activating the base environment</a>
    </li>
    <li>
      <a href="#deleting-an-environment">Deleting an environment</a>
    </li>
    <li>
      <a href="#updating-an-existing-environment">Updating an existing environment</a>
    </li>
    <li>
      <a href="#installing-specific-packages">Installing specific packages</a>
    </li>
  </ul>
</nav>

Managing environments and installing packages will be done by executing the
`conda` command in the command line. Below are some of the most common commands
that we will use in this class.

**Important:** All of the examples below should be run in the `Terminal` app
(MacOS) or `Anaconda Prompt` (Windows). See the [Starting and running
conda](#starting-and-running-conda) section above for more detail.

### Getting help with the conda command

The `conda` command has a built-in help function. From the command line
(Anaconda Prompt on Windows or Terminal on MacOS) run,

```
conda --help
```

which will print out info about individual commands:

```
conda is a tool for managing and deploying applications, environments and packages.

Options:

positional arguments:
  command
    clean        Remove unused packages and caches.
    compare      Compare packages between conda environments.
    config       Modify configuration values in .condarc. This is modeled
                 after the git config command. Writes to the user .condarc
                 file (/Users/nhand/.condarc) by default.
    create       Create a new conda environment from a list of specified
                 packages.
    help         Displays a list of available conda commands and their help
                 strings.
    info         Display information about current conda install.
    init         Initialize conda for shell interaction. [Experimental]
    install      Installs a list of packages into a specified conda
                 environment.
    list         List linked packages in a conda environment.
    package      Low-level conda package utility. (EXPERIMENTAL)
    remove       Remove a list of packages from a specified conda environment.
    uninstall    Alias for conda remove.
    run          Run an executable in a conda environment. [Experimental]
    search       Search for packages and display associated information. The
                 input is a MatchSpec, a query language for conda packages.
                 See examples below.
    update       Updates conda packages to the latest compatible version.
    upgrade      Alias for conda update.
```

To find out more info about a specific sub-command, you can run:

```
conda command --help
```

For example, for more info about the arguments (both required and optional) needed
to install packages, use: `conda install --help`.

### Making sure you are running the latest conda version

The first thing you should do is make sure you are running the latest `conda`
version.

From the command line (Anaconda Prompt on
Windows or Terminal on MacOS), run

```
conda update -n base -c defaults conda
```

### Listing the available environments

The default environment when first installing Anaconda is called `'base'`. You
can list the currently installed Python environments by running the following
command from the command line (Anaconda Prompt on
Windows or Terminal on MacOS):

```
conda env list
```

The currently active environment will have a `'*'` next to it. You should see
the `'base'` environment as well as any other environments you have created.

### Creating your initial environment

Throughout this course, we will maintain an environment called `'{{ site.env_name }}'` to
install and manage all of the packages needed throughout the semester.

The packages in an environment are specified in a file typically called
`environment.yml`. The environment file for this course is stored in the
[course-materials](https://github.com/MUSA-550-Fall-2020/course-materials)
repository on Github and a copy is also stored in the cloud on
[anaconda.org](anaconda.org).

It is recommended to create the `'{{ site.env_name }}'` environment on your
local computer using the environment file stored in the cloud on anaconda.org.

First, we need to make sure the `anaconda-client` package is installed locally.
This will ensure that `conda` can interface with [anaconda.org](anaconda.org).
From the command line (Anaconda Prompt on
Windows or Terminal on MacOS), run:

```
conda install anaconda-client -n base
```

Then, create your environment with `conda env create`:

```
conda env create pennmusa/{{ site.env_name }}
```

If you [list your local environments](#listing-the-available-environments), you
should now see the `'{{ site.env_name }}'` environment listed.

### Activating your environment

Environments must first be "activated" before the packages are available to use.
To activate the environment for this course, you can run the following
from the command line (Anaconda Prompt on
Windows or Terminal on MacOS):

```
conda activate {{ site.env_name }}
```

Now, all of the packages in this environment will be available when we run
Python.

### Finding the active environment

To see the active environment, [list the available environments](#listing-the-available-environments).
The active environment will be listed with a '\*' next to its name.

From the command line (Anaconda Prompt on Windows or Terminal on MacOS),

```
conda env list
```

### Listing the installed packages

If you have already [activated the {{ site.env_name }} environment](#activating-your-environment),
you can list all of the installed packages.

From the command line (Anaconda Prompt on Windows or Terminal on MacOS),

```
conda list
```

### Activating the base environment

To activate the `'base'` default environment, run from the command line (Anaconda Prompt on
Windows or Terminal on MacOS):

```
conda deactivate
```

Note that you should always use the `'{{ site.env_name }}'` environment to do
the analysis in this course, making sure it is the activated environment
when using Python.

### Deleting an environment

Note that you cannot create a new environment with the same name as an existing
environment. If your environment becomes corrupted or you run into issues, it is
often easiest to delete the environment and start over. To do, you can run the
following commands from the command line (Anaconda Prompt on
Windows or Terminal on MacOS):

```
conda deactivate
```

```
conda env remove --name {{ site.env_name }}
```

### Updating an existing environment

The environment we are using throughout the course might be need to be
updated during the course. For example, we might want to update to include
a newly released version of a package.

You can update your local environment via the following command.
From the command line (Anaconda Prompt on
Windows or Terminal on MacOS):

```
conda env update pennmusa/{{ site.env_name }}
```

This command will ensure that the `'{{ site.env_name }}'` environment on your
local computer matches the environment specified by the `environment.yml` file
stored in the cloud for the course.

### Installing specific packages

You shouldn't need to install any individual packages into the `'{{ site.env_name }}'` environment. But for reference, you could install specific
packages into the active environment using from the command line (Anaconda Prompt on
Windows or Terminal on MacOS):

```
conda install package_name
```
