# Low-Cost Air Quality Sensors to Assess Children Health Risk in Dublin Schools
### Trinity College Dublin x Dublin City Council
## Contents

 - [Overview](##overview)
 - [Analysis](##Analysis)
 - [Conclusion](##Conclusion)

## Overview
Children are the most vulnerable to the effects of air pollution yet with the least agency over their health. Early exposure to PM2.5 can lead to cognitive disorders (ADHD, ASD), asthma, impaired lung and brain growth.
Yet there are no air quality studies of schools and daycares in Ireland, 
falling behind its EU peers. Oftentimes, uninformed caretaker and school behaviors can contribute to child exposure. As such, this study aims to be the first to assess children health risk and allow schools and caretakers to take informed mitigation.

This project selected a local neighborhood to monitor based on the google airview data. The selection criteria was based on:
 - Residential and school zones
 - High pollution zones
 - Google Air data reliability
 - Range of small and major roads
**I selected the Phibsborough neighborhood to bring focus to the more disadvantaged, polluted north Dublin.**

Schools in the neighborhood were then selected on:
 - Source receptor pathway
 - Green space potential
 - Type: national school vs daycare
 - Google Air data distribution
<img width="200" alt="image" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/224d5214-9a38-403b-aeb7-4df30b44db35">

#### Street-Level Monitoring
<img width="246" alt="Screen Shot 2023-12-15 at 2 19 23 AM" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/60af3b5a-b57d-4cc6-ac34-05b9520036fa">
The sensors collected live, NO2, particulate matter, ozone, CO2, temperature, and humidity for 4 weeks. The goal is to identify emissions sources (e.g. traffic, winter home burning), influential factors, and assess geographic risks based on locations of schools.

#### School Monitoring
I collaborated with a local school to monitor the effect of different source to receptor pathways on indoor and outdoor air pollution for 2 weeks. I conducted participatory monitoring with indoor sensors, and spoke with teachers to hear their concerns about lack of access to air quality information. 
 What agency can a school take to protect their children’s health?
<img width="358" alt="Screen Shot 2023-12-15 at 2 27 55 AM" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/ab81814e-536c-47eb-9c65-9fe240cbbccb">

 ## Analysis
 **What are the sources putting children health at risk? When are these occurring and how can they be mitigated?**
#### Peak Analysis
Taking lessons from the Breathe London project, I apply peak analysis to understand pollution characteristics. 
 - Peaks from 18:00-21:00 align with solid fuel burning for home heating patterns, a major pollution issue across Europe due to high electricity costs
- Pollution episodes can last from 10-30hrs, persisting into school hours the next day
- School sites, as most are in residential areas, are exposed to episodes up to 60 ug/m3 (4x WHO daily limit)
<img width="183" alt="image" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/26bbda75-dde6-4e81-b336-1201f0bd54a3">
<img width="226" alt="image" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/430f2f51-93fe-4a9f-9eab-7f740500f290">

#### Indoor Leakage
We captured a snapshot of the classroom; concentrations rise through the evening, indicating leakage from outside home burning pollution into empty, enclosed classroom that may persist until the following school day.
<img width="213" alt="image" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/88b97d6f-822a-4e07-ac97-db93826e8e76">

#### Random Forest Regression
Temperature and day of the week were highly influential features, supporting the link with domestic heating occurring when people are home and when temperature is low.
<img width="181" alt="image" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/723b201a-2bd4-4a48-a75e-a172c9d0c8c5">
<img width="85" alt="image" src="https://github.com/michelleh1109/dublin-school-aq/assets/90575654/1ee56cad-e029-4715-80e5-0bc6475cf347">

## Conclusions
My research found that in residential areas, the severe PM2.5 pollution from solid fuel for heating seeps into indoor classrooms and persists into school hours. I spoke with a teacher from the neighborhood about this issue: she shared her and her neighbors' financial struggles to afford cleaner heating options. This illustrates income inequality and environmental health are multi-dimensional, where children exist at the most vulnerable intersection. Future research includes policy initiatives to incentivize away from home burning.
