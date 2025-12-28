# Smart-Street-Flood-Water-Level-Analysis
Analyze water level data →  early flood warnings. Line plots, threshold analysis.
Project Title: Smart Street Flood Water Level Analysis
Project Overview

This project analyzes flood water levels on streets using Python to help detect flood risk early. By monitoring water levels at different times, the system can give warnings before a dangerous flood situation occurs.

Objective of the Project

To collect and analyze water level data

To identify warning and danger levels

To visualize water level changes over time

To help in early flood warning and disaster management

Tools & Technologies Used

Python – Programming language

Pandas – For data storage and analysis

Matplotlib – For graphical visualization

VS Code – Code editor

Data Description

The dataset contains:

Time – Hour-wise reading (08:00, 09:00, etc.)

Water_Level_cm – Water level measured in centimeters

Example:

Time     Water_Level_cm
08:00    30
09:00    45
10:00    60
11:00    75
12:00    110

Working of the Project

Water level data is stored using a Pandas DataFrame

The data is analyzed to check:

Warning Level (e.g., 70 cm)

Danger Level (e.g., 100 cm)

A line graph is plotted:

X-axis → Time

Y-axis → Water level (cm)

Horizontal lines show warning and danger thresholds

If water exceeds limits, it indicates possible flooding

Output

A visual graph showing rising water levels

Easy identification of safe, warning, and danger zones

Helps authorities take early action

Applications

Smart city flood monitoring

Disaster management systems

Urban drainage planning

Early flood alert systems

Conclusion

This project demonstrates how data analysis and visualization can be used for real-life safety applications. It shows that simple Python tools can play an important role in preventing flood damage and saving lives.
