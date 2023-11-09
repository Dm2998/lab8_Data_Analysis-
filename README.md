# lab8_Data_Analysis-
Data Analisis 3Year
```
Seaborn Exercises
Python

```

The Data
We will be working with a famous titanic data set for these exercises. Later on in the Machine Learning section of the course, we will revisit this data, and use it to predict survival rates of passengers. For now, we'll just focus on the visualization of the data with seaborn:

import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
sns.set_style('whitegrid')
titanic = sns.load_dataset('titanic')
titanic.head()

Exercises
Recreate the plots below using the titanic dataframe. There are very few hints since most of the plots can be done with just one or two lines of code and a hint would basically give away the solution. Keep careful attention to the x and y labels for hints.
```
 Distribution Plots; allow to visualise a distribution of data set. 

![image](https://github.com/Dm2998/lab8_Data_Analysis-/assets/114578666/1f788dd8-6863-4c4d-8891-71c9ad45c129)



Distplot: The distplot shows the distribution of a univariate set of observations.


![image](https://github.com/Dm2998/lab8_Data_Analysis-/assets/114578666/3bf258c6-3360-4da6-819c-ef9993df5de3)

```




