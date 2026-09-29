# Practical 1: Data cleaning and wrangling using R

Practical materials for "Data Science for Geographers".

- `Practical_1_Data_cleaning_and_wrangling_R.ipynb` and `Practical_1_Data_cleaning_and_wrangling_Python.ipynb` are the practical notebooks. They do the same things with the same data; choose whichever language you prefer.
- `TobaccoRegister.csv`, `ScottishPostcodes.csv`, `simd2020.csv`, `urban_rural.csv` and `smoking-at-booking.csv` are the five data files used in the practical. `TobaccoRegister.csv` is delimited with `|`, not commas.
- `Extras/` holds optional Python notebooks, including an introduction to web scraping. They are not covered in class.

Keep the notebook and the data files in the same folder; the notebook reads them from its own working directory. The practical writes `merged_data.csv`, which is the starting point for the later practicals.

All of the data are simulated. The files have the same names, variables and quirks as the real Scottish files used in earlier years, but every datazone, postcode, retailer and value is fictional.

The R notebook needs the `tidyverse` package and an R Jupyter kernel. The Python notebook needs `pandas` (version 2 or later) and a Python 3 Jupyter kernel.
