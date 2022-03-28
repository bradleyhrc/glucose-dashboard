# glucose-dashboard
## Interactive Visualization Dashboard of Glucose Data Using Python

This repository contains the code and elements for my project which aims to display an interactive dashboard of my blood glucose data. As a Type 1 Diabetic, I wear a continuous glucose monitor in order to help calculate my insulin dosage whenever I eat and through out the day. The target range for my blood glucose is anywhere between 4.0-8.0 mmol/L. While I monitor myself, my family and loved ones do not have access to this data. This portfolio project aims to share the data in a simple and consumable form (interactive dashboard report) with my family.

Currently, I've included the first draft of the interactive dashboard. It includes a plot of my blood glucose through out the day, as well as an interactive table of values (blood glucose), and lastly a bar plot which shows the amount of time I'm within target, below target, or above target. 

Interactivity includes picking which dates to display or measure from, as well as navigating the graphs. I've added a red region in my plots to indicate critical 'low' areas, where it is possible to feel the effects of low blood sugar (consequences range from shivering, fainting, etc.). Additionally, the green region on the plot indicates the target interval for my blood glucose.

To serve the dashboard locally please download the main 'bradley_glucose_dashboard.ipynb' file and use the command:
```
panel serve bradley_glucose_dashboard.ipynb
```
This is still a prototype, so key features I aim to add include displaying it on my personal website (no need to download), as well as automating the pre-processing of the dataset. Please note that currently the dashboard displays data up to June 5, 2021 as I am using an old dataset. I will update this one shortly.
