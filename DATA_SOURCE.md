# Data source

Cortez, P. (2008). **Student Performance**. UCI Machine Learning Repository.
[Dataset citation](https://doi.org/10.24432/C5TG7T).

- [Dataset page](https://archive.ics.uci.edu/dataset/320/student+performance)
- [Official download](https://archive.ics.uci.edu/static/public/320/student+performance.zip)

Only `student-mat.csv` is used. It contains 395 mathematics records and 33 columns.
The accompanying `student.txt` explains the original variables. Both raw files are unchanged.
They were checked against the official download on 12 November 2026.

## Fields used

| Field | Meaning |
| --- | --- |
| studytime | Weekly category: 1 = <2 hours; 2 = 2-5; 3 = 5-10; 4 = >10 |
| absences | Number of school absences; documented range 0-93 |
| G1 | First-period grade, 0-20 |
| G2 | Second-period grade, 0-20 |
| G3 | Final-year grade issued at the third period, 0-20 |
| school | School code: GP or MS |
| age | Age in years; documented range 15-22; checked but not analysed |

The file does not explain why some final grades are zero. It also does not provide
the total possible attendance exposure needed for an attendance rate.

## Licence

UCI lists the data under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).
Credit belongs to the dataset creator. The tables and charts are derived from the source data;
the raw CSV and variable notes have not been edited. No endorsement by the source is implied.

## Method help

- [pandas introduction](https://pandas.pydata.org/pandas-docs/version/2.2/getting_started/intro_tutorials/index.html)
- [pandas correlation](https://pandas.pydata.org/pandas-docs/version/2.2/reference/api/pandas.Series.corr.html)
- [Seaborn box plots](https://seaborn.pydata.org/generated/seaborn.boxplot.html)
