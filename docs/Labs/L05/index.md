# L05 – Design a Snap Fit

## Modeling

The first thing needed was to research the material properties of PLA and choose dimensions.

<img width="397" height="121" alt="Screenshot 2026-09-22 002753" src="https://github.com/user-attachments/assets/05b448e1-9dff-4566-9159-784190a9e214" />

Next, a simple sketch of the part was made in order to gain a visual of what was needed. 

<img width="185" height="138" alt="Screenshot 2026-09-22 003039" src="https://github.com/user-attachments/assets/ab94ffc3-3df2-49c0-9805-3058b0794e27" />

I had chosen an outer clip to keep it simple and effective. The next thing to do was use the deflection equation for a transverse load to find the length of the beam.

<img width="412" height="146" alt="Screenshot 2026-09-22 003234" src="https://github.com/user-attachments/assets/76e5d048-4993-49e7-ace1-5ecb2b734ee8" />

The length of the beam was chosen to be 2.5 inches. The free body diagrams of each "cantilever beam" are shown below.

<img width="405" height="149" alt="Screenshot 2026-09-22 003748" src="https://github.com/user-attachments/assets/41678235-856b-4670-b6cb-6fcd714d6ed7" />

The stress calculations are shown below. This ensures none are above the max stress decided by the yield strength and safety factor. The amount of force applied did need to be changed to 1 instead of 2 pounds.

<img width="414" height="130" alt="Screenshot 2026-09-22 003836" src="https://github.com/user-attachments/assets/55e21047-8c12-484f-8053-1c9fa10f3fc3" />

<img width="443" height="184" alt="Screenshot 2026-09-22 003846" src="https://github.com/user-attachments/assets/3e84637b-a6db-4cbf-8844-fd57837fb5df" />

<img width="381" height="80" alt="Screenshot 2026-09-22 003850" src="https://github.com/user-attachments/assets/71f6d5e7-7bca-46b1-8805-6c9c46a56c8d" />

## Parametrically Design

To design parametrically, the variables were put into the global variables section as shown below.

<img width="805" height="218" alt="Screenshot 2026-09-21 111816" src="https://github.com/user-attachments/assets/9a421b14-b3c1-4e69-aed4-41d7c237cf23" />

These were then applied to the sketch from the top view of the outer part shown below.

<img width="1160" height="718" alt="Screenshot 2026-09-21 111757" src="https://github.com/user-attachments/assets/c153afc4-29ac-492a-8eec-59115b1a198a" />











## Sources

https://juggerbot3d.com/pla-filament-review/
