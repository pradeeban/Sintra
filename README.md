# About

Simple gnuplot script to plot latitude-longitude coordinates on a World map. The attached World map (`world-50m.txt`) is at 1:50m resolution. 

The example data maps the healthcare sites to Internet round trip delay to a RIPE Atlas Anchor in Atlanta.

Includes 2 variables rather than just static points on the geo-locations
* A color-based z-axis to show counts in each location. In the example, it is the number of healthcare sites in the city/town/region.

* The circle radius as the second variable, showing an Internet performance metric, an inverse of round trip delay to Atlanta, from the RIPE Atlas probes in the city/town/region. 
