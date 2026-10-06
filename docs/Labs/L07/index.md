# A7 – Linkage Mechanisms

## The Assignment

The assignment given was to create a linkage mechanism that performs a designed task. Hardware is allowed but all functional parts must be printed.

## Research

Linkage 1: Flapping Wing Mechanism

https://mechanicaldesign101.com/2017/05/05/flapping-wing-mechanism/

The mechanism shown above is a flapping wing design that allows for more efficient flight with wings. This design uses the linkages shown in the images below to flap the wings in a cyclical way, ensuring even flaps every time.

<img width="763" height="339" alt="Screenshot 2026-10-03 192314" src="https://github.com/user-attachments/assets/7d779a4e-efa1-4e75-a0ed-57c3c84ab967" />

<img width="750" height="344" alt="Screenshot 2026-10-03 192333" src="https://github.com/user-attachments/assets/4c951469-373d-4127-a4f5-a753315fa5d3" />

Linkage 2: XStrings Multi-Directional Tentacle Actuation

https://hcie.csail.mit.edu/research/xstrings/xstrings.html

The mechanism shown in the images below uses strings and certain angles on the linkages to allow for bending in multiple directions.

<img width="875" height="476" alt="image" src="https://github.com/user-attachments/assets/45e838fe-e200-4c5d-a7c1-a1d9463d85d6" />

## Design

The thing I wanted to design was a simple scissor lifting mechanism. I am going to make a box at home that opens using a scissor lifting mechanism in order to lift different layers instead of having one top that opens. 

To begin, I needed to design the scissor beams. I began with a 5 in x 1 in rectangular sketch, then after extruding it by .250 in, I decided it needed to be changed to 6 in x 1 in so that there is more distance between the points, resulting in more height.

<img width="1073" height="476" alt="Screenshot 2026-10-04 203412" src="https://github.com/user-attachments/assets/567f22cf-461f-40cf-bf45-0f7a47653ae3" />

<img width="1916" height="888" alt="Screenshot 2026-10-04 203523" src="https://github.com/user-attachments/assets/a640b4fd-45ac-4f86-9a3c-185c04bfa4d9" />

<img width="1192" height="504" alt="Screenshot 2026-10-04 203542" src="https://github.com/user-attachments/assets/6554d7b5-1c92-433c-8fa6-348e916131ac" />

The next step was to add centerlines and use them to add the screw type that I use (M3 Socket heads) using the hole wizard. Hole wizard settings also shown below.

<img width="1489" height="599" alt="Screenshot 2026-10-04 203944" src="https://github.com/user-attachments/assets/e7d6ed72-9d12-446d-bf12-752322daa2aa" />

<img width="1376" height="559" alt="Screenshot 2026-10-04 204140" src="https://github.com/user-attachments/assets/7a5d6df0-bfe1-4b2b-bf24-83428d75e716" />

<img width="208" height="496" alt="Screenshot 2026-10-04 204159" src="https://github.com/user-attachments/assets/342ec577-e2f2-4671-ab61-c6f352d58dc7" />

<img width="952" height="267" alt="Screenshot 2026-10-04 204457" src="https://github.com/user-attachments/assets/7caf2ad2-6899-4bd4-8f7f-f72f6152555c" />

Lastly for the scissor beams I decided to fillet the edges (.1 in) in order to remove sharper edges.

<img width="241" height="242" alt="Screenshot 2026-10-04 204605" src="https://github.com/user-attachments/assets/38465da3-02fe-48ca-bee2-403265be888d" />

When creating the slider, I originally thought making a double sided lid would actually be a good idea, but really this was just a test of an idea. I began by creating the top of the lid which I made to be a 6 in x 6 in square sketch and extruded it by .25 in. I decided it needed to have about .5 in more than the beams did however so I upped it to 6.5 in.

<img width="1128" height="724" alt="Screenshot 2026-10-05 122219" src="https://github.com/user-attachments/assets/6139b148-5b75-46cd-a8f6-bc99706bd19d" />

<img width="1200" height="566" alt="Screenshot 2026-10-05 122233" src="https://github.com/user-attachments/assets/346dc798-0c4e-499d-abd1-f37b0114d8d8" />

<img width="749" height="632" alt="Screenshot 2026-10-05 122647" src="https://github.com/user-attachments/assets/dcb36331-f78b-42f6-8379-b9ce842348ba" />

I then made the sketch and extrusion for the rectangles that would become the sliders.

