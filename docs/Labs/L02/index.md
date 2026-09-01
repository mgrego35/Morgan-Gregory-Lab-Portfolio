# L02 – Print Something Small

## In-Class Research

DfAM - Focused on minimizing material while maximizing efficiency within a design. Subtractive manufacturing the smaller design details to minimize material do not matter as much because the excess will likely be scrapped.

FDM - The grid infill can sometimes fail due to the crossing lines. Gyroid infills are a good substitute as they also provide structural soundness in all directions.

Small Group Share Out - When doing bridges between parts supports are needed. Overhangs can be avoided by using supports or orienting the print better.

## The Assignment

The assignment given was to find a file to print on the website given (https://www.printables.com/) and use PrusaSlicer to convert it from an STL file to a gcode file. We then had to use the FDM printers in the lab to print the preprocessed file. The part requirements were no more than 2 in x 2 in x .25 in (LxWxH), have a print time smaller than 1.5 hours which was changed to around 10-20 minutes during the actual lab session, and we had to get with 2-3 people to print together. 

## Download

The first design chosen was a small cylinder bowl shape shown below. The goal with this was to have a small area to place my mini screws for my shaft collars at home. I thought the open design would make it easier to get parts when I need them without having to worry about taking a cover mechanism off.

<img width="1837" height="765" alt="Screenshot 2026-08-29 235610" src="https://github.com/user-attachments/assets/2bd1c5c1-c60c-4d76-aec3-1bcd68260149" />

The shortcoming with this design is that the open lid design seemed like a bad idea alongside the relative shape of the inside felt like it would not hold enough because of the wasted space.

I began looking for a second design that was similar in that it was a cylindrical shape with a lid and a thinner walls for more space for the collar screws and found the final design below.

<img width="1842" height="780" alt="Screenshot 2026-08-29 235303" src="https://github.com/user-attachments/assets/8061dc54-ec38-4fa3-b082-35f58b83f642" />

This design fulfilled the shortcomings of the first design.

Design 1: https://www.printables.com/model/818357-small-cylinder-type-bowl

Final Design: https://www.printables.com/model/430109-cylinder-container-for-small-items/files

## Preprocessing

In PrusaSlicer, we were required to group with 2-3 other people on one build plate. Lexie Cox and Ethan Cornett were my two groupmates. Our build plate finalized is shown below. The plate was arranged with all the parts towards the center grouped up because it is convenient so that the extruder does not have to be moved across the plate every time a layer is added. 

<img width="1206" height="758" alt="Screenshot 2026-08-31 191637" src="https://github.com/user-attachments/assets/9860b85b-c7d6-46c7-9e02-a88d2c491543" />

The print dd not have supports as there was nothing that required supports to print, including overhangs or bridging. The different files had to all be scaled differently. My print was scaled down to only 2.67% of the original size, as shown below, while some others had to be scaled up.

<img width="477" height="282" alt="Screenshot 2026-08-31 190905" src="https://github.com/user-attachments/assets/440f39c4-74c6-4542-9ef4-f031091848e3" />

One possible mistake we made in the preprocessing stage was scaling things down too much because it caused the area of the pieces to not necessarily fit together properly, but this will be discussed in more detail in the lessons learned section.

The final, sliced image is shown below.

<img width="1917" height="913" alt="Screenshot 2026-08-31 212605" src="https://github.com/user-attachments/assets/3585e056-37ae-430a-9458-5301a79a6217" />

## Print

The printer used was printer 5. Pictures and a video of the process are shown below.

<video controls width="320" src="https://github.com/user-attachments/assets/34f1ccc7-a894-4e30-aa55-56b516216181">

<img width="758" height="1008" alt="IMG_3887" src="https://github.com/user-attachments/assets/2e7fb2b2-f25c-41b2-84eb-879c71e3f1d5" />

<img width="758" height="1008" alt="IMG_3888" src="https://github.com/user-attachments/assets/8f9a0ced-d717-437a-b18b-2b8067f8088f" />

## Lessons Learned

The first thing I learned was about rapid cooling. Since the print plate did not have enough time to cool down before we pulled it out, being exposed to the air on all sides likely shrunk the part on the outside faster than the inside. The second thing I learned was about bridging which Lexie said required supports to be made between parts to prevent the floating bridges. The third thing I learned was printing orientation can largely affect whether or not a print turns out alright or not. If it is oriented correctly it can make it much easier instead of requiring supports. The last thing I learned was about the scale tool changing radius means it changes the area of a circle differently. A fit can be ruined like in my part, having too much wiggle room because the scaling tool has a big effect in the end.

## Sources

Design 1: https://www.printables.com/model/818357-small-cylinder-type-bowl

Final Design: https://www.printables.com/model/430109-cylinder-container-for-small-items/files




