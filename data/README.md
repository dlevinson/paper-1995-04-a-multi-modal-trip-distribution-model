# Data And Derived Tables

Generated: 2026-05-16 15:36:57 AEST

The paper states that the trip-distribution model was estimated from detailed person travel surveys conducted by the Metropolitan Washington Council of Governments in 1968 and 1987/1988, with the 1988 survey used to estimate trips by five-minute time band for mode and purpose. The package does not include raw household/person/trip microdata.

This data folder contains paper-specific derived/aggregate artifacts from the TRR-MULTIMODAL source folder:

- `multimodal_trip_distribution/source_workbooks/original_legacy/`: original Lotus/Excel-era workbooks for impedance coefficients, time-band travel distributions, accessibility examples, and validation tables.
- `multimodal_trip_distribution/source_workbooks/modern_author_or_prior_conversion/`: XLSX versions found in the source folder.
- `multimodal_trip_distribution/modernized/xlsx/`: modern XLSX sidecars for legacy workbook inspection.
- `multimodal_trip_distribution/modernized/csv/`: nonblank CSV worksheet exports from the modernized workbooks.
- `multimodal_trip_distribution/source_data/`: printed/SPSS-style derived distribution table export.
- `multimodal_trip_distribution/figures/original_legacy/`: legacy drawing/source files for paper figures.

Blank chart/worksheet CSV exports, `.ods` conversion intermediates, drafts, letters, slides, and manuscript submissions were excluded. See `../documentation/SOURCE_FILE_REVIEW.csv` and `../documentation/EXCLUDED_SOURCE_MATERIALS.csv`.

Exact duplicate CSV worksheet exports were removed after conversion. See `../documentation/INTERNAL_DEDUPLICATION.csv` for retained canonical paths and duplicate pointers.
