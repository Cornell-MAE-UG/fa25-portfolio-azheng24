---
layout: project
title: Heat Exchanger Analysis
description: MAE 2210 class
technologies: [Hand Calculations]
image: /assets/images/heat-exchanger-par.jpeg
---

## Overview
---  

This project is a class project for ENGRD 2210 – Thermodynamics.

It involves selecting a real-world thermodynamic device or system covered in the course—such as a heat exchanger, pump, refrigerator, engine, or turbine—and explaining in detail how it operates using system diagrams, photos or schematics, and the appropriate mass, energy, and entropy balance equations. The core objective is to demonstrate a clear understanding of the underlying thermodynamic principles and then analyze how a specific design or operating change would affect system performance.

I chose to analyze a heat exchanger. My main goal was determine the thermodynamic differences between operating heat exchangers in parallel flow and counterflow. 

## Setup:
---  

This is an example of the heat exchanger in **parallel flow**. The hot and cold flow in the same direction.

![Heat exchanger parallel setup]({{ "/assets/images/heat-exchanger-parallel.jpeg" | relative_url }}){: style="width: 600px"}

This is an example of the heat exchanger in **counterflow**. The hot and cold flow in opposite directions.

![Heat exchanger counter setup]({{ "/assets/images/heat-exchanger-counter.jpeg" | relative_url }}){: style="width: 600px"}


## Initial Analysis:
---  

![Heat exchanger intital analysis]({{ "/assets/images/heat-exchanger-2.jpeg" | relative_url }}){: style="width: 600px"}


## Results:
---  


##### Parallel Flow Temperatures

| Measurement&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;Cold (°C)&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;Hot (°C)&nbsp;&nbsp;&nbsp; |
|:-----------------------------|----------------------------------------------:|---------------------------------------------:|
| Initial&nbsp;&nbsp;&nbsp;     | &nbsp;&nbsp;7.3&nbsp;&nbsp;                   | &nbsp;&nbsp;39.5&nbsp;&nbsp;                 |
| Final&nbsp;&nbsp;&nbsp;       | &nbsp;&nbsp;18.7&nbsp;&nbsp;                  | &nbsp;&nbsp;22.3&nbsp;&nbsp;                 |
| ∆T&nbsp;&nbsp;&nbsp;          | &nbsp;&nbsp;11.4&nbsp;&nbsp;                  | &nbsp;&nbsp;-17.2&nbsp;&nbsp;                |

##### Counter Flow Temperatures

| Measurement&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;Cold (°C)&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;Hot (°C)&nbsp;&nbsp;&nbsp; |
|:-----------------------------|----------------------------------------------:|---------------------------------------------:|
| Initial&nbsp;&nbsp;&nbsp;     | &nbsp;&nbsp;5.3&nbsp;&nbsp;                   | &nbsp;&nbsp;39.9&nbsp;&nbsp;                 |
| Final&nbsp;&nbsp;&nbsp;       | &nbsp;&nbsp;22.2&nbsp;&nbsp;                  | &nbsp;&nbsp;18.2&nbsp;&nbsp;                 |
| ∆T&nbsp;&nbsp;&nbsp;          | &nbsp;&nbsp;16.9&nbsp;&nbsp;                  | &nbsp;&nbsp;-21.7&nbsp;&nbsp;                |



## Further Analysis:
---  

In this analysis, I take a look at making the system boundary for a single flow in the exchanger to examine the relationship between change in temperature(∆T) and heat transfer(Q). 

![Heat exchanger further analysis]({{ "/assets/images/heat-exchanger-3.jpeg" | relative_url }}){: style="width: 600px"}

From this analysis, we can see that the heat transfer is directly proportional to the change in inlet and outlet temperatures.


## Conclusion
---  

Based on this data and analysis, we can conclude that counterflow heat exchangers are generally considered better than parallel flow heat exchangers for heat transfer. 

In a counterflow heat exchanger, the two fluids flow in opposite directions. This allows for a more consistent temperature difference between the fluids along the length of the exchanger, which promotes better heat transfer. In contrast, in a parallel flow heat exchanger, the fluids flow in the same direction, and the temperature difference decreases along the length of the exchanger, reducing the heat transfer efficiency.
