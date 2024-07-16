![SVG](https://github.com/abdosoltan349/Numeric-Data/blob/main/digram.svg)
# Numeric Data
Selecting appropriate types of plots to visualize numeric data based on the number and nature of variables. It is divided into sections based on whether the data involves one, two, or more numeric variables, and whether these variables are ordered or not. Here’s a detailed breakdown:


### 1. One Numeric Variable
- *Histogram*: This is a bar plot that shows the frequency distribution of a single numeric variable. It’s useful for understanding the shape of the data distribution.
- *Density Plot*: This plot represents the distribution of a numeric variable as a smooth curve, providing an alternative to histograms with a more continuous representation.

### 2. Two Numeric Variables
#### Ordered
- *Connected Scatter Plot*: Points are plotted on a graph and connected by lines in the order they appear. This is useful for time series data or ordered observations.
- *Area Plot*: This plot shows the cumulative total of data over time or another continuous variable, filling the area under the line.
- *Line Plot*: Displays data points connected by straight lines to show trends over time or ordered categories.

#### Not Ordered
- *Few Points*:
  - *Box Plot*: Summarizes data using five statistics (minimum, first quartile, median, third quartile, and maximum). Useful for identifying outliers and comparing distributions.
  - *Histogram*: Shows the frequency distribution of the data.
  - *Scatter Plot*: Plots individual data points on a two-dimensional axis to show relationships between the variables.

- *Many Points*:
  - *Box Plot*: Similar to above, but useful even with larger datasets.
  - *Violin Plot*: Combines a box plot and density plot, providing more detail about the distribution.
  - *Density Plot*: Visualizes the distribution with a smooth curve.
  - *Scatter with Marginal Plot*: A scatter plot with additional marginal plots to show the distribution of each variable separately.
  - *2D Density Plot*: Similar to a scatter plot but with color shading to indicate areas of higher point density.

### 3. Three Numeric Variables
#### Not Ordered
- *Box Plot*: As above, for summarizing distributions.
- *Violin Plot*: As above, providing detailed distributional information.
- *Bubble Plot*: A scatter plot where the size of each point (bubble) represents a third variable.
- *3D Scatter or Surface Plot*: Extends scatter plots into three dimensions, allowing visualization of three variables simultaneously.

### 4. Several Numeric Variables
#### Ordered
- *Line Plot*: Shows trends over an ordered variable, useful for comparing multiple variables.
- *Stacked Plot*: Displays cumulative totals across ordered categories.
- *Area (SM)*: Shows the cumulative total in a shaded area, similar to an area plot but often used for multiple variables.

#### Not Ordered
- *Ridge Line*: Displays the distributions of multiple variables in a stacked format, often used to compare distributions.
- *PCA (Principal Component Analysis)*: Reduces the dimensionality of data and visualizes the principal components.
- *Correlogram*: Visualizes the correlation matrix, showing relationships between variables.
- *Heatmap*: Represents values in a matrix form, often used for showing correlations or other matrix-like data.
- *Dendrogram*: Shows hierarchical clustering of variables, useful in hierarchical clustering analysis.

### Summary
The flowchart helps in determining the most suitable type of plot based on:
- The number of numeric variables (one, two, or more).
- Whether the variables are ordered or not.
- The quantity of data points (few or many).

By following the paths in the flowchart, you can select the most effective visualization method to represent your numeric data accurately and informatively.
