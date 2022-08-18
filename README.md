# ha-heatwave-alert

Home-Assistant Alert for closing windows to keep your house cool during a heat wave.

## Introduction

To keep your house cool you should close the windows when it is hot outside.

However, deciding whether you should have your windows open or closed during the heat depends on different factors: 
- such as how warm it is outside compared to inside your home
- how well insulated you home is
- how much direct sunlight is on you window

This Home-Assistant Alert will inform you, if it's time to close your windows.

What temperature to close windows?

Though there's no set temperature, you should keep your windows closed when it is cooler inside than outside. The best way to monitor this is by using two thermometers 
- one designed to read the room temperature 
- one for measuring the outside temperature

If you want to air out your home, the best time of day to do this is early in the morning, before it gets too hot, and to only open windows with no direct sunlight on them. 

The afternoon is the hottest time of the day, so windows should remain closed unless there is a strong breeze, in which case you can open the windows but keep the curtains closed.

## Requirements

I will stay generic with devices and services, no bands to keep simple

To monitor outside temperature, you can simply use a Wether Integration. Otherwise you can use any sensor with a thermometer desing for outside, but need to be setup not in direct sun.

For every rooms you wan an alert, you will need 2 sensors:
- temperature sensor
- door/window sensor

## Configuration
