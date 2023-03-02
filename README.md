# FitBit fitness Data analysis using R

## Phase I: Ask
**Project goal**

Analyze smart device usage data to gain insight into how people are using their smart devices.

**Overall business Goal**

Seeking new growth opportunities in smart devices industry.

**Skate holders**

Bellabeat executive team Bellabeats marketing strategy

## Phase II: Prepare

**Data source**

A Kaggle data set: [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit), Public Domain, collected under [research study](https://www.researchprotocols.org/2017/4/e66/) published in JMIR research publication.

**Date description**

Third party data, External data Historical data *Structured data & Long data format* The data has a low confidence level with a possibly high margin error due to small sample size of 30.

**Data organized**

It is in a relational database modal merged by the users ID

**Bias**

-   Sampling bias, as the sample does not represent the whole population.

    -   According to the study made the individuals who afford wearables devices (FitBit) are mainly younger (between the ages of 18 and 34 years) and Mturkers may not be generalizable to other populations.

-   Data are only collected from people who are willing to be paid to use the device and have their non-identifiable data collected.

-   Data is missing the users gender and age which plays an important role in conclusing the analysis result.

**Data integrity**

|                     |                                                                                                                    |
|--------------------------|----------------------------------------------|
| Reliability         | Validity and uniqueness are checked in the cleaning process                                                        |
| Original            | Data is a third party                                                                                              |
| Comprehensive       | Data format in a relational data model with easily read and understood cvs files, and all files merged by their ID |
| Current             | Data collected in 2016                                                                                             |
| Cited               | [research study](https://www.researchprotocols.org/2017/4/e66/)                                                    |
| Ethics              | Approved study by the RTI International Institutional Review Board                                                 |
| Licensing & Privacy | Individual gave their consent for their data to be used                                                            |
| Accessibility       | Open source and reusable in public data base Kaggle                                                                |
| Accuracy            | Objective data as data is collected from the device directly                                                       |
| Consistency         | Data collected directly from apps sync with the devices                                                            |
| Completeness        | No missing data for each entry, by eliminating the batter life and syncing data                      

## Phase III: Process

Before analyzing, the data had to be processed cleaned. Where the data are made useful by fixing or removing incorrect, inconsistencies, incorrectly formatted, duplicate, or incomplete data within a dataset. The data cleaning and analysis are carried out using R programming language. The cleaning process in te notebook are made to some extend reusable to other datasets.

## Phase IV: Analyze & Share

Conclusions based on the data provided are down through sorting and formatting the data to make it easier to get different views, make a Pivot table, or create visual to build a story!

In this section we addressed sets of questions using:

-   Different calculations were performed to obtain additional metrics.

-   Combining different data attributes from a other datasets sources to develop a more comprehensive picture.

