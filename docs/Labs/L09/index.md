# L09 - Laser Cutter

## Objective

The objective is to design, laser cut, assemble, and document a parametric construction kit that accounts for laser cutter kerf. What you build is up to your team. The kit must include 3 unique part types, one press fit, slot fit, or tab fit connection, and 8 total parts.

My group consisted of Lexie Cox, Ethan Cornett, and I.

## Design

### Measuring the Material Thickness

Took 3 different sheets of the same kind we are going to cut. Measurements shown below:

t<sub>1</sub> = .105 inches

t<sub>2</sub> = .108 inches

t<sub>3</sub> = .107 inches

t<sub>average</sub> = .107 inches = 2.718 mm

### Measuring the Kerf

Kerf is material the laser burns away when cutting. It may be a very small amount but it matters in certain contexts like tight fits. To measure kerf, we began by cutting out a  x 20 mm square out of the wooden sheet. This will allow us to find the ideal minus the actual, giving us the kerf.

D = 20 mm

<img width="307" height="158" alt="Screenshot 2026-10-27 115542" src="https://github.com/user-attachments/assets/4c5b5be8-d2c5-4935-96ad-1b5f7987152f" />

x direction - 20 mm - 19.90 mm = .10 mm

y direction - 20 mm - 19.98 mm = .02 mm

### Fit Test

For the fit test, I created a shape like the one below and changed the top left corner to the origin coordinates in order to get a good starting place. I then moved points one by one relative to each other in order to get the dimensions I wanted.

<img width="844" height="429" alt="Screenshot 2026-10-26 121556" src="https://github.com/user-attachments/assets/30a22207-7f3c-47e8-9c81-c6121c99032c" />

There were 3 fits to make, a tight fit, a target fit, and a loose fit. I began with the tight fit using the calculations below, where K is the kerf and D is the clearance or distance between the pegs.

Tight Fit: D = t<sub>average</sub> + x<sub>0</sub> - K<sub>x</sub> - .05 mm

For the tight fit this turned out to be D = 2.718 mm + 10 mm - .10 mm - .05 mm = 12.568 mm

<img width="712" height="343" alt="Screenshot 2026-10-26 123234" src="https://github.com/user-attachments/assets/0ea4552e-46ef-4dc1-87fe-69a00aaeafe3" />

The 10 mm space is shown in the picture above. Then I started the normal fit shown below.

Normal Fit: D = t<sub>average</sub> + x<sub>0</sub> - K<sub>x</sub>

For the normal fit this became D = 2.718 mm + 22.568 mm - .10 mm = 25.186 mm

<img width="682" height="335" alt="Screenshot 2026-10-26 123510" src="https://github.com/user-attachments/assets/226dd90e-fcef-464c-9af1-c24d156e75f7" />

Then I added the next 10 mm space, and did the loose fit calculations, this time ADDING .05 mm to the fit.

Loose Fit: D = t<sub>average</sub> + x<sub>0</sub> - K<sub>x</sub> + .05 mm

For the loose fit this came out to be D = 2.718 mm + 35.186 mm - .10 mm + .005 mm = 37.809 mm

I added the loose fit dimensions and then added the 10 mm final piece. 

<img width="778" height="401" alt="Screenshot 2026-10-26 123539" src="https://github.com/user-attachments/assets/b8e2500b-c897-4b83-8c4c-2f05c77cdc0f" />

<img width="517" height="396" alt="Screenshot 2026-10-26 123847" src="https://github.com/user-attachments/assets/d171377d-6d56-45ec-b7d4-7d01f0d96ff1" />

Finally I added the y values, which were relatively unimportant due to the y clearance not being a factor in the fit. I gave it 20 mm deep and 10 mm of a barrier at the bottom. Final part is shown below.

<img width="417" height="206" alt="Screenshot 2026-10-26 124236" src="https://github.com/user-attachments/assets/0cdf7cee-97d0-44c2-ab20-fd3227eccf08" />

### Choosing the Clearance

The fit test showed that the best clearance was between the 0 and .005 mm range. The chosen clearance was .002 in order to balance having too much clearance and too little. This will allow the parts to fall in with only minor pressure but will prevent them from falling apart easily.

### Designing the Final Cut

To begin the final cut I decided to add my parameters into SolidWorks.

