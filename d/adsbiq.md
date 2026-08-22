---
title: "ADSBiq: Daily open ADS-B aircraft history"
created: 2026-08-22
published: 2026-08-22
homepage: https://adsbiq.com/api/other/parquet
---

[ADSBiq](https://adsbiq.com) publishes free daily worldwide aircraft state-diff data from its community feeder network as compressed Apache Parquet. Records are time-ordered snapshots, sparse changes, and removals that can be reconstructed into aircraft state while avoiding repeated full snapshots.

The public repository includes a small sample, schema documentation, loading examples, ODbL-1.0 licensing, monthly release assets with per-day row counts and SHA-256 checksums, and a machine-readable Frictionless Data Package descriptor.

Dataset and Data Package: https://github.com/Sky-Power-Services/adsbiq-data

Documentation: https://adsbiq.com/api/other/parquet