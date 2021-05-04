[![img](https://img.shields.io/badge/Lifecycle-Experimental-339999)](https://github.com/bcgov/repomountie/blob/master/doc/lifecycle-badges.md)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
---
[[Version Française](README_fr_CA.md)]
# Water Quality Drone

A water quality monitoring drone to be deployed on lake surfaces.

## Issues to investigate 

- Sceptic tanks 
- Boats' gas and oil byproducts 
- Mining industry 
- Plastic residues 
- Agricultural residues 
- Algae infestation

## Parameters 

- Temperature 
- pH 
- Turbidity 
- Total dissolved solids 
- Electro Conductivity (EC)
- Dissolved oxygen (DO)
- Oxygen reduction potential (ORP)
- Clorophyl data (algae)

### Temperature 

### pH

pH defines the acidic and basic nature of water impurity. A pH value is a number from 1 to 14, with 7 as the middle (neutral) point. Values below 7 indicate acidity which increases as the number decreases, 1 being the most acidic. Values above 7 indicate alkalinity which increases as the number increases, 14 being the most alkaline. 

If the water in a stream is too acidic or basic, the H+ or OHion activity may disrupt aquatic organism’s biochemical reactions by either harming or killing the stream organisms.

<p align="center">
  <img src="images/ph.png" label="ph Scale" />
  <br>
  <b>pH Scale</b>
</p>

## Datasources 
| Data Source | Interval | Typical reading | Typical range | 
|------------ | -------- | --------------- | ------------- | 
| Temperature | Once every 5 minutes | 17,5°C | -25°C to 45°C | 
| pH | Once every 5 minutes | 7,5 | 6 to 9 | 
| Turbidity | Once every 5 minutes | 1500/ppm | ? | 
| Total dissolved solids | Once every 5 minutes | 1500/ppm | ? | 
| Electroconductivity | Once every 5 minutes | 0.5V | ? | 
| Dissolved oxygen | Once every 5 minutes | ? | ? | 
| Oxygen reduction potential | Once every 5 minutes | ? | ? | 
| Chlorophyl Data| Once every 5 minutes | ? | ? | 
| Label| Once every 10 minutes | "Normal" | ["Normal", "Abnormal"] | 

## Brainstorming

### Block diagram 

The block diagram was the result of sessions brainstorming about the possibilities and the requisites analysed for Lake Sergent's needs. 

<p align="center">
  <img src="images/brainstorming.jpg" label="Brainstorming" width="800"/>
  <br>
  <b>Block diagram</b>
</p>

Edit this draft into a working diagram in a drawing tool.

## Technological platforms 
### JALC Boat 

JALC Boat is a project aimed to create an aquatic robot educational platform. Its components are 100% free and designed with 3D printing for anyone to create, adapt or modify.

USV Platform 

Dimensions: 28 x 24 x 28cm (W x L x H)

Weight: +- 3kg 

Max speed: 40 cm/s (+-19 km/h)

Normal temp range: 20 - 25ºC

Estimated operating time: 30 min

Wave height: 7 cm 

Windspeed < 4m/s (1,52 km/h)

It uses 2 thrusters BLDC (Brushless direct current)

Buoyancy force +- 28.6 N 

HC06Bluetooth : max range 20m

Ref: https://www.instructables.com/JALC-Boat-Aquatic-Robot-Platform/ 

### Ocean Data Buoy Project 

It started as a small/cheap 3D printed buoy that could measure wave height and period data on the ocean, and evolved to who else could benefit from small/cheap wave buoys and what would happen if suddenly this technology could be used to network a bunch of these floating buoys together to get high fidelity wave data for areas of interest


Ref: https://opensourceoceanweatherbuoy.wordpress.com/

### ROS 

The Robot Operating System (ROS) is a set of software libraries and tools that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project. And it's all open source.

Ref: https://www.ros.org/