<img width="923" height="146" alt="Screenshot 2026-10-26 173625" src="https://github.com/user-attachments/assets/4530dd92-8a7b-49d8-810a-d335219a35e9" />

Next I created a sketch for the square shaped piece to be designed, which is shown below, after I put the parameters and equations in. I made sure all side lengths that needed to be equal were, and I used the x and y kerf differences when calculating the x and y widths. The x widths are slightly smaller because there was more kerf meaning more material will get burned away during the cutting process.

<img width="892" height="645" alt="Screenshot 2026-10-26 172024" src="https://github.com/user-attachments/assets/23c9136d-8d9f-44d7-8e5a-35d1cde45768" />

Proof of parametric modeling is shown below, I added 3 in for my thickness instead of 2.718 and as you can see the equation changed accordingly.

<img width="802" height="600" alt="Screenshot 2026-10-26 182114" src="https://github.com/user-attachments/assets/8fa7da75-d30a-4b8c-ab5a-a4dad27ae804" />

<img width="875" height="643" alt="Screenshot 2026-10-26 182154" src="https://github.com/user-attachments/assets/650b4146-b42c-4c79-8a1b-8823e82a1235" />

I then designed the second sketch in SolidWorks which was the triangular piece. The variables were kept the same and the triangle sketch is shown below.

<img width="813" height="603" alt="Screenshot 2026-10-26 175124" src="https://github.com/user-attachments/assets/95f67fdc-22c6-4368-8d1b-fc2b916337b0" />

Last thing that needed to be designed was the sketch for the other piece. The sketch is shown below. The same parameters were used. Ethan Cornett designed this piece.

<img width="877" height="823" alt="Screenshot 2026-10-27 115129" src="https://github.com/user-attachments/assets/3c836ab9-7701-44cc-a0c5-6265cfd3c45b" />

The final cut plan in Inkscape is shown below, including planned placements for all the parts. We tried to keep material waste to a minimum without compromising on quality.

<img width="768" height="350" alt="Screenshot 2026-10-27 114742" src="https://github.com/user-attachments/assets/52496352-3b5e-45e8-b9df-c4f7fcf902e7" />

## Manufacturing, including Process Research

### The process of printing is the following:

1. Open all vents to allow flow (Make sure handles are parallel)
2. Turn on pump beneath printer
3. Turn on printer
4. Center Let printer auto align
5. plug printer into computer
6. Use ctrl + P to print in inkscape
7. Send it to the Epilog cutter (select the material settings)
8. Wait for cutter to finish after pressing start
9. Wait for most of the smoke to leave
10. Open once it is safe and retrieve part.

This process was taught by a member of the super fabrication lab. It is important this workflow is followed to ensure safety.

The Excel table showing the details of our manufacturing processes are shown below.

<img width="607" height="286" alt="Screenshot 2026-10-27 114411" src="https://github.com/user-attachments/assets/038d6257-3f67-43af-b3ae-389120376a64" />

An image of our test cut is shown below.

<img width="3024" height="4032" alt="IMG_4175" src="https://github.com/user-attachments/assets/cf8bca0f-dcb6-4384-97c4-23e46e2a4b81" />

An image of our final cut is shown below, as well as a video showing the printing process.

<img width="3024" height="4032" alt="IMG_4177" src="https://github.com/user-attachments/assets/cbb69c37-66e7-487d-821d-6976485ddd21" />

The manufacturing process took a while to get right. There were noticeable differences in the amount of smoke that was left in the printer when the vent was left shut, or the pump was not activated. Fixing this dissipated the smoke incredibly quick. We chose to keep the wood in the back left corner in order to keep consistency. The wood was not very burnt once we moved the z axis up slightly. the burning likely became worse up close to the wood, and was not as bad once it was not almost touching. This was because the one area of the wooden board was sticking up.

## Lessons Learned

10/23/26 - Completed Steps 1 and 2 and the documentation for these steps. This took roughly 2 hours.

10/26/26 - Completed Steps 3-4 and designed the pieces to be cut out and the documentation for these steps. This took roughly 3 hours.

10/27/26 - Performed final cut and finished documentation. This took roughly 1 hour.

I learned several lessons throughout this project. The time to print was much faster but that was almost a negative thing because it allowed for multiple failures instead of us taking the time to fix everything, we only focused on one or two things at once. The second and most important thing I learned was that the kerf of a laser cutter can contribute a significant amount to tolerances and it is important to measure it properly before performing the lab.

