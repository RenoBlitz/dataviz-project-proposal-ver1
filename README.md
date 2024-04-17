# Data Visualization Project

## Data

The data I propose to visualize for my project is House_Rocket (House_Rocket/data/df_houses_to_buy.csv at main · pedrofratucci/House_Rocket (github.com)). 

 

It is house sale data from a platform called House Rocket. A simple summary is shown below: 

 

id [int]: Unique ID for each home sold 

date [date]: Date of the home sale 

price [float]: Price of each home sold 

bedrooms [categorical]: Number of bedrooms 

bathrooms [categorical]: Number of bathrooms. Where 1 accounts for a complete bathroom, 0.75 accounts a complete bathroom, but no bathtub and 0.5 accounts for a bathroom with a sink and toilet only 

sqft_living [float]: Square footage of the apartments interior living space 

sqft_lot [float]: Square footage of the land space 

floors [categorical]: Number of floors 

waterfront [binary]: A dummy variable for whether the apartment was overlooking the waterfront or not 

view [categorical]: An index from 0 to 4 of how good the view of the property was 

condition [categorical]: An index from 1 to 5 on the condition of the apartment 

grade [categorical]: An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design 

sqft_above [float]: The square footage of the interior housing space that is above ground level 

sqft_basement [float]: The square footage of the interior housing space that is below ground level 

yr_built [int]: The year the house was initially built 

yr_renovated [int]: The year of the house’s last renovation 

zipcode [int]: What zipcode area the house is in 

lat [float]: Latitude 

long [float]: Longitude 

sqft_living15 [float]: The square footage of interior housing living space for the nearest 15 neighbors 

sqft_lot15 [float]: The square footage of the land lots of the nearest 15 neighbors


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 1. What are the relationships between house price and other features?
    /What is most valuable feature of a house?                   ------(price vs. other features)

 2. How do house price change over time?                         ------(price vs. date, yr_built and yr_renovated)

 3. Users may have a price or some requirements about for the houses in their mind. Need a data visualization to help them find some similar houses as references.

## Sketches

![0314_1](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/7c52a5b2-14de-48de-ba39-4602635a6adf)
The first sketch shows features of the data. The content that receives the user's focus will be displayed in a larger size in the plot. The text in the picture can be interacted with, and relevant data content can be quickly located by clicking on it. This data visualization focuses on solving users' problems in quickly finding and locating target data and filtering data through data visualization.

![0314_2](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/ca169f69-3322-4e93-a5a8-02fbe31af179)
The second sketch is a barchart of features in the dataset. The main interaction is hover. When user move their mouse on the bars, it will show the specific data values. There will also be a filter to change the input data for the data visualization. The visualization focuses on solving the problems of comparison questions which is 2nd question of Questions & Tasks section. For example, we can use bar chart to compare the price of houses; what number of bedrooms is popular for consumers.

![0314_3](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/4610e8d7-23d4-4d53-9d30-b22efaeac614)
The 3rd sketch is a map data visualization. The data dots will be shown in the map with different sizes or colors. The interaction will also be hovering and filtering. The data visualization is used for solving the third question about houses' area.

![IMG_0112](https://github.com/RenoBlitz/dataviz-project-proposal-ver2/assets/156150328/e48c6360-b32a-4be6-a4e4-33837b752c44)
This is a new sketch about Parallel Coordinates Plot learned in week 10. It is very useful data visualization which can used for solving task 4. With filters, users can check houses that meet their requirements.

![IMG_0113](https://github.com/RenoBlitz/dataviz-project-proposal-ver2/assets/156150328/86ec0610-bdef-472e-8fac-be16aefdf1d5)
The last sketch is for solving qeustion 2. The line chart can show us the situation of housing price change over years.


## Prototypes

1. This is a bar chart of another house sale dataset. It shows the top 10 houses with largest living area. 
[![image](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/85bdc6ef-4b2a-44ba-99d4-3fa5f1faa13d)](https://vizhub.com/RenoBlitz/dc6d2e5ee64b4797981647165ab0219a)

2. This is a scatter plot of same house sale dataset. It shows the data of bedrooms numbers.
[![image](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/66b43d05-a8ed-4183-b67b-4ce8c3cb0303)](https://vizhub.com/RenoBlitz/863d85988dce4e72a29395566ca8b0e5)

3. Parallel Coordinates Plot learned and built in week 10. It is very helpful interactive data visualization to check houses under filters.
[![image](https://github.com/RenoBlitz/dataviz-project-proposal-ver2/assets/156150328/fd36955c-7716-458d-be27-d6523e40eca0)](https://vizhub.com/RenoBlitz/ba9065894b904333896aa25fd933f48b)

## Scope hope to achieve

 1. Build data visualizations with interactions for solving the questions or tasks.
 2. Improve and optimize the design so that all visualizations have a relatively unified style.
 3. Have relatively practical interactive content for each data visualization.


## Open Questions

Having some troubles making map visualization. Still learning and trying to figure out the right approach.

## Milestones

Week 11: Finish designing visualizations and building them in VizHub.
Week 12: Tweak and optimize visualizations to solve questions and do the tasks.
Week 13: Make sure that all interactive content work correctly.
Week 14: Deal with those last problems and do the final integration.

## Self-Critique

I will evaluate the work I have completed so far based on my Question & Task Section. 

For the first point, the question I raised was the relationship between the price of a house and its various attributes. This question is intended to identify those things that have a greater impact on home prices and are often what home buyers need to pay attention to. To answer this question, my design uses a Bar Chart and a Scatter Plot. My current job has met my requirements to a certain extent. Bar Chart displays Categorical data information better. I think users can use it to perform the comparison work they need. Scatter Plot is not very good at presenting continuous data. The reason may be that the amount of data is too small. But overall, they all have certain effects. I will continue to optimize the interactive content and beautify these visualizations in the future.

The second point is about how house prices change over time. I haven't been able to complete this part of the work, but through studying other people's work I have some ideas and am now working hard to implement them. It should be done soon. 

The last part is about user usage. Since home buyers usually have some needs of their own, to facilitate users to filter out data with reference values according to their own needs, I want to create a data visualization with corresponding interactive functions. When we learned about Parallel Coordinates with Brushing, I found that it fits this need very well.It works very well on my House Sale data. By box-selecting the corresponding data range, I can match the corresponding data for reference. Best of all, I can filter multiple data at the same time. For example, if I want to know the approximate price of a house with 2-3 bedrooms and a living area of 1000-1300 sqare, I can use this kind of data visualization. I will continue to adjust this data visualization later, especially in terms of size and color, so that it can display relevant data more clearly.

## Reprioritization

In the next work, I must complete time-related data visualization content as soon as possible. Then I need to optimize the design of my interactive content and implement them. At the end of this, I will confirm how to beautify the visualizations based on how they look.

## Updates so far
1. Removed the map visualization. To solve the questions and do the tasks, map visualization cannot provide enough help even it provides some spatial information.

2. Added a new line chart related to Question 2 (Price over time). The time is based on the fearture 'yr_built'. It is helpful on making a simple prediction of future house prices. This visualization will be shown in Prototypes section.

3. For all visualizations, black will be used as the main background color and theme color. The colors of the remaining details will be designed based on the visualization. These will be updated soon.
