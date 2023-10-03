# SEAIQHRD Epidemic Model

This repository contains MATLAB code, documentation, and resources related to the SEAIQHRD epidemic model. The SEAIQHRD model is an epidemiological model used to study the spread of infectious diseases with a more detailed representation of disease stages compared to simpler models like SIR or SEIR.

## About

In this project, we use the SEAIQHRD model to compare three different pandemics - SARS, Measles, and COVID-19, in order to identify effective mitigation efforts to reduce infectious rates in the future, specifically the effects of quarantining. 


## Model Description

The SEAIQHRD model is an extension of traditional compartmental models used in epidemiology. The acronym SEAIQHRD stands for:

- **S**usceptible: Individuals who are not infected but can become infected.
- **E**xposed: Individuals who are exposed to the disease but not yet infectious.
- **A**symptomatic: Individuals who are infected but do not show symptoms.
- **I**nfectious: Individuals who are infected and capable of spreading the disease.
- **Q**uarantined: Individuals who are isolated to prevent further transmission.
- **H**ospitalized: Individuals requiring hospitalization.
- **R**ecovered (or Removed): Individuals who have recovered from the disease or, in some cases, have died from it.

The model tracks how individuals transition between these compartments over time using differential equations.

## Report Description

The "Report Math 435" PDF file contains a comprehensive analysis of the SEAIQHRD epidemic model. It covers the following key aspects:

- Introduction to the SEAIQHRD model.
- Detailed mathematical equations and modeling parameters.
- Analysis of epidemic scenarios and simulations.
- Conclusions and discussions based on the analysis.

The "MATLAB" docx contains the MATLAB code for the SEAIQHRD Model as well as instructions on how to run it properly. 
