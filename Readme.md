A simple 4th order 10 MHz xtal filter for Grehack 2018 Workshop

A Kicad project for GreHack 2018 workshop

This repository contains a easy to build-easy to reproduce 4th order filter using low cost 10 MHz crystal device in HC49 form factor.

This filter has been designed for educational purpose, and could be the perfect companion for a 10 MHz harmonic-free reference clock 
(gps-do, ocxo or any kind of digitaly generated square wave RF source)

This filter could be used in conjunction with the OCXO based "Aion" reference clock 

https://github.com/F6ITU/OCXO

This board has been designed with Kicad, an Open Source EDA software developped by the CERN.

For better performances, noise imunity and port isolation, this board should be shielded. 

The "Simu" subdirectory contains several simulation and measurement files : 
* 10M-4-5kHz 337ohms 47pf.sch is the "ADDE Filter design" simulation file and schematics of the filter itself
* BOM.doc is the Bill of Material used during the Grehack 2018 workshop
* filtre 10 MHz 4 eme ordre2.png is a screen capture of the filter's response measured with a Network Analyzer (Smith chart and amplitude/insertion losses) 
* filtre 10 MHz 4eme ordre.s2p is the real characteristic of the filter (2 port Touchstone file format). This file could be 
imported in any kind or analyzer or RF simulation software (QUCS, Elsie, VNWA.exe etc)
* filtre.jpg is a picture of the filter itself, without shield
