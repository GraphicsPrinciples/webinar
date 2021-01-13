Missed Doses Due to COVID-19
================

This repository contains materials for a hands on example for the
Effective Visual Communication Webinar.

  - [Purpose\_Worksheet.docx](Purpose_Worksheet.docx) is a partially
    completed Purpose Worksheet setting up the purpose for the
    visualization exercise.
  - [Missed\_Doses\_Due\_to\_COVID.csv](Missed_Doses_Due_to_COVID.csv)
    is a dataset that can be used to generate visualizations for the
    exercise.

# Background

This example is inspired by a drug being tested in a Phase 3 study
during the COVID-19 pandemic. Drug kinetics and endpoints have been
altered and no longer reflect the PKPD/efficacy properties of a real
drug.

Situation:

  - A Phase 3 time to event trial is being conducted for Drug A during
    the COVID-19 pandemic.
  - Drug A is administered in the clinic by a health care provider.

Complication:

  - The clinical trial team has noticed a pattern of patients missing
    dosing visits
  - Due to the COVID-19 pandemic, patients’ access to the clinic has
    been greatly impacted, resulting in patients missing one or more
    dosing visits.
  - The project team is considering whether mitigation is required, and
    if so what action should be taken.

Question:

  - What effect would 1, 2, or 3 missed doses have on the efficacy of
    the current trial?
  - Should the trial be stopped? Should the trial management team make
    significant efforts to increase compliance? Or is the predicted
    impact of these missed doses negligible?

# Purpose

The Purpose Worksheet is intended to help with Step 1 of Effective
Visual Communication (i.e., have a clear purpose). For this exercise, we
have partially completed the
[Purpose\_Worksheet](Purpose_Worksheet.docx) for you, based on the
background information above. Review the partially completed worksheet,
make any changes you wish, and complete what hasn’t been filled in.

# Data

A simulated dataset has been provided for this example:
[Missed\_Doses\_Due\_to\_COVID.csv](Missed_Doses_Due_to_COVID.csv). Step
2 of Effective Visual Communication involves you choosing what data to
display and how, in order to support the Purpose. You may or may not use
all of the information supplied in the dataset.

The dataset represents a simulated set of individual patients following
placebo, continuous treatment, or 1, 2, or 3 missed doses of Drug A. The
dataset contains individual drug exposure information, as well as
individual time-to-event information for the primary endpoint which is a
time-to-event endpoint. Below are descriptions of the variables in the
dataset

  - **id** - unique subject identifier
  - **TRT** - treatment group, including number of missed doses (values:
    “Continuous Treatment”, “1 dose missing”, “2 dose missing”, “3 dose
    missing”, “Placebo”)
  - **time** - time of event (years)
  - **status** - event identifier (1 = right censored / lost to follow
    up, 2 = event of interest / primary endpoint)
  - **label** - description of event (values: “censored”, “event”)
  - **avgAUC** - average drug exposure up to the time of the event
    (ng/mL)
  - **avgAUEC** - average change from baseline in PD marker up to time
    of event (mmol/L)
  - **HRR** - model predicted relative change in hazard (relative to
    placebo) based on avgAUEC

Below find the first six rows of the dataset. Access the full dataset
here: [Missed\_Doses\_Due\_to\_COVID.csv](Missed_Doses_Due_to_COVID.csv)

| id | TRT     | time | status | label    | avgAUC |    avgAUEC |        HRR |
| -: | :------ | ---: | -----: | :------- | -----: | ---------: | ---------: |
|  1 | Placebo | 1.60 |      1 | censored |      0 | \-0.052686 | \-0.026343 |
|  2 | Placebo | 0.70 |      2 | event    |      0 | \-0.260150 | \-0.130070 |
|  3 | Placebo | 2.90 |      1 | censored |      0 |   0.455220 |   0.227610 |
|  4 | Placebo | 1.95 |      2 | event    |      0 |   0.381400 |   0.190700 |
|  5 | Placebo | 1.95 |      1 | censored |      0 |   0.278710 |   0.139360 |
|  6 | Placebo | 1.15 |      1 | censored |      0 |   0.069280 |   0.034640 |

# Downloading data

**NOTE** to download a single data set locally as a [csv
file](https://raw.githubusercontent.com/GraphicsPrinciples/webinar/main/Missed_Doses_Due_to_COVID/Missed_Doses_Due_to_COVID.csv),
click on the raw button and save the
[file](https://raw.githubusercontent.com/GraphicsPrinciples/webinar/main/Missed_Doses_Due_to_COVID/Missed_Doses_Due_to_COVID.csv).
The [following link describes the process in further
detail](https://stackoverflow.com/questions/4604663/download-single-files-from-github).
