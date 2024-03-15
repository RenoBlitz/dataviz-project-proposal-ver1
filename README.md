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

 * Does “view” have a significant effect on “price”? 
 * What size is most popular? The number of bedrooms and bathrooms?
 * In which areas are houses more popular? How much impact does location have on price?
 * Provide fast filter and references for user to help them make a judgment on houses’ values.

## Sketches

![0314_1](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/7c52a5b2-14de-48de-ba39-4602635a6adf)
The first sketch shows features of the data. The content that receives the user's focus will be displayed in a larger size in the plot. The text in the picture can be interacted with, and relevant data content can be quickly located by clicking on it. This data visualization focuses on solving users' problems in quickly finding and locating target data and filtering data through data visualization.

![0314_2](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/ca169f69-3322-4e93-a5a8-02fbe31af179)
The second sketch is a barchart of features in the dataset. The main interaction is hover. When user move their mouse on the bars, it will show the specific data values. There will also be a filter to change the input data for the data visualization. The visualization focuses on solving the problems of comparison questions which is 2nd question of Questions & Tasks section. For example, we can use bar chart to compare the price of houses; what number of bedrooms is popular for consumers.

![0314_3](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/4610e8d7-23d4-4d53-9d30-b22efaeac614)
The last sketch is a map data visualization. The data dots will be shown in the map with different sizes or colors. The interaction will also be hovering and filtering. The data visualization is used for solving the third question about houses' area.


## Prototypes

1. This is a bar chart of another house sale dataset. It shows the top 10 houses with largest living area. 
[![image](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/85bdc6ef-4b2a-44ba-99d4-3fa5f1faa13d)](https://vizhub.com/RenoBlitz/dc6d2e5ee64b4797981647165ab0219a)

2. This is a scatter plot of same house sale dataset. It shows the data of bedrooms numbers.
[![image](https://github.com/RenoBlitz/dataviz-project-proposal-ver1/assets/156150328/66b43d05-a8ed-4183-b67b-4ce8c3cb0303)](https://vizhub.com/RenoBlitz/863d85988dce4e72a29395566ca8b0e5)


## Open Questions

(describe any fear, uncertainty, or doubt you’re having about the feasibility of implementing the sketched system. For example, “I’m not sure where to get the geographic shapes to build a map from this data” or “I don’t know how to resolve the codes to meaningful names” … Feel free to delete this section if you’re confident.)

## Milestones

(for each week, estimate what would be accomplised)
