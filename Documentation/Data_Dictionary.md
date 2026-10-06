# Data Dictionary

## Overview

This data dictionary documents the fields used in the Music Industry Executive Dashboard.

## Albums Table

| Field | Description | Data Type | Usage |
|---|---|---|---|
| Band Name | Name of the band associated with the album | Text | Used to identify and compare bands |
| Release Year | Year the album was released | Whole Number | Used for time-based analysis and filtering |
| Certified Sales | Certified album sales associated with the band/album | Numeric | Used to calculate sales KPIs and rankings |
| Genre | Music genre associated with the band/album | Text | Used for genre analysis and filtering |

## Bands Table

| Field | Description | Data Type | Usage |
|---|---|---|---|
| Band Name | Name of the band | Text | Used to identify bands and establish relationships with album data |

## Measures

| Measure | Description |
|---|---|
| Total Bands | Counts the number of bands represented in the dataset |
| Total Albums | Counts the number of albums represented in the dataset |
| Total Certified Sales | Calculates total certified sales |
| Average Certified Sales | Calculates average certified sales |
| Average Albums per Band | Calculates the average number of albums per band |

## Relationships

The Power BI data model uses a relationship between the `Bands` and `Albums` tables through the band name field.

This relationship allows band-level information to interact with album-level metrics throughout the dashboard.