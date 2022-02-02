### car-emissions

# Have you ever wondered how much CO2 your car has been emitting?

### About us:
- Chris Lammers (chrislammers)
- Mariyam Muhammad Alim (MariyamAlim)
- Bhargav Parekh (parekhbhargav25) 

### Introduction

In this report, we will be investigating the CO2 emissions by vehicles from 2000 to 2014. The dataset we used is called “CO2 Emission by vehicles” and was made available to the public by the Government of Canada on March 31, 2017. It has information on the fuel consumption and CO2 emissions of different types of vehicles from the years 2000 to 2014. When presenting our proposal, we had selected a dataset that did not have a time attribute and therefore performing exploratory data analysis (EDA) on that dataset was slightly challenging but this dataset does have a ‘Model Year’ column and thus, performing EDA was easier. 

### Discussion

While initially exploring the data, we found that vehicles from sports/luxury car manufacturers such as Bugatti, Ferrari, and Bentley emitted most CO2. Vehicles from brands like Smart, Fiat, and Mini generally produce less CO2.

All of the columns in this dataset were closely related to each other. The number of cylinders is positively correlated to fuel consumption and CO2 emissions (Figure 1) which means the more cylinders a vehicle has, the more fuel it uses and thus, the more CO2 it emits. Figure 2 shows the strong positive correlation fuel consumption and CO2 emission have. The more fuel is used, the more CO2 is emitted by the vehicle. Figure 3 demonstrates the strong positive correlation between engine size and CO2 emission. While it's clear that larger engines produce more CO2, the fuel type doesn't show any clear patterns.

Figures 4 and 5 demonstrate the efficiency of each fuel type. Diesel uses the least fuel per 100 km to produce the same amount of energy while ethanol and natural gas use the most fuel. Therefore, diesel is the most efficient fuel type while ethanol and natural gas are the least efficient fuel types.

Figure 6 shows us that between 2000 and 2014, regular and premium gasoline were the most used fuel types while natural gas was the least used.

Figure 7 demonstrates the fact that larger vehicles emit more CO2 as compared to smaller vehicles.

In Figure 8, we observed trends in the popularity of different fuel types between the years 2000 and 2014. Despite being the most efficient, diesel fuel isn't popular compared to the others. Ethanol was also one of the less popular fuel types. Regular and premium gasoline maintain their spot as the most used type. There were no vehicles that used natural gas after 2004.

Finally, we created Figure 9 to analyze the trends of average CO2 emissions by vehicles made between 2000 and 2014. There isn't a big difference in the average CO2 emitted by vehicles made in 2000 as compared to those made in 2014 but there is a downward trend, which means vehicles are polluting less CO2 on average.

### Conclusion

After performing exploratory data analysis on the “CO2 Emission by Vehicles” dataset, we learned about what impact different vehicle features and fuel types have on the fuel consumption of a vehicle and the CO2 they emit.
#### Reflection
- Fuel consumption and CO2 emissions are directly related to one another. The more fuel a vehicle uses, the more CO2 it emits.
- Engine size and CO2 emissions have a strong positive correlation. The larger the engine, the more CO2 it emits.
- Fuel consumption at highways and in cities is almost the same.
- Diesel is the most efficient fuel type while natural gas is the least efficient. Diesel produces the same amount of energy as natural gas but uses less amount of fuel.
- Natural gas is the least used fuel type from the years 2000 - 2014, while regular and premium gasoline are the most used fuel types
- The larger the vehicle, the more fuel it uses and CO2 it emits.
- Diesel is the most efficient fuel type but has been one of the least popular fuel types while regular and premium gasoline have been the most popular between the years 2000 and 2014.
- The average CO2 emitted by vehicles made in 2000 is a lot more than vehicles made in 2014.
#### Refinement
- To improve this project further, we would calculate the fuel consumption ratings for each vehicle.
- We could also calculate the efficiency for each vehicle.
- If we had information on where each vehicle was driven or registered during a specific time, we could have come up with CO2 emission trends region-wise. We could have then compared CO2 emission levels in different regions.

### Acknowledgements
“This project was submitted as the final course project for CSCI 2000U “Scientific Data Analysis” during Fall 2021. The authors certify that the work in this repository is original and that all appropriate resources are rightfully cited.”
