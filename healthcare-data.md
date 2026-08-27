---
title: Health Care Data
description: Ready-to-use datasets on DataHub about Health Care.
keywords: Healthcare, DNA Sequencing Costs, Pharmaceutical Drug Spending by countries and Data Analytics, Medicare, Medicaid, Assisted Living Waiver, California, Quebec emergency department occupancy
date: 2018-06-07
modified: 2026-08-27
---

## Costs assosiated with DNA sequencing since 2001

DNA Sequencing Costs:

[core/genome-sequencing-costs](https://datahub.io/core/genome-sequencing-costs)

## Pharmaceutical Drug Spending by countries (data analytics)

Pharmaceutical Drug Spending by countries with indicators such as a share of total health spending, in USD per capita (using economy-wide PPPs) and as a share of GDP. Plus, total spending by each countries in the specific year:

[core/pharmaceutical-drug-spending](https://datahub.io/core/pharmaceutical-drug-spending)

## Medicare and Medicaid Data

[Data.CMS.gov](https://data.cms.gov) gives you direct access to public data released by the Centers for Medicare & Medicaid Services (CMS). All data is available for free as public use files and they have an extensive API. Data covers an array of topics, including high level information about the programs and their spending, beneficiary characteristics, and information about healthcare providers.

## California Assisted Living Waiver Facilities

The [California Assisted Living Waiver county tracker](https://californiacarecompass.com/data/california-alw-county-tracker-2026) covers 1,224 participating facilities across 15 counties, with facility contact details, coordinates, licensed capacity and county totals. The data is derived from the California Department of Health Care Services' public ArcGIS service. Downloadable CSV and JSON files, a data package, license and reproducible source script are available in the [companion open-data repository](https://github.com/asafichaki/california-alw-open-data).

## Québec emergency department occupancy, hourly

Hourly stretcher occupancy for the 120 emergency departments in Québec, archived from the health ministry's extraction file. The ministry overwrites that file at each extraction. [Urgences Québec](https://sante.handled.tools) serves the archive as JSON, no key. `/api/facilities` lists the 120 installations: permit number, establishment, region code and name, street address, phone, lat/lng. `/api/facility/<permit>/history` returns about 160 hourly points per site, roughly seven days, each with `occ_pct`, `present` and `waiting`.
