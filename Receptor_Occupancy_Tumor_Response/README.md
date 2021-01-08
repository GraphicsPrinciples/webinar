Receptor Occupancy Tumor Response
================

This repository contains materials for a hands on example for the
Effective Visual Communication Webinar.

  - [Purpose\_Worksheet.docx](Purpose_Worksheet.docx) is a partially
    completed Purpose Worksheet setting up the purpose for the
    visualization exercise.
  - [Receptor\_Occupancy\_Tumor\_Response.csv](Receptor_Occupancy_Tumor_Response.csv)
    is a dataset that can be used to generate visualizations for the
    exercise.

# Background

This example is inspired by an early oncology clinical trial. Receptor
occupancy, tumor size, and RECIST criteria have been altered and no
longer reflect the properties of a real drug or trial.

Situation:

  - Results are available from an early oncology drug trial showing
    tumor shrinkage and response in a subset of patients
  - Data available include average receptor occupancy (a function of
    drug exposure)
  - Primary endpoint was overall response (partial or complete response
    according to RECIST criteria)
  - Secondary endpoint was percent change from baseline tumor diameter

Complication:

  - Trial had no control / placebo arm, so not immediately clear whether
    the tumor shrinkage and response rates are related to treatment

Question:

  - Is there a way to show the drug is working?

# Purpose

The Purpose Worksheet is intended to help with Step 1 of Effective
Visual Communication (i.e., have a clear purpose). For this exercise, we
have partially completed the
[Purpose\_Worksheet](Purpose_Worksheet.docx) for you, based on the
background information above. Review the partially completed worksheet,
make any changes you wish, and complete what hasn’t been filled in.

# Data

A simulated dataset has been provided for this example:
[Receptor\_Occupancy\_Tumor\_Response.csv](Receptor_Occupancy_Tumor_Response.csv).
Part of this exercise involves you choosing what data to display and
how, in order to support the Purpose. You may or may not use all of the
information supplied in the dataset.

The dataset represents a set of individual patients following treatment
with the oncology drug. The dataset contains individual average receptor
occupancy information (a function of drug exposure), as well as
individual tumor size and RECIST criteria. Below are descriptions of the
variables in the dataset

  - **ID** - unique subject identifier
  - **RO\_AVG** - average receptor occupancy (%)
  - **Tumor\_PCFBSL** - percent change from baseline in tumor diameter
    (%)
  - **RECIST** - RECIST criteria (“PD”, “SD”, “PR”, “CR”)
  - **RECIST\_LABEL** - RECIST criteria descriptor (“PD - Progressive
    Disease”, “SD - Stable Disease”, “PR - Partial Response”, “CR -
    Complete Response”)

Below find the first six rows of the dataset. Access the full dataset
here:
[Receptor\_Occupancy\_Tumor\_Response.csv](Receptor_Occupancy_Tumor_Response.csv)

| ID | RO\_AVG | Tumor\_PCFBSL | RECIST | RECIST\_LABEL            |
| -: | ------: | ------------: | :----- | :----------------------- |
|  1 |     0.8 |           600 | PD     | PD - Progressive Disease |
|  2 |     0.8 |           500 | PD     | PD - Progressive Disease |
|  3 |     4.0 |           280 | PD     | PD - Progressive Disease |
|  4 |     0.8 |           300 | PD     | PD - Progressive Disease |
|  5 |     6.4 |           210 | PD     | PD - Progressive Disease |
|  6 |    12.8 |           205 | PD     | PD - Progressive Disease |
