## Experiment Documentation

### 1. Aim
To perform data visualization and visual encoding using Python libraries to analyze trends, distributions, and relationships within a dataset.

### 2. Logic
The logic revolves around **Visual Encoding**, which is the process of mapping data attributes (like marks or days) to visual properties (like height, position, or color).
* **Temporal trends** are mapped to line positions.
* **Categorical comparisons** are mapped to bar heights.
* **Frequency distributions** are mapped to histogram bins.
* **Correlations** are mapped to spatial points in a scatter plot.

### 3. Theory
Data visualization transforms raw numbers into a graphical context. 
* **Matplotlib:** A low-level library providing full control over every element of a figure.
* **Seaborn:** Built on top of Matplotlib, it provides a high-level interface for drawing attractive and informative statistical graphics.
* **Line Charts:** Best for showing changes over time.
* **Bar Charts:** Ideal for comparing discrete quantities across different categories.
* **Histograms:** Used to represent the distribution of a continuous variable.
* **Scatter Plots:** Essential for identifying the relationship or correlation between two numerical variables.

### 4. Algorithm
1.  **Import** necessary libraries (`matplotlib`, `pandas`, `seaborn`, `numpy`).
2.  **Initialize** data using a Python dictionary and convert it into a DataFrame for structured manipulation.
3.  **Define Coordinates:** Select columns from the DataFrame to act as X and Y axes.
4.  **Apply Visual Encoding:** Use specific functions (`plt.plot`, `plt.bar`, `plt.hist`, `plt.scatter`) to generate the plot.
5.  **Customize:** Add titles, labels, legends, and markers to enhance readability.
6.  **Render:** Call the display function to output the visualization.

### 5. Conclusion
Through this experiment, it is concluded that visual encoding effectively highlights patterns that are difficult to see in raw tabular data, such as the direct correlation between study hours and marks.

---

## One-Liner Explanations

### Libraries
* `import matplotlib.pyplot as plt`: Imports the primary module for creating static, interactive, and animated visualizations in Python.
* `import pandas as pd`: Provides high-performance data structures like DataFrames for data manipulation and analysis.
* `import seaborn as sns`: A statistical data visualization library that provides a high-level interface for drawing attractive graphics.
* `import numpy as np`: Supports large, multi-dimensional arrays and matrices, along with mathematical functions to operate on them.

### Commands
* `pd.DataFrame(data)`: Converts a dictionary into a structured 2D table format for easier data handling.
* `plt.plot()`: Draws a line chart to show trends between two sets of data.
* `plt.bar()`: Creates vertical bars where the height represents the value of a category.
* `plt.hist()`: Groups data into bins to show the frequency distribution of a single variable.
* `plt.scatter()`: Places individual points on a graph to observe the relationship between two variables.
* `plt.title()` / `plt.xlabel()` / `plt.ylabel()`: Adds descriptive text to the top and axes of the plot.
* `plt.legend()`: Displays a small box identifying the data series represented by different colors or markers.
* `plt.grid()`: Adds background lines to help the eye trace values across the plot.
* `plt.axvline()`: Draws a vertical line at a specific point on the x-axis, often used to show a mean or threshold.
* `plt.xticks()`: Sets the tick locations and labels on the x-axis for better formatting.
* `plt.show()`: Displays all currently active figure objects on the screen.
