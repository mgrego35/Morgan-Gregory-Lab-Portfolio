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

It was then extruded by the width being .25 inches. This was after being fixed properly.

<img width="971" height="609" alt="Screenshot 2026-09-21 112336" src="https://github.com/user-attachments/assets/c374b311-9409-455f-9cce-5c26b6e77473" />

<img width="959" height="498" alt="Screenshot 2026-09-21 112417" src="https://github.com/user-attachments/assets/faa2a237-6983-457c-81cb-3f051dbf6d05" />

Fillets were added for both clean looks and extra assurance that the beam would not fail at the 90 degree angle.

<img width="540" height="406" alt="Screenshot 2026-09-21 113011" src="https://github.com/user-attachments/assets/5e9906dc-8338-4358-9f83-4e9fa328322b" />

The same process was done below with the inner piece.

<img width="869" height="543" alt="Screenshot 2026-09-21 114822" src="https://github.com/user-attachments/assets/cebd4009-36f6-4224-9371-32875fdcfee3" />

<img width="959" height="426" alt="Screenshot 2026-09-21 114849" src="https://github.com/user-attachments/assets/cf23c6b2-3ff3-4bc9-aab1-19749547fa30" />

<img width="795" height="568" alt="Screenshot 2026-09-21 115239" src="https://github.com/user-attachments/assets/8b820e1c-229a-4d6c-93db-ae98d8d26da9" />

Outer CAD File: [Outer.zip](https://github.com/user-attachments/files/32497368/Outer.zip)

Inner CAD File: [Inner.zip](https://github.com/user-attachments/files/32497371/Inner.zip)

## Preprocessing

For preprocessing, not much was changed other than the gyroid infill was used for 15%. This was used because it offers good strength in all directions and it is simple without crossing lines as much. The final plate is shown below along with times and other details.

<img width="534" height="194" alt="Screenshot 2026-09-21 120059" src="https://github.com/user-attachments/assets/b27e3d11-047d-4a9d-a910-960466e26092" />

<img width="1053" height="647" alt="Screenshot 2026-09-22 005431" src="https://github.com/user-attachments/assets/a0fab7a2-b2e9-470f-8d9a-d80ebd8b05c9" />

A video of the print is shown below, along with a final photo.

<img width="340" height="471" alt="Screenshot 2026-09-22 005638" src="https://github.com/user-attachments/assets/72f5b6f3-efac-4685-9155-b217308942cf" />

<video controls width="320" src="https://github.com/user-attachments/assets/8d2e734b-be59-470d-9ce6-3aabc6f0607c"></video>

## Sources

https://juggerbot3d.com/pla-filament-review/
