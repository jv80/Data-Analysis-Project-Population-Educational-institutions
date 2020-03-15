# Population/Schools(Data Analysis Project)
Population/Schools is a personal work that shows different phases of data analysis and data processing with real datasets.
The goal of this project is to show examples of input/output data, data cleaning, visualization and data analysis.

The final product of this project is a map of Vancouver with the information of the schools and population(between 5-19 years old) per local area. 
## Datasets
Three different datasets were used in this project:
1. [Dataset of Vancouver census 2016 using the City's 22 local planning areas from City of Vancouver open data website](https://data.vancouver.ca/datacatalogue/censusLocalAreaProfiles2016.htm "City of Vancouver open data portal")

2. [Dataset of schools in Vancouver (name, category, coordenates of ubication) from City of Vancouver open data website](https://opendata.vancouver.ca/explore/dataset/schools/information/?location=12,49.24716,-123.11523&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20ifV0sInhBeGlzIjoiZ2VvX2xvY2FsX2FyZWEiLCJtYXhwb2ludHMiOjUwLCJzb3J0IjoiIiwic2VyaWVzQnJlYWtkb3duIjoic2Nob29sX2NhdGVnb3J5IiwiY29uZmlnIjp7ImRhdGFzZXQiOiJzY2hvb2xzIiwib3B0aW9ucyI6e319fV0sInRpbWVzY2FsZSI6IiIsImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9 "City of Vancouver open data portal")

3. [Map of 22 local planning areas of Vancouver from City of Vancouver open data website](https://data.vancouver.ca/datacatalogue/localAreaBoundary.htm "City of Vancouver open data portal")
## Specific Objetives
1. Data wrangling of Census 2016 and school datasets.
2. Create two new processed datasets for female and male between 5 and 19 years old from Census 2016.
3. Data wringling of Schools dataset
4. Generate of the map of 22 local planning areas of Vancouver.
5. Visualize of the all data in a map of Vancouver.
## Workflows 
Three different workflows were used in this project to generate a final map of the 22 local planning areas of the City of Vancouver with a the localization of the schools, amount of people between 0 and 17 years old.
### Workflow of data wringling of Census 2016 dataset
![alt text](https://github.com/jv80/Population-Schools/blob/master/Diagrams/MainWorkflow.png)

| Input File | Work File | Output File|
|--------------------------------:|--------------------------------:|--------------------------------:|
|[CensusLocalAreaProfiles2016.csv](https://github.com/jv80/Population-Schools/blob/master/Data/CensusLocalAreaProfiles2016.csv)|[ProcessingCensus2016.ipynb](https://github.com/jv80/Population-Schools/blob/master/Work%20Files/ProcessingCensus2016.ipynb)|[CensusLocalAreaProfiles2016_cleaned.csv](https://github.com/jv80/Population-Schools/blob/master/Data/CensusLocalAreaProfiles2016_cleaned.csv)
[CensusLocalAreaProfiles2016_cleaned.csv](https://github.com/jv80/Population-Schools/blob/master/Data/CensusLocalAreaProfiles2016.csv)|[ProcessingFemalePopulation2016.ipynb](https://github.com/jv80/Population-Schools/blob/master/Work%20Files/ProcessingFemalePopulation2016.ipynb)|[FemalePopulationDataset_cleaned.csv](https://github.com/jv80/Population-Schools/blob/master/Data/FemalePopulationDataset_cleaned.csv)
[CensusLocalAreaProfiles2016_cleaned.csv](https://github.com/jv80/Population-Schools/blob/master/Data/CensusLocalAreaProfiles2016.csv)|[ProcessingMalePopulation2016.ipynb](https://github.com/jv80/Population-Schools/blob/master/Work%20Files/ProcessingMalePopulation2016.ipynb)|[MalePopulationDataset_cleaned.csv](https://github.com/jv80/Population-Schools/blob/master/Data/MalePopulationDataset_cleaned.csv)

### Workflow of data wringling of Schools dataset
![alt text](https://github.com/jv80/Population-Schools/blob/master/Diagrams/Schoolsv.PNG)

| Input/Output File | Work File |
|--------------------------------:|--------------------------------:|
[schools.csv](https://github.com/jv80/Population-Schools/blob/master/Data/schools.csv)|[ProcessingSchools.ipynb](https://github.com/jv80/Population-Schools/blob/master/Work%20Files/ProcessingSchools.ipynb)

### Visualization of the data (Final Map)

https://jhyvaz.maps.arcgis.com/home/webmap/viewer.html?webmap=4db2cb1e776b48fea037611e29dc3482





