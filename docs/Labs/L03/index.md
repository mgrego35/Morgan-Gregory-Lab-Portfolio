# Lab #3: Design Something Small

## Design

The assignment was to design something small with the dimensions 1.5 in x 1.5 in x .5 in max (l x w x h). A friend of mine recently bumped her head and it left a slight bump, which I wanted to create a hat for.

## Research

In class we discussed infills along with brims and skirts. There are many different types of infills available on PrusaSlicer. The three I researched were gyroid, grid, and adaptive cubic. In all of the images below the same part is used at 15% infill to show the difference in print times, and to show how dense the infill looks.

Gyroid - This infill is mainly used when isotropic strength is needed. This means it has about the same strength no matter which side you test from. It both reduces printing material while keeping the strength as high as possible. One drawback of gyroid is the added print time, but it is well worth the strength for certain parts. It is also preferred due to less failing due to skipping between lines. A picture of gyroid from PrusaSlicer is shown below.

<img width="625" height="401" alt="Screenshot 2026-09-07 145913" src="https://github.com/user-attachments/assets/fa185238-d888-41b1-b44f-06bfedcd3b0e" />

Grid - This infill creates a grid of lines with squares in between. It gives good strength in certain directions and lacks strength in others, such as if you press in diagonally. It prints pretty fast without being too fast. Sometimes grid has been known to fail due to previous lines hitting the hot end. A picture of grid from PrusaSlicer is shown below.

<img width="600" height="394" alt="Screenshot 2026-09-07 150146" src="https://github.com/user-attachments/assets/cd064f21-8283-4882-b8ad-da69fa960be6" />

Adaptive Cubic - The adaptive cubic infill is like the cubic infill but it saves both print time and filament by leaving the middle of the print less dense than the outside parts. This is useful for larger prints where there is no need for a dense inside and less weight is needed.

<img width="637" height="411" alt="Screenshot 2026-09-07 150218" src="https://github.com/user-attachments/assets/94bec12b-57f9-4e73-86f2-57c8fce7820c" />

## Preprocessing

We chose the build orientation below because it grouped everything together to make the hot end not have to move far away from the center. My print did not need to be scaled because they were designed in SolidWorks with the exact dimensions intended for printing. 

References:

https://ultimaker.com/learn/mastering-3d-printing-infill-patterns-from-gyroid-to-lightning/

https://help.prusa3d.com/article/infill-patterns_177130

