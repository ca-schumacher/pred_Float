# pred_Float
Data analysis of a reverse cationic flotation process

# Predicting the effectiveness of a Froth floating process

**June 2019**

## Introduction

**Project Description:**

We will use this dataset to analyse and predict a (reverse cationic) Froth floating process having the two aims:
* What is the best predictor for the iron concentration of the product?
* Can the data set be used to predict the impurity of the product (by silicate concentration)?

**Data Description:** 

This notebook deals with the analysis of a reverse cationic flotation process of a real production environment. The data (including its documentation) is accessible through kaggle: https://www.kaggle.com/edumagalhaes/quality-prediction-in-a-mining-process

**The Froth flotation process:**

The froth floatation is used to seperate the iron contents in the ore from other contaminations. The whole process usually contains for steps:

- Contioning of the ore feed pulp (mixture of ore and water) and other reagents
- Separation of hydrophobic and hydrophilic materials: binding particles attach to the bubbles
- The bubbles transport the particles upwards until they float on the surface (froth)
- Collection of the froth by mechanical separation (e.g. by an impeller)

The pulp is added to the cell and flows to the bottom where it is mixed with an air or nitrogen flow. Both are swirled e.g. by an impeller to create bubbles to which the particles can bind. The bubbles then transport the particles upwards. By this process, the particles in the froth can be separated from the pulp.

## Approach

---

## Explanation of data columns:

**date**

**% Iron Feed** % of Iron that comes from the iron ore that is being fed into the flotation cells

**% Silica Feed**			% of silica (impurity) that comes from the iron ore that is being fed into the flotation cells

**Starch Flow**			Starch (reagent) Flow measured in m3/h

**Amina Flow**			Amina (reagent) Flow measured in m3/h

**Ore Pulp Flow**			t/h

**Ore Pulp pH**			pH scale from 0 to 14

**Ore Pulp Density**		Density scale from 1 to 3 kg/cm³

**Flotation Column 01 Air Flow**	Air flow that goes into the flotation cell measured in Nm³/h

**Flotation Column 02 Air Flow**	Air flow that goes into the flotation cell measured in Nm³/h

**Flotation Column 03 Air Flow**	Air flow that goes into the flotation cell measured in Nm³/h

**Flotation Column 04 Air Flow**	Air flow that goes into the flotation cell measured in Nm³/h

**Flotation Column 05 Air Flow**	Air flow that goes into the flotation cell measured in Nm³/h

**Flotation Column 06 Air Flow**	Air flow that goes into the flotation cell measured in Nm³/h

**Flotation Column 07 Air Flow** Air flow that goes into the flotation cell measured in Nm³/h

**Flotation Column 01 Level**	Froth level in the flotation cell measured in mm (millimeters)

**Flotation Column 02 Level**	Froth level in the flotation cell measured in mm (millimeters)

**Flotation Column 03 Level**	Froth level in the flotation cell measured in mm (millimeters)

**Flotation Column 04 Level**	Froth level in the flotation cell measured in mm (millimeters)

**Flotation Column 05 Level**	Froth level in the flotation cell measured in mm (millimeters)

**Flotation Column 06 Level** 	Froth level in the flotation cell measured in mm (millimeters)

**Flotation Column 07 Level**	Froth level in the flotation cell measured in mm (millimeters)

**% Iron Concentrate** % of Iron which represents how much iron is presented in the end of the flotation process (0-100%, lab measurement)

**% Silica Concentrate** % of silica which represents how much iron is presented in the end of the flotation process (0-100%, lab measurement)

