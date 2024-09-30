# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html). Dates formatted as YYYY-MM-DD as per [ISO standard](https://www.iso.org/iso-8601-date-and-time-format.html).

The following are in progress, and are a record of changes between various branches and release, to be used when creating the next release/s...

## dev_amy and dev

### Added

* GitHub action to deploy book on push to main
* Copy of environment as `requirements.txt` for GitHub action (as conda environment was very slow and had an error)

### Changed

* Add logo and fixed GitHub url in `_config.yml`
* Minor alterations for clarity, spelling, grammar or corrections in `README.md` and `content/`

## dev and main

### Changed

* Add rich to environment
* Updated tracing in `content/02_model_code/04_model.ipynb`

## main and release v1.1.2

### Added

* Notebooks/pages on testing (`content/02_model_code/05_testing.ipynbg`) and the test package (`content/02_model_code/06_test_package.ipynb`)
* Example data for tests
* Process flow diagram

### Changed

* Citation, links and minimum python version on various pages
* Updated and altered `environment.yml`
* Updated `src/treat_sim/model.py`, `content/02_model_code/04_model.ipynb` and `src/full_model.ipynb`

## v1.1.2 - 2024-05-02

### Changed

* PATCH: Pathway sampling now correctly uses `self.args` to select distributions.

## v1.1.1 - 2024-05-01

### Changed

* PATCH: Trauma patient treatment fixed to use the correct sampling distribution (mistakenly using stabilisation).

## v1.1.0 - 2023-10-30

The materials and methods in this repository support work towards developing the S.T.A.R.S healthcare framework (**S**haring **T**ools and **A**rtifacts for **R**eusable **S**imulations in healthcare).  The code and written materials here demonstrate the application of S.T.A.R.S' version 1 to sharing a `simpy` discrete-event simuilation model and associated research artifacts.  

* All artifacts in this repository are linked to study researchers via ORCIDs;
* Model code is made available under a MIT license;
* Python dependencies are managed through `conda`;`
* The python code itself can be viewed and executed in Jupyter notebooks via [Binder](https://mybinder.org); 
* The model is documented and explained in a [Jupyter book website](https://pythonhealthdatascience.github.io/stars-simpy-examplar-docs) served up by GitHub pages;
* The materials are deposited and made citatable using Zenodo;
* The models are sharable with other researchers and the NHS without the need to install software.
