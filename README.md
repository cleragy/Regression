# Analyzing CO2 Emissions in the Agri-Food Sector

![IMG_2564](https://github.com/nonkululekomgaga1/RegressionSprint_2401FTDSTeam_EG4/assets/167474790/eb04ee09-6da8-4540-99c9-7bbb5cab79e3)


## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

### Objective
Our team, comprising environmental consultants and data scientists, has been tasked by a coalition of agricultural stakeholders to analyze and predict CO2 emissions from the agri-food sector. The project aims to understand the sector's impact on climate change and develop strategies for sustainable practices.

### Approach

*Data Compilation*: We will utilize comprehensive datasets from the FAO and IPCC, covering various aspects of agricultural activities and their CO2 emissions.
*Emission Source Analysis*: We'll categorize emissions from sources such as livestock, land use, fertilizers, machinery, and transportation.
*Regression Analysis*: Employ regression techniques to identify trends and correlations between agricultural practices and CO2 emissions.
*Impact Assessment*: Explore the relationship between CO2 emissions and temperature variations to assess the sector's contribution to climate change.
*Stakeholder Engagement*: Regular engagement with policymakers, agricultural businesses, and environmental organizations to ensure relevance and applicability of our findings.

## 2. Dataset <a class="anchor" id="dataset"></a>
Emissions from the agri-food sector play a crucial role in climate change, as they represent a significant share of global annual emissions. The dataset highlights the substantial contribution of the various sources of emissions. Therefore, it is essential to understand and address the environmental impact of the agri-food industry to mitigate climate change and promote sustainable practices within this sector.

**Dataset Features:**
- Savanna fires: Emissions from fires in savanna ecosystems.
- Forest fires: Emissions from fires in forested areas.
- Crop Residues: Emissions from burning or decomposing leftover plant material after crop harvesting.
- Rice Cultivation: Emissions from methane released during rice cultivation.
- Drained organic soils (CO2): Emissions from carbon dioxide released when draining organic soils.
- Pesticides Manufacturing: Emissions from the production of pesticides.
- Food Transport: Emissions from transporting food products.
- Forestland: Land covered by forests.
- Net Forest conversion: Change in forest area due to deforestation and afforestation.
- Food Household Consumption: Emissions from food consumption at the household level.
- Food Retail: Emissions from the operation of retail establishments selling food.
- On-farm Electricity Use: Electricity consumption on farms.
- Food Packaging: Emissions from the production and disposal of food packaging materials.
- Agrifood Systems Waste Disposal: Emissions from waste disposal in the agrifood system.
- Food Processing: Emissions from processing food products.
- Fertilizers Manufacturing: Emissions from the production of fertilizers.
- IPPU: Emissions from industrial processes and product use.
- Manure applied to Soils: Emissions from applying animal manure to agricultural soils.
- Manure left on Pasture: Emissions from animal manure on pasture or grazing land.
- Manure Management: Emissions from managing and treating animal manure.
- Fires in organic soils: Emissions from fires in organic soils.
- Fires in humid tropical forests: Emissions from fires in humid tropical forests.
- On-farm energy use: Energy consumption on farms.
- Rural population: Number of people living in rural areas.
- Urban population: Number of people living in urban areas.
- Total Population - Male: Total number of male individuals in the population.
- Total Population - Female: Total number of female individuals in the population.
- total_emission: Total greenhouse gas emissions from various sources.
- Average Temperature °C: The average increasing of temperature (by year) in degrees Celsius,
 

CO2 is recorded in kilotonnes (kt): 1 kt represents 1000 kg of CO2.

The feature "Average Temperature C°", represents the average yearly temperature increase. For example, if it is 0.12, it means that the temperature in that specific location increased by 0.12 degrees Celsius.

Forestland is the only feature that exhibits negative emissions due to its role as a carbon sink. Through photosynthesis, forests absorb and store carbon dioxide, effectively removing it from the atmosphere. Sustainable forest management, along with afforestation and reforestation efforts, further contribute to negative emissions by increasing carbon sequestration capacity.

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```

