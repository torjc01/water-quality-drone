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

Refs: 

https://www.instructables.com/JALC-Boat-Aquatic-Robot-Platform/ 

https://www.thingiverse.com/thing:470370


### Ocean Data Buoy Project 

It started as a small/cheap 3D printed buoy that could measure wave height and period data on the ocean, and evolved to who else could benefit from small/cheap wave buoys and what would happen if suddenly this technology could be used to network a bunch of these floating buoys together to get high fidelity wave data for areas of interest


Refs:

https://opensourceoceanweatherbuoy.wordpress.com/

https://www.thingiverse.com/thing:2070980

### ROS 

The Robot Operating System (ROS) is a set of software libraries and tools that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project. And it's all open source.

Ref: https://www.ros.org/
