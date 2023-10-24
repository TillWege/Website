---
number: 3
title: 'Assignment 3 - Additive manufacturing'
course: 'df'
pubDate: 'Oct 16 2023'
---

## Assignment

For this assignment we were tasked with producing a 3D-model using additive manufacturing. The model had to be designed in CAD and then printed using a 3D-printer. The model had to be designed in such a way that it could not be produced using traditional subtractive manufacturing methods like milling.

## Designing


<figure style="float: right">
    <img src="/df/df-3a.jpg" style="max-height: 200px" />
    <figcaption><p>Design</p></figcaption>
</figure>

For the design of the part I decided to model a simpel hollowed out cube that is curved on one of the faces. The upper face of the cube contains a small slit that then open into the entire cube. The idea behind this design was to create a part that would be impossible to produce using traditional subtractive manufacturing methods. This was the final design I ended up with.

The design file and the STL-file for this can be foud [here](https://github.com/TillWege/dig-fab/tree/main/assignment%203) .


## Printing

<figure style="float: right">
    <img src="/df/df-3b.jpg" style="max-height: 200px" />
    <figcaption><p>3D Printer</p></figcaption>
</figure>

I printed the model on my SV-01 3D-Printer using PLA. The model is printed with a layerheight of 0.28mm and 20% of infill. The shell is printed with a wall thickness of 0.84mm. The print took about 70 minutes to complete. The printer was set to a bed temperature of 60°C and a nozzle temperature of 200°C. The printer was also set to use a brim to increase the surface adheasion to the bed.


## Result

<figure style="float: left">
    <img src="/df/df-3c.jpg" style="max-height: 200px; margin-right: 2rem" />
    <figcaption><p>Result</p></figcaption>
</figure>

The cube printed without any issues. The internal overhang on the top face posed no problem, as it was well within the capabilites of my 3D-printer. The surface finish of the part is not perfect, but this is probably due to my fillament having absored some moisture of the past months. The brim could be removed without any problems after printing.