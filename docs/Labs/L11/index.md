# A11 – Snap Fit with SLA

## Objective

Design and 3D print a small artifact composed of two or more parts that snap together using the Form 4 SLA printer.
The goal is to design, test, and document a functional snap fit while understanding how material properties, tolerances, and printer settings affect assembly performance and durability.

You may design any small artifact, provided that:

It demonstrates a working snap fit between two or more components.

It is not just a plain test block; the design must be creative and/or useful (e.g., a small enclosure, clip, latch, hinge, or functional connector).

2–3 student projects will share one build plate.

## Research

Cantilever snap fits require deflection based off of a cantilever beam and then return to their original shape. Release is allowed by pressing inwards on the cantilever in order to stop the prevention of the release. Below is an example of a free body diagram for a cantilever snap fit. The deflection can be calculated by using a derivation or a formula.

<img width="470" height="285" alt="Screenshot 2026-11-06 215930" src="https://github.com/user-attachments/assets/dd94997f-767a-43f6-9007-b9e7b4fd9a84" />

SLA modulus of elasticity for Grey V5 resin are very similar to PLA, which results in similar levels of deflection to the previous lab.

## CAD Design

My design is a cantilever snap fit. It will have the cantilever side on one side and the indented side on another, in order to be able to print multiple of the same part. This will be a pen stand for my fountain pens to sit on my desk. 

I began by taking the measurements on all of my pens. The largest diameter was taken and this is to find the right fit for the top. The largest diameter is to be used. The measurements were taken with a Neiko digital caliper.

Lamy Safari: .7140 inches

Ellington Emerald Enigma: .6790 inches

Scriveiner Classic Silver Chrome: .6055 inches

Largest Diameter: .7140 inches

In order to make this a loose fit, I will be using .7200 inches as the diameter of the pen holes. The resin being used, grey v5, has a shrinkage max of around 1.5% and this will give us room so that we still have plenty of room for error.

I started by creating a variable for the pen diameter in order to easily change it if reiteration is needed.

<img width="919" height="35" alt="Screenshot 2026-11-07 204139" src="https://github.com/user-attachments/assets/fe1316c0-a50d-44a7-adc3-3015924781ca" />

I then created a rectangular sketch with the dimensions shown below in order to create the main body and extruded it.

<img width="679" height="394" alt="Screenshot 2026-11-07 204249" src="https://github.com/user-attachments/assets/056978ed-ab73-4ad0-8b44-36390ecfe567" />

<img width="1588" height="871" alt="Screenshot 2026-11-07 204329" src="https://github.com/user-attachments/assets/ba422bb5-69ae-455c-a334-3ebbe55d57a8" />

Next I created what will be the pen hole in a sketch and used the extruded cut feature to remove all of the material. The diameter variable was applied to the sketch. A centerline was used to line up the middle of the sketch. 

<img width="800" height="504" alt="Screenshot 2026-11-07 204825" src="https://github.com/user-attachments/assets/5d4a0cfc-917a-4202-9a50-ecdb13dc7385" />

<img width="1917" height="842" alt="Screenshot 2026-11-07 204926" src="https://github.com/user-attachments/assets/69ef9762-4b67-46b1-ba71-1773e807219f" />

I then realized a slightly higher tolerance is necessary, and decided to make the value of D .730 inches instead of .720. This will account more for the shrinkage.

<img width="802" height="485" alt="Screenshot 2026-11-07 205611" src="https://github.com/user-attachments/assets/2491a351-582f-4a78-a8ea-1a11e2390e9d" />

Then I created the sketch for the cantilever side. The cantilever snap fit will not have a large deflection, instead, it will be closer together in order to create a tighter fit with less deflection.













## References

https://uncc.instructure.com/courses/272053/pages/week-11-sla-designing-interlocking-parts?module_item_id=7944823
