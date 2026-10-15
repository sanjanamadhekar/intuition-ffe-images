# Intuition FF&E images

Public product images for the FF&E test dataset in the private `Intuition` repo
(`reference/ffe/FFE_test_dataset.xlsx`). They live here, in a public repo, so the
workbook's `=IMAGE()` formulas render in Google Sheets, which only loads public URLs.

- `ffe/images/`: one file per picture on the workbook's Products sheet, named
  `r<sheet row>_<column>_<SKU>.<ext>`.
- `ffe/images.csv`: which cell each picture belongs to.

Everything here is from US hospitality suppliers' own public websites and product guides
(Bernhardt, Foliot, Kimball, Sara). Don't put Inhabitr or factory data in this repo.
