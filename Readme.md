# Just a Measuring Device (JMD) Capnograph

## Problem Statement
How to create a capnograph with available CO2 sensors and a processor with display? Capnograph is a respiratory etCO2 measurement device to check Acute Respiratory Distress Syndrome (ARDS) patient's vitals. While developing it, one has to keep in mind following:-
- response time of the sensor
- compatibility with the international standards for interfaces with the respiratory tubings
- cost of the device (targeted to be <$150)
- size and ease of use of the device

## Motivation
In times of COVID-19, there are several groups which worked on the masks, DIY-ventilators, spirometers, face-shields etc as these are essential for safety of the care giver or survival of the patient. At the same time, etCO2 reflects reliable information about the endotracheal tube position, cardiac output, lung pathology and compliance. Cost of etCO2 modules are prohibitive in nature for developing countries and making a DIY device with a sensor available in the market may help the cause.

## Scope and reasoning
- breaths per minute more than 20 (neo natal cases)
- modular approach (micro pump, sensor, display)
- side stream vs main stream
- must have its own display
- integration to mobile phone in the second stage
- no certification

## Bill of Material
- GSS SprintIR-W sensor
- ESP32 OLED Display Module

## Resources
- 

## Experimentation

A snapshot of what is possible with the sensor, so that the user gets the idea of the result already on the main page before taking a deep-dive
