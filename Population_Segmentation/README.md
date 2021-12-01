# Population Segmentation with US Census Dataset
Population segmentation aims to find natural groupings in population data that reveal some feature-level similarities between different regions in the US.

## Data Source
using [data](https://data.census.gov/cedsci/) collected by the [US Census](https://en.wikipedia.org/wiki/United_States_Census), which aims to count the US population, recording demographic traits about labor, age, population, and so on, for each county in the US.

## Algorithms Used
* principal component analysis (PCA) to reduce the dimensionality of the original census data

* k-means clustering to assign each US county to a particular cluster based on where a county lies in component space which tell you which US counties are most similar and what demographic traits define that similarity.