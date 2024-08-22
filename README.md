# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 22/08/2024

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```python
import pandas as pd

# Load the dataset
file_path = '/content/survey lung cancer.csv'
data = pd.read_csv(file_path)

# Display the first few rows to inspect the data
print(data.head())

# Display column names to understand the structure
print(data.columns)

import matplotlib.pyplot as plt

# Plotting the time series
plt.figure(figsize=(12, 6))
plt.plot(data.index, data['AGE'], label='AGE', color='blue')  # Adjust 'Open' to your actual column name
plt.title('Survey Lung Cancer - Lung Cancer Over Time')
plt.xlabel('NUMBER OF PATIENTS')
plt.ylabel('AGE OF PATIENTS')
plt.legend()
plt.grid(True)
plt.show()


```










# OUTPUT:






# RESULT:
Thus we have created the python code for plotting the time series of given data.
