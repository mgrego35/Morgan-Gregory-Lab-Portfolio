# Final Project – Laptop Dock

## Instructions

Goal: Select a real-world problem that you, a friend, or a family member personally experience and refine your prototype design to address it. The goal of this week is to identify a meaningful challenge that can be solved through manufacturing and to develop the first iteration of your prototype using research, modeling, and feedback.

Objective: Choose a problem that can be addressed with 3D printing/laser cutting and develop an initial design concept.

## Part 1: Defining the Problem and Rough Prototyping

### Research

The spiral design process (shown below) is important for engineers to understand because it describes the workflow on any project. During the planning phase, the problem is defined and the needs to be met are clearly laid out. A budget can also be given depending on the project and the constraints are given as well. During the Risk Analysis phase, the project is given an assessment of cost, time, labor, and prototypes can be made. During the engineering phase the prototypes are created fully, programmed, and changes are implemented. During the Evaluation phase, feedback and testing is used to verify if the product needs to be reformed further.

<img width="489" height="311" alt="image" src="https://github.com/user-attachments/assets/d67193e7-1e82-4a9b-9fb4-43a0189b67e8" />

Fused Deposition Modeling or FDM parts are inherently anisotropic. This is due to the filament being able to harden between layers which creates a natural very small gap between layers. This must be considered when designing because it can change the way a part may fail. For example if I have a part that can be modeled as a cantilever beam, if I create layers at the 90 degree angle going the wrong way, it will snap much easier than if I make them going perpendicular to that.

Stereolithography is a form of printing that uses a photosensitive resin. The shrinkage on these parts can be much higher than on FDM printing. The shrinkage can be almost 2% of a dimension depending on certain factors such as resin type, printer, and more. In order to compensate for this in my print, I will make sure to add around 1-2% depending on the resin type I use in order to get a much more accurately dimensioned part.

Laser cutting kerf is the material that is burned away when cutting. It depends on printer type, cut speed, cut power, and more. I will measure the kerf with the cutter I use BEFORE I cut in order to get an accurate measurement before, and then I will use that to add to my design dimensions if I decide to use the laser cutter.

### Problem Definition

Here are 3 problems that I am considering solving using FMD and SLA printing technologies.

The first idea is a drawer system for my desk. My desk feels too cluttered and I want to have a place to put things like my stapler. I could make little hinge joints with SLA printing and the base/body of the drawer system with FDM printing because it is cheaper.

The second idea is a laptop stand in order to save desk space. I could use a vertical stand to prop my laptop up when it is docked. I would also want to design around making a cord holder to go with my stand in order to prevent cords from falling behind my desk. I could make a stand with FDM printing and a cord organizer with SLA printing.

The third idea is a shelf for my projector that I can use to keep the space on my bedside table clear. I could do a simple shelf with FDM and a hook system with SLA technologies.

### Problem Selection

The problem I have chosen to solve is the laptop stand and cord organizer. I will use SLA printing, preferably grey v5 resin, in order to create a cord clip that clips on the edge of my desk shown here.

<img width="500" height="388" alt="Screenshot 2026-11-16 151602" src="https://github.com/user-attachments/assets/88a6d60d-63c3-4012-8de9-205d5840fbe2" />

I will also have to make a stand that accounts for the width of the laptop when shut. I will make it by FDM printing. 

<img width="501" height="254" alt="Screenshot 2026-11-16 151610" src="https://github.com/user-attachments/assets/97b9de7e-e9aa-4561-9572-3da2d896c8d6" />

### Concept Development

I decided to begin by measuring the width of my laptop shut. The width was .804 inches.

I then made a drawing shown below of the stand.

<img width="336" height="132" alt="Screenshot 2026-11-16 160543" src="https://github.com/user-attachments/assets/f6f829d6-c4d7-4783-bdc4-7647a4f55ca4" />

The drawing for the cable clip is shown below. The measurement for the table thickness was .5970 inches.

<img width="383" height="117" alt="Screenshot 2026-11-16 160528" src="https://github.com/user-attachments/assets/c07a3791-64f1-4717-bc72-4682f4368dc2" />

I then started by designing the model for the stand in SolidWorks. I began with the sketch below.

<img width="932" height="748" alt="Screenshot 2026-11-16 161727" src="https://github.com/user-attachments/assets/63970858-20f4-4168-9c9b-8a40de7604b5" />

I then extruded it by 6 inches.

<img width="1918" height="841" alt="Screenshot 2026-11-16 162045" src="https://github.com/user-attachments/assets/aefabb75-a2a0-4d1d-bc0a-8920403148d4" />

Then, I created an area for the little handle to lift the lid of the laptop up.

<img width="874" height="752" alt="Screenshot 2026-11-16 162207" src="https://github.com/user-attachments/assets/48b2b3d6-9510-4afa-a9c8-46397a0b953e" />

<img width="1916" height="842" alt="Screenshot 2026-11-16 162233" src="https://github.com/user-attachments/assets/ea871cb8-9c49-4663-88fd-08c05ce3a517" />

Finally I added fillets at the top to prevent damage to my laptop or the edges of the stand. The final part is shown and linked beneath that

<img width="1918" height="840" alt="Screenshot 2026-11-16 162744" src="https://github.com/user-attachments/assets/d0a92bfb-a475-43f4-a96f-b0cc34a088dc" />

<img width="989" height="540" alt="Screenshot 2026-11-16 162939" src="https://github.com/user-attachments/assets/280b7f06-a59b-42ca-8b46-0fd381625d84" />

[LaptopStandMKI.zip](https://github.com/user-attachments/files/34939780/LaptopStandMKI.zip)

Next I began working on the cable clip. I started with the sketch shown below and extruded it by 2 inches.

<img width="852" height="564" alt="Screenshot 2026-11-16 165924" src="https://github.com/user-attachments/assets/634a60f9-66ee-401e-8118-f712b5c515ba" />

The next Thing I did was create a sketch for the cable holes shown below and made an extruded cut.

<img width="1304" height="786" alt="Screenshot 2026-11-16 204153" src="https://github.com/user-attachments/assets/58ee323e-b929-4769-be3a-b4c95d4059f9" />

<img width="1917" height="845" alt="Screenshot 2026-11-16 204218" src="https://github.com/user-attachments/assets/d64a929e-cabc-4053-9c9b-e0b13c74247d" />

Finally I created some fillets on the edges in order to clean the part up and prevent sharp edges.

<img width="1919" height="840" alt="Screenshot 2026-11-16 204349" src="https://github.com/user-attachments/assets/94b0aefd-48a6-44fe-bb33-d9cb5fe379f3" />

The final part is shown below and linked as well.

<img width="990" height="563" alt="Screenshot 2026-11-16 204620" src="https://github.com/user-attachments/assets/cda6fffc-a5c8-49d5-b640-03c69dcb1dc4" />

[CableClip.zip](https://github.com/user-attachments/files/34946865/CableClip.zip)

### Video Presentation

<video controls width="320" src="https://github.com/user-attachments/assets/9e600007-1d97-4790-b95a-c82e6daaed75"></video>

## Part 2






## References

https://medium.com/@nld.anuradha/the-spiral-model-in-sdlc-risk-driven-and-iterative-development-a58f977d065c




