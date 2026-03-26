# Matplotlib Tutorial for Open Data Week NYC 2026

live notebook: https://story645.github.io/odwny2026

### Get started
live notebook: https://story645.github.io/odwny2026


Then go to [notebook 1: static visualizations]()

### Data acknowledgement 
The data is included here from ease of use, but it is obtained from https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2020-to-Present/erm2-nwe9/about_data 

### Schedule
This schedule/dataset is subject to change, but the rough plan is:

start up: [10 minutes]
- verify install/open codespaces/get settled
- What most intrigues you at https://matplotlib.org/devdocs/gallery/index.html
 - add link to shared notes: https://hackmd.io/@story645/pynyc23 

Introduction [20 minutes]
- figure→axes→elements diagram
-Example: plot a heatmap/matshow of penguins
- Together: scatter plot of bill_length_mm vs bill_depth color by species and vary by size
Exercise: (I'll show the finished figure)
- subplot mosaic -> add an empty axes
- add a bar chart showing the mean of each variable
- add labels

Animation[25 minutes]
- example: highlight one penguin on heatmap, scatter, and bar chart
- example: movie highlighting each penguin on the heatmap
- add in highlighting on the scatter
- exercise: [10 minute]
linked movie highlighting each penguin on bar chart

Interactivity: [30 minutes]
- break scatter out by species and show out of the box linked zoom
- use jupyter widgets to slide the animation
- custom interactivity to select the penguin on the heatmap and update the bar chart
- exercise[15 minutes]
- select the penguin in the scatter plot and update the bar chart

Wrap up: [5 minutes]
- overview of resources for how to go further
