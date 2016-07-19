---
layout: project-page
title: "Supervolcano Yellowstone"
linkname: yellowstone-volcano
author: "James Robinson"
location:
    - place: Yellowstone National Park
project-link:
    - href: /summer2016/pdf/yellowstone-volcano.pdf
thumbnail-path: img/yellowstone-volcano/thumbnail.jpg
---

I've always been fascinated by earth's natural features. Whenever I see a road cut or mountains up close I try to imagine the processes and timescale that formed the rock I'm looking at. Yellowstone National Park has some of the most strange and interesting natural features and geology on earth.  It is one of a handful of volcanoes on earth that qualify as a supervolcano - a volcano capable of producing an eruption with ejecta mass greater than 10^15 kg (according to wikipedia).  Researcher's believe the last time Yellowstone erupted was around 640 thousand years ago.  The tephra (ejected ash and rock) from the last eruption as well as eruptions dating back to 1.3 million years ago and 2.1 million years ago have been found thousands of miles away from the Yellowstone crater.  What and who would be effected if Yellowstone were to erupt in modern times? That's what I set out to map for this project.  

Finding data and making it useful was the most difficult bit of this project.  After a bit of searching, I eventually found a publication from a group of researchers who had developed a model for predicting ashfall from a hypothetical Yellowstone eruption ([Modeling ash Fall Distribution from a Yellowstone Supereruption by Larry G. Mastin, Alexa R. Van Eaton, and Jacob B. Lowenstern, published by AGU in Aug 2014](http://onlinelibrary.wiley.com/doi/10.1002/2014GC005469/abstract;jsessionid=E0DC5A3A5A49898454E72C370BBC6C9B.f02t03)).  Given the timing of the class (July) and wanting to show the most severe outcome possible (for visual effect), I settled on using their simulation for a 3-day eruption occurring in July.  This simulation assumes the eruption will eject 330 km^3 of tephra in the form of a major umbrella cloud (meaning the bulk of the plume stagnates and disperses once it goes above the windy areas in our atmosphere).  Given my ignorance with datafiles, figuring out how to use and map their [kindly provided] simulation data was a bit tricky.  It was in the form of an Esri-specific ASCII file which I had to reorient to the correct lat/long export as a geotiff. 

The map shown above details what I decided is the significant ashfall area (where ash depth >5 cm) as well as oil pipelines and rail terminals.  I also mapped potential hazards involving roadways, power plants, cities, and census data.
