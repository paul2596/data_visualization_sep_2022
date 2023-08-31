# Visualization Dashboard to Analyze the Spread of a Disease from Simulation Data (Project Timeline:Sep 2022-Oct 2023)

### Objectives
- To study the uncertainty and impact of the disease. 
- Build dashboards with appropriate interactions that help convey the data story through the patterns identified.
- Help in deciding the deployment of limited tactical resources (medics and medical supplies) based on the visualization.

### Methodology
For the visualization of the coordinates, map plot is used which shows the infected areas and spread of the disease. 
Stacked area chart is used in the dashboard to show the average infected in each population size for different simulation intensities.

#### Color
The visualization shows the areas in need of aid through a colour gradient from a shade of yellow indicating least infected to a darker shade of magenta to indicate the increase in need of aid.
#### Color Blind Friendly Palette
For the map a shade of yellow to darker shade of magenta is used. Similarly, for the plot of average infected colours are used from IBM’s colour-blind safe palette. Colour gradient used for the map points for visualizing infected values can be distinguished even on a grey scale.

### Custom Filter
The spread of the disease from the origin where it starts to propagate is studied by using a custom radial filter. 
This filter was created by evaluating the distance between different coordinates from the origin using Haversines Formula, which gives us an insight on the radial spread of the disease.

### Decision Making Based on the Visualization
- The output visuals from the interactive dashboard can be controlled by adjusting different filters provided.
- By adjusting the radial distance from origin using the distance filter, the deployment of medics can be lined up near spots which require the most attention.
- By adjusting the standard deviation and covariance filter the regions can be narrowed down by severity of spread.
- Further, the dashboard can be filtered based on simulation intensity by making use of the stacked area chart. It can also be noted that the number of infected people readuce as the population size increases.

![image](https://github.com/paul2596/data_viz/assets/71576923/9d3933f8-7277-4eb3-831f-1ee7cf6a17b7)

### Final Dashboard
https://github.com/paul2596/data_viz/assets/71576923/6590370c-e160-4c3e-b561-7b8b4d2a5332

