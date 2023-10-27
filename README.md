# Predicting Efficiency Mobility & Classification Analysis of City & Highway Car Performance

## Objective : 
This trend has laid the foundation for a predictive model aimed at classifying the efficiency of cars between 1999 and 2008. The primary goal is to ascertain whether there has been an improvement in performance across different manufacturers over the span of nine years. By delving into the intricacies of these data points, we aim to provide valuable insights into the evolution of the automotive industry and how it has shaped consumer preferences and choices.

## The Data : 
The dataset likely represents a collection of car specifications that can be used for analysis and modeling, such as predicting fuel efficiency based on different attributes, comparing the performance of different car models, or evaluating the impact of specific features on the car's performance.

The data was shared by mentor dibimbing "Abdullah Ghifari".

## Data Collection

### Visualize "Manufacturer"

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/efb8691a-53ce-4a7b-922c-8f57504edbbb)

### Visualize "Displ"

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/ec3f6576-6ddb-4c14-bdef-3224bb7714ed)

Insight : 'displ' Displacement refers to the total volume of all the cylinders in an engine, typically measured in liters (L) or cubic centimeters (cc). It is an essential specification that provides information about the engine's size and can often be indicative of the engine's power and performance characteristics.
A higher displacement generally suggests a larger, more powerful engine, while a smaller displacement may imply a more fuel-efficient or smaller engine.

- Visualize "Cylinders"

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/b0f640a4-e455-4715-97e1-c5e30678fdb2)

Insight : 'cyl' refers to the number of cylinders in the engines of the corresponding vehicles.
The number of cylinders can significantly impact a vehicle's power, efficiency, and overall driving experience.

- Visualize "Transmission"

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/f1f54028-19cc-4b5f-b83b-26dd3088eccb)

- Visualize "Fuel"

Insight : "fl" represents the fuel type of the vehicles, with the accompanying letters indicating different fuel categories

Based on the data:

* 168 vehicles use regular gasoline (fl r)
* 52 vehicles use premium gasoline (fl p)
* 8 vehicles use ethanol (fl e)
* 5 vehicles use diesel (fl d)
* 1 vehicle uses compressed natural gas (fl c)

- Visualize "Class"

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/921ea9da-9eae-4314-8e1c-42c743df0140)

## Target Analysis
- **Cty** : "cty" likely represents the city fuel efficiency of the vehicles in miles per gallon (mpg).

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/7d1aa474-3383-4a90-b24d-86af749a8a8f)

Vehicles with higher city fuel efficiency are often preferred by consumers seeking cost-effective and eco-friendly transportation options for urban commuting and stop-and-go traffic scenarios.

- **Hwy** : "hwy" likely represents the highway fuel efficiency of the vehicles in miles per gallon (mpg).

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/464ea2d4-7c33-4f4d-843d-68cca59eca6a)

**High highway fuel efficiency is desirable for several reasons:**

1. **Cost-Effectiveness** : Vehicles with high highway fuel efficiency can help drivers save money on fuel costs during long-distance trips or highway driving.

2. **Environmental Impact** : Improved fuel efficiency contributes to lower fuel consumption, reducing the environmental impact by decreasing the emission of greenhouse gases and pollutants.

3. **Sustainability** : Enhanced fuel efficiency promotes sustainable practices by reducing the reliance on non-renewable energy sources and conserving natural resources.

## Data Cleaning :

### There no Missing Value

### Counting & Identify Duplicated
![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/a31f5903-f587-42a1-9f73-756887ffd24d)

## Outliers
![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/b191d9cc-4770-4b61-acfa-40be201793be)
Insight :
![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/0cf48c48-8ec8-4650-9b82-9807ec84c264)

## Feature Engineering

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/82e8f298-5d98-4ef9-b39c-47bad9c0bd5d)

### Cty Columns

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/aa9baa18-35ad-4d7b-8c89-76386e357a0f)

- cty_efficiency.value_counts()

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/4ee4bc7d-370f-4cb0-9bf2-a80997e8343d)

### Hwy Columns

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/31243d7c-97b5-42ea-ae36-2f153a81e60f)

- hwy_efficiency.value_counts()

![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/81b86309-9f69-474f-b941-846ce520aab7)

## Deep Dive EDA :

- An examination between Transmission vs City Mobility Efficiency
![image](https://github.com/GITA-2112/mpg_othervariable/assets/135007275/48d5731d-344b-4ab3-95a5-79f21f9d8e22)

- An examination between Transmission vs Highway Mobility Efficiency
