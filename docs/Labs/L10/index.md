# L10 - RC2 Sliding Fit Design and Verification

## Research and Planning

The first step was to research RC2 sliding fits in machinerys handbook.

<img width="845" height="493" alt="Screenshot 2026-11-02 105500" src="https://github.com/user-attachments/assets/b275182b-f142-4e36-92ff-9b468e84b0d8" />

Hole width = 1.200 inches

So clearance is 1.4 thousandths of an inch, tolerance for the shaft is upper limit -.4 thousandths and lower limit -.8 thousandths., and the tolerance for the hole is upper limit +.6 thousandths and lower limit 0 thousandths of an inch.

The sketch I made of my idea is shown below.

<img width="326" height="201" alt="Screenshot 2026-11-02 190844" src="https://github.com/user-attachments/assets/df70310e-2ea4-449a-ac34-dd26fb5024c0" />

In a real world engineering application, an RC2 sliding fit would be somewhere that can turn but not turn freely or be loose. An example application would be something like a toolholder for a machining process. There should be almost no play.

## CAD Design

### Hole Design

To begin, I started by designing the hole part. I started by creating a sketch of a circle with a 1.5 inch diameter and extruded it by 3.150 inches in order to leave room for .150 inches of wall thickness everywhere.

<img width="642" height="387" alt="Screenshot 2026-11-02 110335" src="https://github.com/user-attachments/assets/26143eca-ed36-4f98-a7e1-1f2c3638b2d1" />

<img width="1597" height="841" alt="Screenshot 2026-11-02 110701" src="https://github.com/user-attachments/assets/fff193cf-fc9b-41fb-8e8e-a2ee459034ee" />

I then added a 1.2 inch diameter hole with the tolerances given from the RC2 sliding fit. I used the extruded cut feature to cut 3 inches into the part.

<img width="896" height="541" alt="Screenshot 2026-11-02 111242" src="https://github.com/user-attachments/assets/1e878153-9c78-4a59-b448-bcd5de2eda5a" />

<img width="360" height="337" alt="Screenshot 2026-11-02 111313" src="https://github.com/user-attachments/assets/e8c55d4b-7b69-40aa-a306-2f2a64d04026" />

I then realized that this would be way too much volume and shifted focus to making something that could hold a single pill or 2 pills. I changed the length to 1.1 inches.

<img width="770" height="461" alt="Screenshot 2026-11-02 113601" src="https://github.com/user-attachments/assets/f69c5332-654c-48ef-b062-c6c946848927" />

Final image shown below.

<img width="702" height="375" alt="Screenshot 2026-11-02 113954" src="https://github.com/user-attachments/assets/195371b5-2d90-4a0f-bea5-954c7241e8ad" />

### Shaft Design

To begin the shaft design I created a circular sketch with the shaft dimensions which is shown below. I extruded it by .5 inches as shown below.

<img width="778" height="557" alt="Screenshot 2026-11-02 111727" src="https://github.com/user-attachments/assets/99eaadc6-c2f8-405c-973a-13751cc60a3c" />

<img width="1592" height="832" alt="Screenshot 2026-11-02 111855" src="https://github.com/user-attachments/assets/1bc2f69e-a317-47d8-a129-602c0a10f96e" />

I then made a cap for the shaft shown below.

<img width="920" height="472" alt="Screenshot 2026-11-02 114358" src="https://github.com/user-attachments/assets/40acff29-6208-4dd8-8c39-81b25dadabba" />

Final piece shown below.

<img width="1592" height="782" alt="Screenshot 2026-11-02 114521" src="https://github.com/user-attachments/assets/7843eecc-cd47-4036-9c1e-a813040bfda1" />

## Preprocessing for 3D printing

The preprocessing software used, Preform, includes a one click setup feature that automatically orients your prints to minimize material use for support and more. The holes needed to be added to my part to prevent cupping. Device name was MatureImpala. The only thing changed was a layer height of .05 mm. Total volume for all 3 prints was 31.15 mL.

<img width="1917" height="1018" alt="Screenshot 2026-11-02 114619" src="https://github.com/user-attachments/assets/24234c2d-d12f-4a48-a051-e052521f2f93" />

<img width="1911" height="965" alt="Screenshot 2026-11-02 122526" src="https://github.com/user-attachments/assets/fd84964a-3dec-4a1f-a6d2-2adfdd7be3b7" />

## Post Processing

The first process was to use the scrapers and removal tools to remove the part from the build plate and then remove the supports.

<img width="418" height="560" alt="Screenshot 2026-11-03 120633" src="https://github.com/user-attachments/assets/ed9ed0ae-415f-456a-b5ee-08f7c9637e13" />

The second process was using an alcohol bath to wash the part.

<img width="416" height="557" alt="Screenshot 2026-11-03 120643" src="https://github.com/user-attachments/assets/9b198209-570f-4964-acce-d74c8af53a62" />

The last step was to put the parts in a curing oven.

<img width="415" height="562" alt="Screenshot 2026-11-03 120651" src="https://github.com/user-attachments/assets/5ee0f555-368c-40f8-9823-28028dcbd596" />

Deviations were significant from nominal values. around .005 inches.

## Fit Test

Measured diameter of 1.182 inches for the shaft and 1.195 inches for the hole. The parts have good enough clearance to slide without forcing it, and they stay together, and do not have very much play at all. These are significantly different than the allowed tolerances.

<img width="362" height="338" alt="Screenshot 2026-11-03 005333" src="https://github.com/user-attachments/assets/ba931668-7e74-4ae6-b79b-823f28cd8437" />

## Lessons Learned

The main lesson I learned in this lab is that SLA printing can result in larger shrinkage than FDM and needs to be accounted for as it can ruin dimensions. Curing made it much tighter and required a tiny bit of sanding. Next time I can design for the shrinkage by adding an extra 1-2% to each critical dimension.

Total time spent: 5 hours

## References

https://www.rexresearch1.com/MathFormulaHandbooksLibrary/MachinerysHandbkOBERG.pdf
