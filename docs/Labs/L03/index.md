# Lab #3: Design Something Small

## Design

The assignment was to design something small with the dimensions 1.5 in x 1.5 in x .5 in max (l x w x h). A friend of mine recently bumped her head and it left a slight bump, which I wanted to create a hat for.

The first step was to create the cross sectional geometry for half of the hat shown below. The dimensions given are in inches.

<img width="497" height="326" alt="Screenshot 2026-09-08 120125" src="https://github.com/user-attachments/assets/4f887ed5-05d5-4879-91f9-974d9048bb88" />

The next step was to add a larger circular extruded cut into the hat. The dimensions of the whole are shown below in inches.

<img width="557" height="326" alt="Screenshot 2026-09-08 120237" src="https://github.com/user-attachments/assets/9ca21c82-bbfc-4c36-8107-fe033e63b1ce" />

The final step is to create a smaller extruded cut in order to fit the top of the bump. The dimensions given below are in inches.

<img width="670" height="642" alt="Screenshot 2026-09-08 120250" src="https://github.com/user-attachments/assets/2954d7a7-22f9-4794-93a3-d4536571c219" />

## Research

In class we discussed infills along with brims and skirts. There are many different types of infills available on PrusaSlicer. The three I researched were gyroid, grid, and adaptive cubic. In all of the images below the same part is used at 15% infill to show the difference in print times, and to show how dense the infill looks.

Gyroid - This infill is mainly used when isotropic strength is needed. This means it has about the same strength no matter which side you test from. It both reduces printing material while keeping the strength as high as possible. One drawback of gyroid is the added print time, but it is well worth the strength for certain parts. It is also preferred due to less failing due to skipping between lines. A picture of gyroid from PrusaSlicer is shown below.

<img width="625" height="401" alt="Screenshot 2026-09-07 145913" src="https://github.com/user-attachments/assets/fa185238-d888-41b1-b44f-06bfedcd3b0e" />

Grid - This infill creates a grid of lines with squares in between. It gives good strength in certain directions and lacks strength in others, such as if you press in diagonally. It prints pretty fast without being too fast. Sometimes grid has been known to fail due to previous lines hitting the hot end. A picture of grid from PrusaSlicer is shown below.

<img width="600" height="394" alt="Screenshot 2026-09-07 150146" src="https://github.com/user-attachments/assets/cd064f21-8283-4882-b8ad-da69fa960be6" />

Adaptive Cubic - The adaptive cubic infill is like the cubic infill but it saves both print time and filament by leaving the middle of the print less dense than the outside parts. This is useful for larger prints where there is no need for a dense inside and less weight is needed.

<img width="637" height="411" alt="Screenshot 2026-09-07 150218" src="https://github.com/user-attachments/assets/94bec12b-57f9-4e73-86f2-57c8fce7820c" />

## Preprocessing

We chose the build orientation below because it grouped everything together to make the hot end not have to move far away from the center. My print did not need to be scaled because they were designed in SolidWorks with the exact dimensions intended for printing. The infill I used was the gyroid infill. I used it mainly to give good supports even though the piece was so small. I did not change the wall thickness, because wall thickness is mainly changed to add strength to an object. There were no real mistakes so far that were noticeable. The final build plate is shown below along with the times and sizes and details given from PrusaSlicer.

<img width="697" height="645" alt="Screenshot 2026-09-08 120627" src="https://github.com/user-attachments/assets/7a3b82fc-b840-4f95-b9f3-877b0e3fb52f" />

<img width="637" height="636" alt="Screenshot 2026-09-08 120752" src="https://github.com/user-attachments/assets/67f01b8d-6849-4744-bc29-71021e9136b2" />

<img width="633" height="373" alt="Screenshot 2026-09-08 120741" src="https://github.com/user-attachments/assets/fc9d1643-d8b0-4179-9e89-382a4f3d15f2" />

<img width="912" height="258" alt="Screenshot 2026-09-08 120715" src="https://github.com/user-attachments/assets/0d6124a5-9616-45b3-a337-98a9c272f53b" />

<img width="882" height="342" alt="Screenshot 2026-09-08 120725" src="https://github.com/user-attachments/assets/16a49d6c-af9b-4a0b-b1db-f023d955bfdc" />

## Print

The finished print along with a video are shown below.

<img width="605" height="806" alt="unnamed" src="https://github.com/user-attachments/assets/4508ddbd-aeaf-4b08-8f1c-aebdf5cfc825" />

<video controls width="320" src="https://github.com/user-attachments/assets/74edb933-4561-4e6e-b49d-4f1436577aaa"></video>

## Lessons Learned

This project took me a total of around 5 hours of work to finish. I think that the greatest lesson learned throughout the project was to not design things that do not have the thickness to be printed properly. The inside of my hat did not have proper thickness and it was too thin to stick together. If this were a more critical part and I did not use the proper wall thickness, the part would likely crack or break very easily and it would fail at its task. I did not catch any mistakes until the end when I realized the part was too thin towards the middle of the hat. One item where thickness is taken into account is the Rubix Cube. These cubes are not meant to be heavy and if they had 100% infill they would be more annoying to use or be quick with. 

## References:

https://ultimaker.com/learn/mastering-3d-printing-infill-patterns-from-gyroid-to-lightning/

https://help.prusa3d.com/article/infill-patterns_177130

Solidworks Part: 



