# Introduction to *HyperSpy*, *LumiSpy* and *eXSpy*

> **Spectroscopy Data Analysis in Python Using [HyperSpy](https://hyperspy.org)**

Tutorial for the **[eBEAM2024](https://ebeam2024.sciencesconf.org/) school on nano-optics with free electrons**

> Aussois, September 1-13, 2024

---------------

**Dear attendants of the eBEAM summer school,**

we are happy to introduce you to data analysis using [HyperSpy](https://hyperspy.org) and its extensions [LumiSpy](https://lumispy.org) and [exSPy](https://hyperspy.org/exspy) at the eBEAM 2024. 

To follow the interactive tutorials and make maximum use of the limited time available, we kindly ask you to bring your laptop and already install the **[HyperSpy-bundle](https://hyperspy.org/hyperspy-bundle/)** matching your system before coming to the school. The [HyperSpy bundle](https://hyperspy.org/hyperspy-bundle/) ships a python environment including all relevant packages.

Edit: The slides from the HyperSpy lecture at the summer school can now also be found in this repository: [eBEAM24_HyperSpy-LumiSpy-eXSpy.pdf](eBEAM24_HyperSpy-LumiSpy-eXSpy.pdf) (use the rightclick menu to download separately from the rest of the repository).

## Installing HyperSpy

Follow the [installation guide for the HyperSpy bundle](https://hyperspy.org/hyperspy-bundle/install.html). The demo notebooks have been tested to run on the HyperSpy bundle version `2024.07.15`. Some of the examples might not run with older HyperSpy versions (`<2.0.0` / bundle releases up to `2023.11.20`) and we do not guarantee for operation with newer HyperSpy versions, though the syntax/API should not change until the next major release (`v3.0.0`) will be released.

If you already have python installed on your system and prefer not installing the bundle, we recommend creating a new environment for the tutorial and installing at least the following packages using *pip* or *conda*:

``hyperspy, exspy, lumispy, hyperspy-gui-ipywidgets, jupyter-lab, ipympl, scikit-learn, numba``

*Note that you should have at least version `1.26.4` of `numpy` installed.*

Otherwise, have a look at the full [list of packages included in the HyperSpy-bundle](https://hyperspy.org/hyperspy-bundle/index.html#included-software-and-libraries).

*(if you run into problems, a number of experienced colleagues can help you in the breaks of the summer school)*

## Download tutorial for local execution:

The tutorials are based on [Jupyter Notebooks](http://jupyter.org/).

**[Download the tutorial notebooks and demo data as zip file](https://github.com/LumiSpy/eBEAM2024-Tutorial/archive/refs/heads/main.zip)** from this repository and unpack in a local directory.

The tutorial is split in three jupyter notebooks to cater both for participants with ot without precious experience using HyperSpy:
- `1_Intro_HyperSpy-LumiSpy-eXSpy.ipynb` - A basic introduction to HyperSpy to get started with core functionalitie
- `2_AdvancedExamples_HyperSpy-LumiSpy-eXSpy.ipynb`- Some more advanced usages examples for users with previous experience
- `3_MachineLearning_Plasmonic_EELS_BlindSourceSeparation.ipynb` - A dedicated file introducing the machine learning features for denoising and decomposition of spectral maps

The relevant datasets are provided in the subfolder `data`.

## Launch jupyter-lab

If possible, try to already launch `jupyter-lab` on your computer and open the first tutorial notebooks to make sure that we can directly dive into the HyperSpy usage during the tutorials.

There are multiple ways to start `jupyter-lab`, see for example the [JupyterLab User Guide](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) or the [Ansys JupyterLab Quick Start Guide](https://developer.ansys.com/blog/jupyterlab-quick-start).

## Introduction to python

If you are new to programming or programming with python, we recommend the [W3 schools Python Tutorial](https://www.w3schools.com/python/default.asp).


## Visualising and running the tutorials online:

(Non-interactive) Visualizing the tutorial notebooks online:

[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](https://nbviewer.org/github/lumispy/eBEAM2024-Tutorial/tree/main/)

(Interactive) Running the tutorial notebooks online (may be slow):

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/lumispy/eBEAM2024-Tutorial/main)
