Welcome to the sktime workshop at prologue day of HAICON 2025
============================================================

This tutorial is about [sktime] - a unified framework for machine learning with time series. sktime contains algorithms and tools for building, applying, evaluating modular pipelines and composites for a variety of time series learning tasks, including forecasting, classification, regression.

This tutorial gives a walkthrough of forecasting and benchmarking forecasters with `sktime` 

[sktime]: https://www.sktime.net

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sktime/tutorial_haicon_prologue_day/HEAD) [![!discord](https://img.shields.io/static/v1?logo=discord&label=discord&message=chat&color=lightgreen)](https://discord.com/invite/54ACzaFsn7) 

## :rocket: How to get started

In the tutorial, we will move through notebooks section by section.

You have different options how to run the tutorial notebooks:

* Run the notebooks in the cloud on [Binder] - for this you don't have to install anything!
* Run the notebooks on your machine. [Clone] this repository, and install all dependencies by pip install -r requirements.txt

## :bulb: Description

This tutorial is structured into four notebooks:
* Short introduction into sktime and how you can use sktime for various tasks (classification, anomaly detection, forecasting)
* Notebook focusing on advanced features for time series forecasting:
  * Building pipelines in sktime to perform time series forecasting
  * Using foundation models for forecasting in sktime. 
* benchmarking forecasting algorithms in sktime
* outlook on upcoming benchmarking features and call for contributions

We invite anyone to get involved as a developer, user, supporter (or any combination of these).


## :movie_camera: Other Tutorials

- [Europython 2023 - General sktime introduction, half-day workshop](https://github.com/sktime/sktime-tutorial-europython-2023)

- [PyCon Prague 2023 - Forecasting, Advanced Pipelines, Benchmarking](https://github.com/sktime/sktime-tutorial-pydata-global-2023)

- [Pydata Amsterdam 2023 - Probabilistic prediction, forecasting, evaluation](https://github.com/sktime/sktime-tutorial-pydata-Amsterdam-2023)

- [ODSC Europe 2023 - Forecasting, Pipelines, and ML Engineering](https://github.com/sktime/sktime-tutorial-ODSC-Europe-2023/tree/main)

- [Pydata London 2023 - Time Series Classification, Regression, Distances & Kernels](https://github.com/sktime/sktime-tutorial-pydata-london-2023)

- [Pydata Berlin 2022 - Advanced Forecasting Tutorial](https://www.youtube.com/watch?v=4Rf9euAhjNc)

- [Pydata London 2022 - How to implement your own estimator in sktime](https://www.youtube.com/watch?v=S_3ewcvs_pg)

- [Pydata Global 2022 - Feature extraction, Pipelines, Tuning](https://github.com/sktime/sktime-tutorial-pydata-global-2022)


## :wave: How to contribute

If you're interested in contributing to sktime, you can find out more how to get involved [here](https://www.sktime.net/en/latest/get_involved.html).

Any contributions are welcome, not just code!

## Installation instructions for local use

To run the notebooks locally, you will need:

* a local repository clone
* a python environment with required packages installed

### Cloning the repository

To clone the repository locally:

`git clone https://github.com/sktime/sktime-tutorial-pydata-global-2023`

### Using python venv

1. Create a python virtual environment:
`python -m venv sktime_pydata`
2. Activate your environment:
 - `source sktime_pydata/bin/activate` for Linux
 - sktime_pydata/Scripts/activate` for Windows
3. Install the requirements:
`pip install -r requirements`
4. If using jupyter: make the environment available in jupyter:
`python -m ipykernel install --user --name=sktime_pydata`