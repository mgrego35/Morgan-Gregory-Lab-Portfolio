# Lab #4: Benchmark a Parameter

## Parameter

The parameter I decided to test was the tolerance of the printer. The given tolerance is plus or minus .3%, and to test this I will make 5 different lengths with the same square cross sections, and will test each of their lengths against the nominal length to find the percent shrinkage. The idea is to prove that our printer tolerances are around the given ones. The measurement will be taken with a calibrated Neiko digital caliper. My prediction is that +/- .3% is correct and it will be somewhere within that area.

## Document Design

I wanted to test the following lengths, .25 inches, .5 inches, 1 inches, 3 inches, and 5 inches. The cross sections of these will be .5 inches for the length and width in order to have a control.

I started by creating the platform, which is shown below. I made it 6 inches long and 3 inches wide. This decision came from the longest piece being 5 inches, which leaves about half an inch on both ends so it was not hanging off or flush. The width came from .5 inches on both sides, the 3 .5 inch cross sections, and 2 gaps in between of .25 inches each. The sketch for the base plate and the extrusion are shown in SolidWorks below.

<img width="633" height="385" alt="Screenshot 2026-09-10 123944 (2)" src="https://github.com/user-attachments/assets/40884d15-f87f-4266-80f0-a284589a6b81" />

<img width="639" height="293" alt="Screenshot 2026-09-10 124042" src="https://github.com/user-attachments/assets/6929c681-e00c-45d8-b398-5a0e1ac0a12a" />

<img width="596" height="282" alt="Screenshot 2026-09-10 124329" src="https://github.com/user-attachments/assets/94688c12-f63f-497f-bc05-d7e7ec163ece" />

Next I had to add the beams on the platform. Since they were all going to be the same height, I made the sketch shown below, including them all so they can have consistent dimensions. The final sketch and extrusion are shown below.

<img width="580" height="311" alt="Screenshot 2026-09-10 124956 (1)" src="https://github.com/user-attachments/assets/543f15be-ef0a-4a3c-a14f-e044b5dc194f" />

<img width="639" height="300" alt="Screenshot 2026-09-10 125053 (1)" src="https://github.com/user-attachments/assets/7e8c6baa-11ba-4b8e-8fcf-cbb95b5e2a6c" />

<img width="662" height="377" alt="Screenshot 2026-09-10 125141 (1)" src="https://github.com/user-attachments/assets/005d5846-719d-48a1-ad8a-74e50a9daf05" />

The final thing I needed was text explaining what it was. I wanted people to understand what the part was. I chose to add text in the middle of it as shown below.

<img width="733" height="366" alt="Screenshot 2026-09-10 125514" src="https://github.com/user-attachments/assets/42ef4be3-d35d-435b-aa33-a35f86315b4e" />

<img width="640" height="300" alt="Screenshot 2026-09-10 125701" src="https://github.com/user-attachments/assets/01627ec6-33af-4247-b7ba-e83283c06494" />

The finished model is found here: [L04_2156.zip](https://github.com/user-attachments/files/32214557/L04_2156.zip)

## Preprocessing

The settings were left relatively unchanged. The main things changed were the fill density and the fill pattern. This print did not need anything special like wall loops, skirts, or brims to be changed. The fill density we chose first was 10% as shown in the first image below, but it did not look solid enough for what I wanted, so it was changed to 15% instead, which is shown below that.

<img width="715" height="294" alt="Screenshot 2026-09-14 204649" src="https://github.com/user-attachments/assets/bafcd715-943e-4034-b750-83253bd18878" />

<img width="781" height="369" alt="Screenshot 2026-09-14 204711" src="https://github.com/user-attachments/assets/87a84cfc-4df2-43d7-9b51-0d33623fae21" />

<img width="736" height="284" alt="Screenshot 2026-09-14 204723" src="https://github.com/user-attachments/assets/e0a4f5d3-18c0-4a29-9667-8f0910c35c8d" />

<img width="780" height="369" alt="Screenshot 2026-09-14 204730" src="https://github.com/user-attachments/assets/e6774178-fa15-4ad3-845a-d7236c95acff" />

Below are the final images from the preprocessor, unsliced and sliced showing print times.

<img width="514" height="368" alt="Screenshot 2026-09-14 205045" src="https://github.com/user-attachments/assets/460c8cf9-fc01-42b4-a7cb-a233ba445521" />

<img width="777" height="370" alt="Screenshot 2026-09-14 205052" src="https://github.com/user-attachments/assets/d2dd766d-6982-4cfa-a16f-770dfd748e9b" />

## Print and Analysis

Below is a video of the print, and a picture of the final product.

<video controls width="320" src="https://github.com/user-attachments/assets/36627a1d-41b2-494c-a145-43b42bda06ee"></video>

<img width="534" height="310" alt="Screenshot 2026-09-14 211539" src="https://github.com/user-attachments/assets/deb5ccf3-07d9-456b-b2ce-2a655fbae726" />

The dimensions of the beams were as follows: .2495 in, .4980 in, .9970 in, 2.9885 in, and 4.9835 in

The percent errors were found using the equations below, and averaged up. This must be done because it is a percentage and varies by length.

<img width="525" height="106" alt="Screenshot 2026-09-14 212108" src="https://github.com/user-attachments/assets/29161c4b-1e16-486c-bff5-90a9a16fe574" />

<img width="523" height="113" alt="Screenshot 2026-09-14 212211" src="https://github.com/user-attachments/assets/95b888b6-8585-41c3-8d27-ad70dd04cf82" />

<img width="523" height="109" alt="Screenshot 2026-09-14 212230" src="https://github.com/user-attachments/assets/7f71823c-ea21-4d6e-b67a-d395fd1cd19f" />

<img width="521" height="110" alt="Screenshot 2026-09-14 212426" src="https://github.com/user-attachments/assets/7780e523-63ef-4a73-a6ae-8bce1b86b328" />

<img width="521" height="112" alt="Screenshot 2026-09-14 212352" src="https://github.com/user-attachments/assets/ee4c5608-e68d-4ecf-919e-1b91529c3038" />

<img width="527" height="120" alt="Screenshot 2026-09-14 212432" src="https://github.com/user-attachments/assets/07174a12-9ebd-4067-9ace-a2159e7ec69f" />

Thus, the average shrinkage in length was .322% of the whole length. This is right on point to where it should be.

## Lessons Learned

The outcome of this lab was just as I had expected. It was right around .3% of the length and the average was only slightly off. It matched the expected from the sheet but it was a little under what I the shrinkage calculator predicted. I did learn that there is no difference in the percent shrinkage if it is bigger. The shrinkage will be bigger but the percentage will likely stay on point. The highest was .5 inches with a .4% shrinkage while the 5 inch one only had a .33% shrinkage. This project took about 5 hours to finish.

## Resources

[PL_3DP_Design_Rules_EN (1).pdf](https://github.com/user-attachments/files/32218913/PL_3DP_Design_Rules_EN.1.pdf)

https://grandpacad.com/en/tools/material-shrinkage-calculator
