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

## Manipulations of the Dataset:

The original dataset contained lots of surplus information with many null values which we cleaned up in Microsoft Excel before uploading to Tableau. First, our dataset contained information for electric and plug in hybrid vehicles, which our team omitted in our version dataset, focusing on the fuel economy comparisons of strictly gas-powered vehicles. Second, our team identified the columns with large amounts of null values and excluded those columns from our version of the dataset. Next, the dataset also had lots of information relating to environmental regulations, such as CO2 emission data which we also omitted from our dataset version. Finally, we limited our dataset to account for a few redundant dimensions, and our dataset was effectively complete. Still, the final version of our 2024 Fuel Economy dataset is certainly comprehensive, containing over 20 different car divisions, for gas powered cars, SUVs, and trucks manufactured in the year 2024. 

## Tableau Packaged Workbook:
The packaged workbook containing the visualizations shown above is attached to this repository.


# Additional Dataset Information:
•	The data in the table is based on every car released in 2024. 
•	Table specifics
o	Manufacturer – group/company that oversees production of the car. Ex. Aston Martin only produces Aston Martin products, but FCA (sometimes referred to as Stellantis) produces Dodge, Chrysler, Jeep, and RAM.
o	Division – sometimes referred to as the “make” of the car. Ex. An F150’s Division would be “Ford”
o	Carline – sometimes referred to as the “model” of the car. Often repeats as many models have options for different transmissions, or have multiple trims. Ex. Supra 3.0 is listed twice, once for Semi-Automatic, once for Manual.
o	EngineCylinders - # of cylinders in the engine. Engines can have any number of cylinders in their car. Generally speaking, more cylinders means less MPG.
o	City FE – From the manufacturer – this would be the car’s fuel economy on regular gas (87 Unleaded) if the car drove a full tank of gas in a city environment (frequent stops, low speeds, lower gears). Generally considered the lowest fuel economy if the car isn’t driven hard.
o	Hwy FE – from the manufacturer - this would be the car’s fuel economy on regular gas (87 Unleaded) if the car drove a full tank of gas in a highway environment (few stops, high speeds, higher gears). Generally considered the highest fuel economy if the car isn’t driven frugally.
o	Comb FE – from the manufacturer - this would be the car’s fuel economy on regular gas (87 Unleaded) if the car drove a full tank of gas in a mixture of city and highway environment.
o	Aspiration – determines if the engine’s intake has internal “air boost” technology
	Naturally Aspirated – the engine relies on atmospheric pressure. Noo internal boost.
	Turbocharged – Engine relies on an exhaust-driven “turbo” for atmospheric pressure.
	Supercharged – Engine relies on a mechanically-driven supercharger for atmospheric pressure.
	Turbocharged + Supercharged – Engine relies on both a supercharger and a “turbo” for atmospheric pressure. Also called “Twincharged” or “Twincharging” an engine.
	Other – Other cases using uncommon aspiration methods, such as centripetal superchargers and hybrid engine assists.
o	Transmission – the type of transmission that the car is mated to. The transmission controls the power to torque ratio.
	Continuously Variable Transmission (CVT): the transmission only has one gear that is continuously variable, or changes based on the speed of the vehicle. Usually have good fuel economy. No clutch control, but no need because there’s only one gear and you can’t switch gears.
	Automated Manual: A newer version of Semi-automatic, but without a torque converter. No clutch control.
	Semi-Automatic: A version of automatic in which a computer controls clutch control, but with a torque converter. No clutch control.
	Manual: User controls the clutch, which controls whether the transmission/throttle is mated to the engine (whether pressing the gas makes the car go forward). 
	Automatic: User has no control over the transmission’s clutch
o	# of Gears – number of gears in the transmission. More gears = more shifting time, generally means less MPG
o	Drivetrain – decides which wheels the engine is powering.
	2WD, Front (FWD): The front wheels are powered by the engine. Ex. Honda Civic
	2WD, Rear (RWD): The back wheels are powered by the engine. Ex. Mazda MX-5 Miata
	AWD: All wheels are powered by the engine. Torque is distributed evenly to all wheels. Better grip/traction in snow. Ex. Subaru WRX
	4WD: All wheels are powered by the engine, but in low-traction situations, the driver can adjust torque to distribute unevenly. Ex. Chevrolet Silverado
	Part-time 4WD: All wheels are powered by the engine, but in low-traction situations, a computer adjusts torque to distribute unevenly. Ex. Toyota Tundra 4WD
o	Annual Fuel Cost – How much it would cost for one years’ worth of gasoline using regular gasoline (87 Unleaded)
o	# of Intake Valves per cylinder – the # of valves each cylinder inputted into the engine. The higher this value, the more intake the system is receiving.
o	# of Exhaust Valves per cylinder – the # of valves each cylinder in the engine outputs. The higher this value, the more exhaust this system is producing.
o	Carline Class Desc – The type of car that the model is classified under. Some categories are broken into drivetrain type.
o	Release Date – the day that the model was released.




