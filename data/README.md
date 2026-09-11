# Data Access and Expected Schema

The original participant-level NIPT dataset is intentionally excluded from this public repository because it contains sensitive prenatal screening and pregnancy-related records.

To reproduce the analysis, use an appropriately authorized and de-identified workbook saved as `data/nipt_data.xlsx`. The expected worksheet names are `male_data` and `female_data`.

Expected English columns include:

- `maternal_id`
- `maternal_age`
- `maternal_height_cm`
- `maternal_weight_kg`
- `gestational_age`
- `maternal_bmi`
- `test_date`
- `conception_method`
- `raw_read_count`
- `mapping_ratio`
- `duplicate_ratio`
- `unique_read_count`
- `gc_content`
- `z13`, `z18`, `z21`, `zx`, and `zy` where applicable
- `x_chromosome_fraction` and `y_chromosome_fraction` where applicable
- `gc13`, `gc18`, and `gc21`
- `filtered_read_ratio`
- `aneuploidy` or `T13`, `T18`, and `T21`
- `pregnancy_count`
- `parity`
- `fetal_health`

Do not commit identifiable or participant-level health data to a public repository without explicit authorization.

