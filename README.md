# Multi-Property Molecular Design on HPC

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/globus-labs/molecular-design-at-scale/HEAD)

This repository contains a tutorial showing how to rapidly design molecules which meet several proeprties by using Bayesian optimization on HPC.

The objective of this application is to identify which molecules have the largest ionization energies (IE, the amount of energy required to remove an electron) _and something else (TBD).

IE can be computed using various simulation packages (here we use [MOPAC](http://openmopac.net/)); however, execution of these simulations is expensive, and thus, given a finite compute budget, we must carefully select which molecules to explore. 

In this example, we use machine learning to predict molecules with high IE based on previous computations (a process often called [active learning](https://pubs.acs.org/doi/abs/10.1021/acs.chemmater.0c00768)). We iteratively retrain the machine learning model to improve the accuracy of predictions. 

## Running the Tutorial

The tutorial is designed to work on Binder so that you can run it without installing anything.

Just click this link: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/globus-labs/molecular-design-at-scale/HEAD)

### Running Locally

Running with local resources can be much faster and allow you to save changes you make to the notebooks.

The demo uses a few codes that are easiest to install with Anaconda. Our environment should work on both Linux and OS X (though M1 systems can be problematic) and can be installed by:

```bash
conda env create --file environment.yml
```
## Tutorial Guide

TBD
