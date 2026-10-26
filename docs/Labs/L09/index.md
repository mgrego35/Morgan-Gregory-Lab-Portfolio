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

For both the Kerf and Fit coupons we used the same Settings. These are shown below.

-----------------------------------------
| Setting | Kerf/Fit Coupon | Final Cut |
-----------------------------------------
| Laser Cutter # |
| Material Type |
| Nominal Thickness |
| Measured Thickness |
| Speed |
| Power |
| Frequency/PPI |
| Number of Passes |
| Focus Method/How it was confirmed |
| Air assist on? Exhaust on? |
| How you set origin and alignment? |











## Lessons Learned

10/23/26 - Completed Steps 1 and 2.
10/26/26 - Completed

