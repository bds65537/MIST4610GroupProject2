# Team 6 MIST 4610 Group Project 2





## Team Name:
 21484 Group 6

## Team Members:
Erika Evan @erikaevan

William Malonda @WMalonda

Luke Michaelis @lukemichaelis

Brendan Sheehan @bds65537

Jason Vu @jdv14934
## Description of Data Set:

The dataset our team selected comes from data.gov which is a US government website with a large catalog of datasets. Our dataset is the 2024 Fuel Economy Guide for the most common cars, SUVs, and trucks manufactured in 2024 driven in the United States, which includes domestic and foreign auto manufacturers. The database includes a wide variety of information for each manufacturer, division, and carline, which are all examples of string type data. Also, there are quantitative engine specifics like number of cylinders and intake/exhaust valves, numerical data. Additionally, the dataset lists city, highway, and combined fuel economy for each vehicle as advertised by the manufacturer, as well as drivetrain type and annual fuel cost. Finally, there is a column that lists the date the car was released, which is a date datatype. As a whole, the dataset offers comparable information on the different car manufacturers and how each has different numbers of vehicles with different specs, performance, and costs. 

## Question 1: How does the number of cylinders in the engine affect the fuel economy across different drivetrain types?

Importance of this question:
This question explores the relationship between engine specifications (specifically, the number of cylinders) and fuel economy, considering different drivetrain types such as Front-wheel Drive (FWD), Rear-wheel Drive (RWD), All-wheel Drive (AWD), and others. Analyzing this relationship can provide valuable insights into the impact of engine design on the efficiency of various vehicle configurations.

Our first graph illustrates the various quantities of engines across the different types of Drivetrains along with the average combined fuel economy. We noticed that there was a consistent downward trend across all the drivetrains as the engine count increased in terms of combined fuel economy. With this being said, the 2-Wheel Drive, Front has the highest average combined fuel economy  for a 4 engine count where the 2-wheel drive, rear had the lowest. This shows that the higher the engine count, the worse it affects the combined fuel economy.

## Question 2: Is there a correlation between annual fuel cost and price paid for fuwl? Can the price of someone's fuel can be predicted from the manufacturer's fuel economy data?

Importance of this question: 
This question investigates whether the annual fuel cost of vehicles affects how much someone pays for unleaded fuel over one year and whether the price of fuel can be predicted from fuel economy data. It also examines variance between city fuel economy and highway fuel economy.


Our second graph displays a trendline between fuel economy and fuel costs of the cars within our dataset. The trendline used is that of a power function line instead of an exponential function as it better fits our graph. For each type of fuel economy (City, Highway, and Combined), as the fuel economy level of a car increases, the annual cost of fuel decreases and vice versa via the trendline. Many of the vehicles will fall within the range of 20–30 FE and will hover around the 2000-3000 annual fuel cost. Using the graph, the annual fuel cost for each car will be able to determine the price paid for fuel for each car. Additionally, the price of a person’s fuel can generally be predicted using the manufacturer’s fuel economy data.

## Manipulations of the Dataset

The original dataset contained lots of surplus information with many null values which we cleaned up in Microsoft Excel before uploading to Tableau. First, our dataset contained information for electric and plug in hybrid vehicles, which our team omitted in our version dataset, focusing on the fuel economy comparisons of strictly gas-powered vehicles. Second, our team identified the columns with large amounts of null values and excluded those columns from our version of the dataset. Next, the dataset also had lots of information relating to environmental regulations, such as CO2 emission data which we also omitted from our dataset version. Finally, we limited our dataset to account for a few redundant dimensions, and our dataset was effectively complete. Still, the final version of our 2024 Fuel Economy dataset is certainly comprehensive, containing over 20 different car divisions, for gas powered cars, SUVs, and trucks manufactured in the year 2024. 

##



