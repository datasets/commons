---
title: "Statistics of the World: open high-frequency economic series"
created: 2026-10-16
homepage: https://statisticsoftheworld.com/open-data
---

Statistics of the World is an independent economic data site. It collects statistics published by national and international agencies and makes them easier to find, compare and reuse.

This dataset is its open data file: every stored reading of the high-frequency series whose source licences are open. Most are daily, weekly, monthly or quarterly; a few OECD series are annual. It covers commodity prices and exchange rates (World Bank Pink Sheet and Global Economic Monitor), US Treasury yields, consumer prices, jobs and output (BLS, BEA, EIA and the Federal Reserve Board), UK prices and GDP (ONS), EU national accounts, prices, production, trade and unemployment (Eurostat), OECD statistics on national accounts, prices, jobs, productivity, money, research spending and trade in services, plus the OECD's leading indicators and Economic Outlook forecasts, labour statistics for many countries (ILOSTAT) and electricity data (Ember).

It comes as one CSV of readings (series, country or area, period, value, status flag and licence) with a Frictionless datapackage.json that describes it and lists every series with its unit, publisher and credit line. The CSV is built from the site's database on each download, so it holds the latest stored readings.

Statistics of the World does not publish these statistics itself. The original agencies remain the authoritative source.

License: CC BY 4.0 for Statistics of the World's own work on the file (selection, cleaning, codes, labels and metadata). Each reading keeps its source licence in its `licence` column: CC BY 4.0, public domain (U.S. federal government works), the UK Open Government Licence v3.0, Commission Decision 2011/833/EU (Eurostat), or the OECD Terms and Conditions for data. Reusers credit Statistics of the World and the source named in the data package.

Useful links:

- Open data page and licence statement: https://statisticsoftheworld.com/open-data
- Data package: https://statisticsoftheworld.com/api/v1/open/datapackage.json
- Readings (CSV): https://statisticsoftheworld.com/api/v1/open/observations.csv
- API documentation: https://statisticsoftheworld.com/api-docs
- Methodology: https://statisticsoftheworld.com/methodology
- Terms of service: https://statisticsoftheworld.com/terms
