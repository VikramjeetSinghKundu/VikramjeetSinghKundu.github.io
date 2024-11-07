# HW6.1: Visualization of Building Inventory Data

## Plot 1: Distribution of Buildings by County

This bar chart visualizes the number of government buildings across different counties in Illinois. The goal is to highlight which counties have a higher concentration of government-owned buildings, allowing us to easily spot the distribution pattern across the state. I used a blue gradient color scheme to encode the building count, with darker shades representing counties with more buildings. This color scheme helps quickly identify counties with higher numbers of government properties.

To prepare the data for this visualization, I grouped the dataset by the “County” column and calculated the count of buildings for each county. This aggregated data allowed us to create a simplified view that focuses on building concentration rather than individual building details. We chose a bar chart for its simplicity and effectiveness in showing count-based distributions across categorical values like county names. No transformations were done on the building count values, as they were aggregated directly from the dataset.

[View Plot 1](https://VikramjeetSinghKundu.github.io/plot1.html)

## Plot 2: Building Area Analysis by Year Constructed

This scatter plot examines the square footage of buildings based on their construction year, allowing us to explore trends in building sizes over time. Each point represents a building, with the x-axis showing the year it was constructed and the y-axis indicating its square footage. The plot also features an interactive time range filter, which lets users select different time periods to examine trends within specific years. This interactivity makes it easier to observe how building sizes may have evolved over time.

For this plot, I used the “Year Constructed” column for the x-axis and “Square Footage” for the y-axis. To make it more engaging, I added tooltips that display the building’s location name, year constructed and square footage when hovering over each point. This interaction provides additional context without cluttering the main visualization. No additional transformations were necessary beyond filtering the data for non-null square footage and construction year values which ensures that only relevant data is displayed. 

The entire plot is not fitting the screen so a left-right scrolling is required to see the entire visualization.

[View Plot 2](https://VikramjeetSinghKundu.github.io/plot2.html)

## Interactivity Discussion

The interactivity in Plot 2 is designed to enhance clarity and exploration. By allowing users to select a specific time range, they can focus on different construction periods, which helps them spot any patterns in building size trends across time. This feature adds an exploratory dimension to the visualization, making it more engaging and informative.

## Links
- [The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv)
- [The Analysis](https://github.com/VikramjeetSinghKundu/VikramjeetSinghKundu.github.io/blob/main/Homework%206-DataViz-Analysis-Vikramjeet%20Singh%20Kundu.ipynb)
