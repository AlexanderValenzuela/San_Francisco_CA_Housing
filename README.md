# Project Title - San Francisco Housing

## Introduction
The primary goal of this project is to create a Proptech application that would offer potential customers a one click service for buying investment rental properties.   As an anlayst, my team and I will utilize data visualization, aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities. 


## Technologies
**Python Libraries**

`python 3.9.12`<br>
`pandas 1.4.2`<br>
`Path`<br>
`hvplot 0.73`



## Installation Guide

[Install anaconda](https://www.anaconda.com/download/)

To clone and run this application, you'll need Git installed on your computer.
From your command line:
```
#Create a new conda environment
conda create -n dev python=3.7 anaconda

#Activate the new environment with the following command
conda activate dev

# Install dependencies in conda environment
pip install jupyter lab
conda install -c pyviz hvplot geoviews

# Clone this repository
git clone https://github.com/AlexanderValenzuela/San_Francisco_Housing

# Activate conda environment
conda activate dev

# In the conda environment, run Jupyter Lab
jupyter lab 

# Browse to the San_Francisco_Housing directory and launch `san_francisco_housing.ipynb`
```
---

## Usage
Use the `san_francisco_housing.ipynb` notebook to visualize and analyze the real-estate data.<br>

In the outline below, we will use numerical and visual aggregation for calculations and create visualizations using hvPlot and GeoViews. In addition, we will use the `read_csv` function to read the sfo_neighborhoods_census_data.csv file from the Resources folder into the notebook and create the DataFrame that will be used in the analysis.<br>

> 1. Calculate and Plot the Housing Units per Year<br>
Use numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart.
![Screenshot 2023-05-01 at 9 00 27 PM](https://user-images.githubusercontent.com/111409358/235576602-e44382ee-b27b-45c2-9a83-2dde3510584e.png)

> 2. Calcuate and Plot the Average Sales Prices per Square Foot<br>
Use numerical and visual aggregation to calculate the average prices per square foot, and then visualize the results as a bar chart. 
![Screenshot 2023-05-01 at 9 02 19 PM](https://user-images.githubusercontent.com/111409358/235576870-f37e3f67-3cc4-4caa-a7b0-0f22626c78d5.png)

> 3. Compare the Average Sales Prices by Neighborhood<br>
Use interactive visualizations and widgets to explore the average sale price per square foot by neighborhood. 
![Screenshot 2023-05-01 at 9 05 16 PM](https://user-images.githubusercontent.com/111409358/235577063-1e88b873-05af-48d5-a165-84be65bd843a.png)

> 4. Build an Interactive Neighborhood Map<br>
Explore the geospatial relationships in the data by using interactive visualizations with hvPlot and GeoViews. 
![Screenshot 2023-05-01 at 9 06 14 PM](https://user-images.githubusercontent.com/111409358/235577145-b1d93d89-9ac4-4b4c-a2b1-ccba471d4ab9.png)

> 5. Composing the Data Story<br>
Based on the visualizations created, answer the following questions:<br>
> - How does the trend in rental income growth compare to the trend in sales prices? Does this same trend hold true for all the neighborhoods across San Francisco?<br>
> - What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? Do neighborhoods exist that you would suggest for investment, and why?


## Contributors
- Data Team
- Fintech Team
- Development Team
- Alexander Valenzuela<br>
[LinkedIn Profile](<https://www.linkedin.com/in/alex-valenzuela-97826842/>)


## License
Licensed under the MIT License



