# Data Visualisation with Matplotlib

Here we see how to grab some raw data and create some interesting charts using Pandas and Matplotlib.

<ul>
  <li>Used .groupby() to explore the number of posts and entries per programming language</li>
  <li>Converted strings to Datetime objects with to_datetime() for easier plotting</li>
  <li>Reshaped our DataFrame by converting categories to columns using .pivot()</li>
  <li>Used .count() and isna().values.any() to look for NaN values in our DataFrame, which we then replaced using .fillna()</li>
  <li>Created (multiple) line charts using .plot() with a for-loop</li>
  <li>Styled our charts by changing the size, the labels, and the upper and lower bounds of our axis.</li>
  <li>Added a legend to tell apart which line is which by colour</li>
  <li>Smoothed out our time-series observations with .rolling().mean() and plotted them to better identify trends over time.</li>
</ul>
