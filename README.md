# NO3_DMQC_Prep
# NOAA Lapenta Internship Project 

**My Project:** Extension of a Python package for quality control of Argo float data (OAR)

**Project Description** The goal of this project is to extend the capabilities of an existing Python package for delayed mode quality control of Argo float data. 
* It currently handles only oxygen, the goal is to handle at least one other biogeochemical variable, e.g., nitrate. (The full set also includes pH, chlorophyll, and backscatter.) 
* New functions and notebooks to demonstrate the new features need to be developed.

**Expected Outcome** The expected outcome is an expanded Python package with the capability to perform delayed mode quality control on oxygen and at least one other biogeochemical variable.

**Duties and Responsibilities** The intern will act as the primary software developer. This will include design, implementation, debugging, testing, and documenting of the code.

## Back Ground Information 

Link to BCG Argo Website: https://biogeochemical-argo.org/index.php

## Setting up the Github

Link to reference Github: https://github.com/ArgoCanada/bgcArgoDMQC

Link to our forked Github: https://github.com/hfrenzel-noaa/bgcArgoDMQC

**Vocab**
* DMQC - Delayed Mode Quality Control
* WOA - World Ocean Atlas

## SAGE GUI 

Link to reference Github: https://github.com/SOCCOM-BGCArgo/ARGO_PROCESSING

Runs through MATLAB, but we want to replicate some functions in python
* ischange function

## Ruptures Package

Link to reference Github:
* https://centre-borelli.github.io/ruptures-docs/
* https://pypi.org/project/ruptures/

Similar to ischange function from MATLAB in python
* Used to find the change points in the data


## Plans:
Look into the files bgcArgoDMQC and take notes on the code to understand it 
* DMQC for float 7902199 as a test
* Work with the SAGE GUI
* Familiarize flt object  - in core, 
* calc gains - sprof calc_gains function
* netcdf read and see files, specifically: PRES & NITRATE
* Understand and utilize ruptures library
* Work to find change points, calculate drift and offset

Main plan is to create the background functions especially one called calcadjustments which will work behinds the scenes and calculate gain and mean
