# TSAF-Ex-1-Plot-a-Time-Series-Data

## AIM:
To develop a Python program to plot and visualize time series data such as population,
commodity market price, or temperature.

## ALGORITHM:
1. Start the program.
2. Import Pandas and Matplotlib libraries.
3. Create the time-series data using Year or Month and its corresponding values.
4. Create a DataFrame using the time and value data.
5. Display the DataFrame.
6. Plot the time-series data using a line graph.
7. Add a suitable title and labels for the X-axis and Y-axis.
8. Display the graph.
9. Observe the graph and identify the trend as increasing, decreasing, approximately
constant, or seasonal.
10. Stop the program.

## PROGRAM:

### Monthly Commodity Price — 12 Months
```
import pandas as pd
import matplotlib.pyplot as plt
month = ["Jan", "Feb", "Mar", "Apr", "May", "Jun",
 "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"]
price = [4200, 4350, 4280, 4500, 4650, 4800,
 4700, 4900, 5000, 5150, 5050, 5300]
data = pd.DataFrame({
 "Month": month,
 "Price": price
})
print(data)
plt.plot(data["Month"], data["Price"])
plt.title("Monthly Commodity Market Price")
plt.xlabel("Month")
plt.ylabel("Price")
plt.show()
```

## OUTPUT:
<img width="803" height="712" alt="image" src="https://github.com/user-attachments/assets/56ca5b6a-db6f-4bfb-b700-aaff539954c4" />

## RESULT:
Thus, the given time-series data were successfully stored using Pandas and visualized using
Matplotlib. The trends in population, temperature, and commodity price were identified from
the plotted graphs