<img width="940" height="595" alt="Screenshot 2026-10-05 123154" src="https://github.com/user-attachments/assets/62b8eb98-9c11-4cb9-b0fb-49dc62992eac" />

<img width="1520" height="546" alt="Screenshot 2026-10-05 123520" src="https://github.com/user-attachments/assets/253a5c6a-d474-4885-b0ba-89917a1a187f" />

This was around the time I decided to make only one slider as a beam so I deleted all but one rectangle and added the extra length to it.

<img width="612" height="645" alt="Screenshot 2026-10-05 124115" src="https://github.com/user-attachments/assets/41ffe12c-0fac-47bf-b35c-f3ce6e5ddd36" />

<img width="1041" height="622" alt="Screenshot 2026-10-05 124243" src="https://github.com/user-attachments/assets/f77ce069-5d34-4eb3-949a-c12311626e78" />

Finally for the slider, I added the sketch shown below and the extruded cut to get the final piece.

<img width="1197" height="434" alt="Screenshot 2026-10-05 124321" src="https://github.com/user-attachments/assets/c3bd4766-e0f4-44f4-a238-b7b7cb87cb31" />

I also tried to make a spacer shown below, it was a simple hollow cylinder.
<img width="850" height="696" alt="Screenshot 2026-10-05 125045" src="https://github.com/user-attachments/assets/b0d4da84-c73d-4aeb-b4c1-992c4ad08306" />

<img width="1916" height="863" alt="Screenshot 2026-10-05 125102" src="https://github.com/user-attachments/assets/88063ba7-fe27-4979-b6e2-01760a712fb3" />

For this simple fit I chose .05 in of added tolerance for all the screw holes.

Final Parts Files List here:

[ScissorBeams.zip](https://github.com/user-attachments/files/33114325/ScissorBeams.zip)

[TestSlider.zip](https://github.com/user-attachments/files/33114329/TestSlider.zip)

[Spacer.zip](https://github.com/user-attachments/files/33114335/Spacer.zip)

## Preprocessing

Pictures of the preprocessing stage are shown below. Not much was needed other than changing orientation, adding supports, changing to 5% gyroid infill, and changing the perimeters to 4. I changed the perimeters because screw holes can be risky sometimes and I wanted some extra shear strength to my part.

<img width="507" height="183" alt="Screenshot 2026-10-05 125540" src="https://github.com/user-attachments/assets/9dbeaf46-9647-468e-98aa-3e6ae66b2831" />

<img width="475" height="182" alt="Screenshot 2026-10-05 125555" src="https://github.com/user-attachments/assets/10f45915-0dc2-466d-9015-0d8693d32b4f" />

<img width="675" height="166" alt="Screenshot 2026-10-05 125837" src="https://github.com/user-attachments/assets/dd9a9130-736e-467d-9c1b-adb8828716b9" />

<img width="749" height="549" alt="Screenshot 2026-10-05 125959" src="https://github.com/user-attachments/assets/1af125bd-1e69-4beb-8891-5c362be56f87" />

<img width="373" height="352" alt="Screenshot 2026-10-05 130004" src="https://github.com/user-attachments/assets/dce02b8b-6e4b-4d46-897c-bf541681c9be" />

## Printing

I printed on printer number 12 and the printing process is shown below.

<img width="498" height="665" alt="Screenshot 2026-10-06 114412" src="https://github.com/user-attachments/assets/a11daf76-fa5d-400e-9d0f-3525db1d1281" />

<video controls width="320" src="https://github.com/user-attachments/assets/4b32ba19-707e-44c8-9186-58b3ee49ecab"></video>

Final assembly shown here:

<img width="446" height="292" alt="Screenshot 2026-10-06 114417" src="https://github.com/user-attachments/assets/93704eeb-f6f6-4b03-9316-c44799260bfd" />

<img width="482" height="471" alt="Screenshot 2026-10-06 114422" src="https://github.com/user-attachments/assets/a594cd33-bdb1-474c-b414-11545132ad9c" />

## Lessons Learned

This project has taught me a great deal. The first and foremost important lesson was to always check the printer. I did not get a picture unfortunately but the filament spool got caught up/tangled and it caused the extruder to not pull properly, ruining my first print and wasting time. The second major lesson was to always take into account smaller pieces may have to use different tolerances because they may not print the same as bigger pieces. The spacer did not work out and I had to use washers to cover the gap.

## References

- https://mechanicaldesign101.com/linkage-designs/

- https://mechanicaldesign101.com/2017/05/05/flapping-wing-mechanism/

- https://hcie.csail.mit.edu/research/xstrings/xstrings.html
