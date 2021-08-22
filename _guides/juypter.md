---
layout: page
title: Jupyter User Guide
permalink: /guides/jupyter
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

We will use the [Jupyter
notebook](https://jupyter-notebook.readthedocs.io/en/stable/) to run our Python
data analysis in this course. If you've successfully installed and activated the
environment for this course, the Jupyter notbook package should already be
installed.

On this page, I'll discuss two common issues when starting out with Jupyter
notebooks: launching a notebook and ensuring the right files are available.

I **strongly encourage** you to go through the official documentation for the Jupyter notebook:

- [Introduction](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#introduction)
- [Starting the notebook server](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#starting-the-notebook-server)
- [Creating a new document](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#creating-a-new-notebook-document)
- [Opening notebooks](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#opening-notebooks)
- [Notebook user interface](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#notebook-user-interface)
- [Structure of a notebook document](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#structure-of-a-notebook-document)
- [User interface components](https://jupyter-notebook.readthedocs.io/en/stable/ui_components.html)

## Launching a Jupyter notebook

The recommended approach for starting a notebook is to use the Anaconda Prompt
on Windows or the Terminal app on MacOS. To do so, we simply need to activate
our `'{{ site.env_name }}'` environment and then launch the notebook.

From the command line, run:

```
conda activate {{ site.env_name }}
```

```
jupyter notebook
```

This will create the local Jupyter server and should launch
the _Jupyter dashboard_. If it does not open in a browser,
copy the link that is output by the command into your favorite browser.
Typically, the server will be running at http://localhost:8080.
The dashboard should like look this:

<img src="https://jupyter.readthedocs.io/en/latest/_images/tryjupyter_file.png">

Once the server is running, you can create a new notebook and get started!

A new notebook can be created either from the dashboard, or using
the File ‣ New menu option from within an active notebook. The new notebook is
created within the same directory and will open in a new browser tab.

<img src="https://jupyter-notebook.readthedocs.io/en/stable/_images/new-notebook.gif">

[Source: Jupyter Notebook documentation](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#starting-the-notebook-server)

The following shows the basic user interfaces of a Jupyter notebook:

<img src="https://jupyter-notebook.readthedocs.io/en/stable/_images/blank-notebook-ui.png">

For detailed explanations of these components, see the [Jupyter notebook documentation](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#notebook-user-interface) on the
user interface. There is also a [more detailed section](https://jupyter-notebook.readthedocs.io/en/stable/ui_components.html) on the user interface components.

## Changing the Jupyter notebook start-up folder

By default, the Jupyter notebook launches from the home directory. When you
see the Notebook dashboard, you should see all of the files in this
folder.

When working with weekly lectures or assignments, it is easiest to open notebooks
from the specific assignment or week folder that you are working on.

To do so, it will be easiest to change the directory before launching the
Jupyter notebook:

### Step 1: Change to the desired directory

Let's imagine we want to change to a folder named:

/Users/YourUserName/MUSA_550 (on a Mac),

or

C:\Users\YourUserName\MUSA_550 (on Windows)

If you need help finding the folder name's path, [this guide for Windows](https://www.wikihow.com/Find-a-File%27s-Path-on-Windows). (I usually use Method #2). On MacOS, you can use [this guide](http://osxdaily.com/2015/11/05/copy-file-path-name-text-mac-os-x-finder/) to copy a folder's path name.

Next, use the following steps:

**Step 1.** On Windows, open the Anaconda Prompt, or on Mac, open the Terminal.

**Step 2.** Navigate to the folder where the environment file is located. From the Prompt or Terminal run:

**Windows**

```
cd C:\Users\YourUserName\MUSA_550
```

**Mac**

```
cd /Users/YourUserName/MUSA_550/
```

### Step 2: Launch the Jupyter notebook

Now, type the following command, either in Anaconda Prompt or the Terminal:

```
jupyter notebook
```

And the launched notebook will start from your desired folder!
