---
title: Higher-Order Network Models for Temporal Network Data
permalink: /setup
---

# Using git to obtain tutorial material

While you can manually download all necessary [`code`](https://github.com/IngoScholtes/eurocss2019-tutorial/tree/master/code) and [`data`](https://github.com/IngoScholtes/eurocss2019-tutorial/tree/master/code) files from our [gitHub repository](https://github.com/pathpy/pathpy-tutorials), we strongly recommend to clone this repository with `git` to obtain a local, sychronised copy of all material. Assuming you have a working `git` installation, you can do this by executing the following command in the terminal:

```
git clone --depth 1 --branch NetSciX-2020 https://github.com/pathpy/pathpy-tutorials
```

The option `--depth 1` ensures that you only get the latest version, ignoring the history of the repository. Furthermore, the option `--branch NetSciX-2020` ensures that you get the right tutorials.  If you don't have `git` installed already, here you can find information on [how to set up git](https://help.github.com/articles/set-up-git/).

In the [`code` directory](https://github.com/IngoScholtes/eurocss2019-tutorial/tree/master/code) of the repository, you will find the code files that we will work through during the tutorial.  These files contain explanations, as well as python code that we will explain during the live coding sessions. As we make changes to these files, you can sync your local copy with the tutor. Just execute the terminal command

```
git pull
```

to receive the latest updates. If you are using Visual Studio Code (see below) this is even easier: Just click the **sync** symbol in the status bar to update the current sample solution shown on the tutor's screen!

# Installing python 3.X

To complete the hands-on exercises, you will need a working `python 3.x` environment running on an operating system of your choice. For Windows, MacOS, and Linux users we recommend to install the latest [Anaconda](https://www.anaconda.com/download/) distribution, an OpenSource `python` 3.7 distribution that comes pre-configured for data science and machine learning tasks.

The only additional package that you may need for this tutorial is the package [markdown](https://pypi.org/project/Markdown/). We use it to produce nicely formatted output with the python skeleton files. You can just install it by typing:

```
pip install markdown
```

# Installing Visual Studio Code

To complete the exercises, we recommend using the development environment [Visual Studio Code](https://code.visualstudio.com/Download), a platform-independent Open Source code editor available for Windows, MacOS, and Linux. Just download the installation file and run the setup. Once the installation has completed, run Visual Studio Code either by clicking the icon or by typing `code` in the terminal.

To conveniently work with `python` and `jupyter` notebooks in Visual Studio Code, we recommend an extension, which you can install free of charge directly from Visual Studio Code's integrated extension manager. We will need the official [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) extension, which adds `python` code editing, debugging, and linting functionality. This extension provides a convenient interface to the `jupyter` notebook server automatically installed by `Anaconda 2019.07`.

To install the extension, click the "module" icon in the bottom of the left menu bar or press `Ctrl+Shift+X`. This will bring up the Extensions window. Type `python` and click the top-most search result [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python). In the window on the right, click install. A restart of Visual Studio Code completes the installation.

Once the installation is finished, open Visual Studio Code, click `File -> Open Folder` and navigate to your local copy of the cloned github repository. In the *Explorer* panel (the files symbol in the left bar) you can then find the notebook files that you need to complete the tutorial.

Conveniently, Visual Studio Code comes with integrated support for `git`. This means you can fetch the current, growing sample solution simply by navigating to the *Source Control* panel (the fork symbol in the left bar). In the *...* menu extension you just have to click *Pull*.

## Setting up [pathpy](http://www.pathpy.net)

`pathpy` is pure python code and is available under an OpenSource license. It has no platform-specific dependencies and thus work on all platforms.  It depends on `numpy` and `scipy` which come preinstalled in the Anaconda 5.2 environment. Assuming that you have `python 3.x` environment, the latest version of `pathpy` can be installed via the [python package index pypi](https://pypi.org/project/pathpy3/). Just open a terminal window and run the command:

```
pip install pathpy3
```
