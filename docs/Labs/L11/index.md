# A11 – Motor Selection

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

In order to make this a loose fit, I will be using .7200 inches as the diameter of the pen holes.

I started by creating a variable for the pen diameter in order to easily change it if reiteration is needed.

I then created a rectangular sketch with the dimensions shown below in order to create the main body and extruded it.













## References

https://uncc.instructure.com/courses/272053/pages/week-11-sla-designing-interlocking-parts?module_item_id=7944823
