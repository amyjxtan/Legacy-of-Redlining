# Legacy of Redlining

## Project Overview

This project uses data from the 1930s when the practice of redlining initially began and compares it to 2020 census demographic data to examine segregation in the present. It demonstrates how, almost 90 years later, there is segregation based on the Home Owner's Loan Corporation grade assigned to it back in the 1930s on the state, division, and regional levels. 

**Note:** this project is best viewed when the notebook is downloaded and run, so that maps fully display and are interactive.

## Installation and Setup
### Codes and Resources Used

- **Editor Used:**  Anaconda
- **Python Version:** Python 3.11.5

### Python Packages Used

- **Data Manipulation:** `pandas`
- **Data Visualization:** `matplotlib`, `pyplot`, `seaborn`, `plotly (express)`
## Data
### Source Data
The data used in this project is `metro-grades.csv` from [FiveThirtyEight](https://github.com/fivethirtyeight/data/tree/master/redlining), saved into the variable `redlining` in the notebook.
## Results and evaluation
The impacts of redlining are still felt today - previously redlined areas are still segregated the way they were intended to be back in the 1930s. My hypothesis (areas with histories of slavery would be more segregated) was disproven - the Northern region was actually slightly more segregated than the Southern region. A potential explanation for this would be laws enacted in response to the Great Migration from the 1910s-1970s. During the Great Migration, approximately six million Black people moved from the American South to escape racial violence, pursue economic and educational opportunities, and obtain freedom from Jim Crow Laws. However, they were met with resitance, and faced injustices and difficulties after migrating. Redlining laws in part, emerged as a result of the influx of Black folks in predominately White areas, leading both the North and South to most significantly still show the effects of this.

## Future work
- Use GIS software to produce better and more accurate maps that would better reflect a metro-area that isn't forced into a particular state boundary.
- Pair this demographic data with HOLC grades with other issues such as food insecurity, social vulnerability, life expectancy, etc. 
- Map across time using census data from other years to examine how segregation patterns have changed across time.

## License
[MIT License](https://opensource.org/license/mit/)
