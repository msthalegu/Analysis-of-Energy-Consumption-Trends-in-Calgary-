# Energy and Emissions in Calgary: Patterns, Trends, and Recommendations (2019-2023)

## Project Overview
This report presents a statistical summary of the dataset, highlighting key observations, trends in energy consumption and efficiency, and seasonal consumption patterns. Additionally, it provides recommendations on how to improve energy efficiency based on the observed data.
This dataset contains information on energy consumption and greenhouse gas (GHG) emissions in the city of Calgary from 2019 to 2023. It includes key attributes such as property type, building name, address, and postal code. The original dataset consisted of 494 rows and 31 columns, but columns with more than 40% missing or null values were removed to ensure data quality. Additionally, numerical values were extracted from string-based columns, postal codes were standardized, and meaningful text was extracted from property names and addresses to facilitate analysis. These preprocessing steps were performed using regular expressions (Regex).

## Statistic Summary
![image](https://github.com/user-attachments/assets/e19dec30-2ce2-478a-9f31-a82c059c4670)

The standard deviation for Source Energy Use (18,232 GJ) and Total GHG Emissions (1,078 metric tons CO2e) is significantly larger than their respective means (4,556 GJ and 442 metric tons CO2e). This indicates substantial variation in energy consumption and emissions across different sites, likely due to differences in building size, operational efficiency, and climate conditions. Additionally, key metrics such as Weather Normalized Site Energy Use, Source Energy Use, Total GHG Emissions, and Electricity Use exhibit right-skewed distributions. The large gap between the mean and median suggests that a small number of high-energy-consuming properties drive up the average, while the majority of sites operate at much lower consumption levels. 
When analyzing data distribution, it is important to consider the presence of outliers. In this dataset, lower outliers are not realistic, as energy consumption cannot be negative. However, their presence highlights the extent to which extreme high outliers—above the 75th percentile—distort the overall distribution, making these lower values appear artificially low. The true lower boundary for energy consumption is 0, which represents properties with minimal or no recorded usage.

![image](https://github.com/user-attachments/assets/f5440fd6-ab47-41e2-b8b3-c066be8b3a20)

Generally, the trend in site energy usage increases as the property’s GFA (Gross Floor Area) grows, which is expected, as larger buildings typically consume more energy. Energy usage is closely linked to greenhouse gas (GHG) emissions. While the type of energy used also impacts GHG emissions, in Calgary—where oil and gas are commonly used—higher GHG emissions are associated with higher energy consumption, as shown in Figure 1.

## Key Trends in Energy Consumption and Efficiency

![image](https://github.com/user-attachments/assets/e27c0ff2-e365-403d-929d-f1072be82950)

Figure 2 shows that the quadrants with the highest energy consumption per square meter in Calgary are SW and SE, with values exceeding 45 GJ/m². In contrast, NE and NW have the lowest energy consumption per square meter, remaining below 40 GJ/m².


![image](https://github.com/user-attachments/assets/fd86e061-be30-4cea-b864-5a7839cd5e8d)

Figure 3 highlights trends in energy consumption by property type over time. Notably, Fitness Centers/Health Clubs/Gyms and Ice/Curling Rinks experienced a decline in energy consumption during 2020-2021, reflecting the impact of the COVID-19 pandemic, which led to temporary closures and reduced operations.

![image](https://github.com/user-attachments/assets/3bc1df0c-a664-44d0-a99c-d4dc70d9c506)

Examining the relationship between site energy usage, GHG emissions, and Gross Floor Area (GFA) in Figures 3 and 4, we can assess consumption efficiency. The top three property types with the highest energy consumption from 2019 to 2023 are Fire Stations, Fitness Centers/Health Clubs, and Offices. Interestingly, despite Fitness Centers ranking second in energy consumption, their GHG emissions are lower than those of Offices, suggesting higher energy efficiency in their operations. A similar trend is observed in Non-Refrigerated Warehouses, which moved up in ranking for GHG emissions despite not being among the highest energy consumers.

Another key observation is the overall improvement in energy efficiency across all property types over time. The energy consumed per square meter and the emissions produced per square meter have gradually decreased, likely due to advancements in energy-saving technologies and increased adoption of sustainability practices.

## Seasonal and property type variations.
![image](https://github.com/user-attachments/assets/d736101b-10ad-42f8-9351-e6a28e974c69)

Figure 5 illustrates the difference between weather-normalized and actual site EUI (Energy Use Intensity), highlighting how actual energy usage deviates from expected (normalized) values. The property types with the highest EUI differences in 2023 have shown a steady increase in energy consumption since 2019, with significant fluctuations in 2020. These variations suggest an influence of seasonal changes, particularly in 2020 and 2023.

The top three properties with the largest EUI differences are primarily commercial and civic buildings. Commercial properties, such as offices and fitness centers/health clubs, require high energy consumption due to continuous daily operations and the use of electronic equipment. Similarly, civic buildings like fire stations, which operate 24/7 and rely on high-energy equipment, also exhibit substantial energy usage. In contrast, properties such as museums, self-storage facilities, and social meeting halls—used intermittently—tend to have significantly lower energy demands.


## Recommendations for improving energy efficiency and reducing emissions
In general, properties should maintain or upgrade insulation and equipment to improve energy efficiency and reduce GHG emissions. Calgary is also increasing its use of renewable energy, which can help further decrease GHG emissions. The adoption of advanced, energy-saving equipment is particularly beneficial for properties like offices, fitness centers, and fire stations, promoting more energy-efficient buildings.








