---
layout: page
title: Common Conda Issues
permalink: /guides/conda-issues
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

In this guide, we describe some of the most common issues encountered during
local installation of Python packages, as well as the troubleshooting steps to
try to fix the issues.

- Part 1: [Troubleshooting Steps for Most Issues](#troubleshooting-steps)
  - [Update your conda version](#step-1-update-your-conda-version)
  - [Delete any existing environment](#step-2-delete-any-existing-environment)
  - [Create a fresh environment](#step-3-create-a-fresh-environment)
- Part 2: [Common Problems](#common-problems)
  - ["Permission Denied" Errors on Windows](#permission-denied-errors-on-windows)
  - [SSL Connection Errors](#ssl-connection-errors)
  - [Missing package errors](#missing-package-errors)
  - [The file extension of the environment file on Windows](#the-file-extension-of-the-environment-file-on-Windows)
  - [Mixing `pip` and `conda`](#mixing-pip-and-conda)
  - [Import errors for `geopandas`](#import-errors-for-geopandas)
  - [Numpy errors](#numpy-errors)

## Troubleshooting Steps

The following troubleshooting steps can be used to try to solve common issues:

**Note:** The commands here should be executed via the command line, either
using the `Anaconda Prompt` on Windows or the `Terminal` app on MacOS.

### Step 1: Update your conda version

To make sure it isn't an issue with `conda` itself, make sure you are using the
latest version by running:

```
conda update -n base -c defaults conda
```

### Step 2: Delete any existing environment

We want to create a fresh environment, so you can delete any environment that
was giving you issues. If that environment was called `'{{ site.env_name }}'`,
you can run the following commands to delete it:

```
conda deactivate
```

```
conda env remove --name {{ site.env_name }}
```

The first command will activate the `'base'` environment and then the second
command will perform the deletion.

### Step 3: Create a fresh environment

Follow the instructions outlined
[here](/guides/conda#creating-your-initial-environment) to create a
fresh version of the course website.

## Common Problems

Below we list some of the most common issues encountered when installing packages with Anaconda.

### "Permission Denied" Errors on Windows

This is actually caused by a problem with the `conda` software on Windows. You
should be able to solve it by updating to the latest version and following the
above steps.

### SSL Connection Errors

Connection errors can also sometimes occur on Windows that will prevent new
packages being downloaded. Again, you should be able to solve it by updating to
the latest version and following the above steps.

### Missing package errors

If you have successfully followed the steps above to create your environment,
but receive an `ImportError` when importing packages, you might have launched
the notebook from the `'base'` environment instead of the `'{{ site.env_name }}`
environment. Be sure to activate the `'{{ site.env_name }}` environment before launching
the notebook.

### The file extension of the environment file on Windows

Be sure that Windows does not automatically add an `.txt` extension to your
`environment.yml` file. This will cause `conda` to fail, with a cryptic error:

```
SpecNotFound: environment with requirements.txt needs a name
```

The environment file needs to end in `.yml`. You can change the extension for a file on Windows following [these instructions](https://www.mediacollege.com/microsoft/windows/extension-change.html).

### Mixing `pip` and `conda`

The command `pip` can also be used to install Python packages. However, using `pip` to install packages into a `conda` environment can lead to issues. It's best to stick to using the `conda env update` command to update your environment or `conda install package_name` to install specific packages.

### Import errors for `geopandas`

When importing `geopandas`, you can sometimes receive errors about missing libraries. These is usually because packages got mixed up during installation.

The best and easiest thing to do to try to solve it is use the steps above to create a fresh environment.

### Numpy errors

If you receive the following error:

```
ImportError: Something is wrong with the numpy installation. While importing we detected an older version of numpy in ['/Users/nhand/miniconda3/envs/{{ site.env_name }} /lib/python3.6/site-packages/numpy']. One method of fixing this is to repeatedly uninstall numpy until none is found, then reinstall this version.
```

Make sure you are running the latest conda (see Step 1 above), and then from the Anaconda Prompt (Windows) or Terminal (Mac), run:

```
conda install --force-reinstall --clobber numpy
```
