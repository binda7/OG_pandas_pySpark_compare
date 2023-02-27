# Analysis of aspects of athletes participating in the Summer Olympic Games over the years

## In addition to the analysis itself, it was decided to compare two popular Python libraries: "Pandas" and "PySpark".

## Analyzed data

During the analysis, it was decided to analyze the age of the athletes (who was the oldest and youngest participant), gender, the number of athletes for each Olympic Games. In addition, it was analyzed which countries send the most of their athletes. The number of medals already won by the athletes.. As an addition, an analysis of athletes coming from Poland was done separately.

## Pandas vs PySpark comparison

For both libraries, exactly the same set of queries was performed. First, a csv file taken from the database was read. Then carried out by generating new queries, a measurement of the time it took to complete the task was made. Both libraries showed similar execution time for each task. The problem arose when generating graphs. In the case of Pandas, the situation was straightforward, while using PySpark's DataFrame, one of the available options was to convert the DataFrame to a Pandas Dataframe, which generated another command. However, note that PySpark is geared for large databases and is ideal for this. For small amounts of data to be analyzed, Pandas is a better choice.



### PC:
- Intel Core i5-10300H
- NVIDIA GeForce GTX 1650 Ti
- 16 GB RAM

### Data Base:
    Olympics 124 years Dataset(till 2020)

Kaggle: https://www.kaggle.com/datasets/nitishsharma01/olympics-124-years-datasettill-2020?select=regions.csv


### SOON WINTER OLIMPIC GAMES ANALITYCS WITH POLARS
