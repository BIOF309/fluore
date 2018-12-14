% Analysis of Membrane disruption by a toxin
% John Jimah
% 2018.12.11

# Testing membrane disruption by a toxin
Analyzed data
![AddAve](images/disruption.png)

# Example data of Toxin lysing a membrane
![AddAve](images/toxin.png)

# Example of Unprocessed data
![AddAve](data.png)

# Scatter plot code
![AddAve](scatter.png)

also numpy.polyfit
import pandas as p
import numpy as n
data = p.read_csv("data1.csv", usecols=[1]) # I want the first col
data1 = p.read_csv("data2.csv", usecols=[3]) # I want the 3rd col
x = data
y = data1

# Next step: 
Fitting and replication

# Acknowledgements
BioF309 class and teachers
