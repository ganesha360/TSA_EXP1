# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

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












# OUTPUT:






# RESULT:
Thus we have created the python code for plotting the time series of given data.
