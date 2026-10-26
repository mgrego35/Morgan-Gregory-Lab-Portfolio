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

[FIRST IMAGE (MOVING THE PIECES)]

[SECOND IMAGE (SKETCH OF THE PART)]

There were 3 fits to make, a tight fit, a target fit, and a loose fit. I began with the tight fit using the calculations below, where K is the kerf and D is the clearance or distance between the pegs.

Tight Fit: D = t<sub>average</sub> + x<sub>0</sub> - K<sub>x</sub> - .05 mm

For the tight fit this turned out to be D = 2.718 mm + 10 mm - .10 mm - .05 mm = 12.568 mm

[IMAGE HERE]

Next I added the next 10 mm little tab to give them some space. Then I started the normal fit shown below.

Normal Fit: D = t<sub>average</sub> + x<sub>0</sub> - K<sub>x</sub>

For the normal fit this became D = 2.718 mm + 22.568 mm - .10 mm = 25.186 mm

[IMAGE HERE]

Then I added the next 10 mm space, and did the loose fit calculations, this time ADDING .05 mm to the fit.

Loose Fit: D = t<sub>average</sub> + x<sub>0</sub> - K<sub>x</sub> + .05 mm

For the loose fit this came out to be D = 2.718 mm + 35.186 mm - .10 mm + .005 mm = 37.809 mm

I added the loose fit dimensions and then added the 10 mm final piece. 

[IMAGE HERE]



## Manufacturing


10/23/26 - Completed Steps 1 and 2.
10/25/26

