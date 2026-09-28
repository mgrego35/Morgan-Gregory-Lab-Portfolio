# A6 – Design Fits for an Artifact

## The Assignment

The given assignment this week was to grab an artifact from the bin in class and make a snap fit that attaches to the artifact. The artifact chosen was a gear with a mount that I intent to make a better more custom mount for that can stand it up. The artifact is shown below.

<img width="375" height="445" alt="Screenshot 2026-09-28 153624" src="https://github.com/user-attachments/assets/c063a62b-d0aa-48bb-bf9d-23d1edbb2bf0" />

Measurements for this assignment were taken with a Neiko digital caliper found at the end of this assignment and shown below.

<img width="503" height="308" alt="Screenshot 2026-09-28 153804" src="https://github.com/user-attachments/assets/ee94ecb6-157b-465a-91e9-02aed66e375e" />

## Parametric Design

To begin the parametric designing phase, I started by taking the measurements of the base and adding them to my variables list.

<img width="747" height="122" alt="Screenshot 2026-09-28 151024" src="https://github.com/user-attachments/assets/7c862cde-6e27-4f68-a02d-8cdb8c06fa82" />

Next I created a sketch of the top view. I began with this because it was easily the hardest geometry to produce and I could easily cut out rectangles from the sides instead of trying to do it a much harder way. The first top view sketch is shown below.

<img width="780" height="534" alt="Screenshot 2026-09-28 020431" src="https://github.com/user-attachments/assets/9de91178-d644-4659-8829-3651394fb108" />

I then extruded the top sketch by the global variable for the height. This will leave clearance between the platform and bottom in order to not get caught on the small piece below.

<img width="639" height="297" alt="Screenshot 2026-09-28 134934" src="https://github.com/user-attachments/assets/b66779f2-8b0b-4336-a44c-d1ae7017666e" />

Next, I made the sketches on the side in order to cut out where the extra pieces are on the artifact. This allows it to not be blocked when trying to snap in.

<img width="778" height="806" alt="Screenshot 2026-09-28 135528" src="https://github.com/user-attachments/assets/f292ae7e-d908-4611-9523-45488fd4136e" />

I then used the extruded cut feature and selected through all.

<img width="543" height="495" alt="Screenshot 2026-09-28 135550" src="https://github.com/user-attachments/assets/af6611d0-f7bc-4355-98bd-974ddbb3d1c7" />

Then it was time for the base to be made, I made it a simple base as just a rectangular extrusion. The sketch and extrusion are shown below.

<img width="671" height="622" alt="Screenshot 2026-09-28 140003" src="https://github.com/user-attachments/assets/b280f98c-dc76-41a4-88d0-0b46108b6f07" />

<img width="598" height="574" alt="Screenshot 2026-09-28 140021" src="https://github.com/user-attachments/assets/0105799c-f704-4e4c-af87-6d61b3146f87" />

Finally I added some fillets on internal 90 degree corners that would be higher stress areas in order to add some extra strength geometrically. I also added chamfers on the back in order to alleviate some sharper edges. These changes are shown below. Only smaller radii (.01 in) were used, it is minor but it helps greatly.

<img width="854" height="308" alt="Screenshot 2026-09-28 140131" src="https://github.com/user-attachments/assets/92b68add-8a74-46af-8969-1b8749e71f65" />

<img width="702" height="275" alt="Screenshot 2026-09-28 140203" src="https://github.com/user-attachments/assets/4ab3cc07-3f0f-4a31-91d8-23d33a06a09e" />

<img width="597" height="580" alt="Screenshot 2026-09-28 140137" src="https://github.com/user-attachments/assets/02a45894-4488-4b64-9cc1-42a0068a64aa" />

The finished model is linked in the references section and is shown below.

<img width="801" height="715" alt="Screenshot 2026-09-28 152141" src="https://github.com/user-attachments/assets/f5f4c8c8-f7ee-43eb-a9d9-6504ba33e952" />

## Preprocessing

Preprocessing required some decisions for this part. I started by choosing the standard gyroid infill I always use for good strength in all directions.

<img width="510" height="186" alt="Screenshot 2026-09-28 140730" src="https://github.com/user-attachments/assets/cfec5fc6-0b90-428c-b04c-84e5dc40de04" />

I did however, need to use support materials in the gaps. It was possible to orient the print differently, but the lines being on the cross sections of the beams would have likely lead to failure or could have caused problems down the line. To play it safe I generated support material, and the final details and orientation are shown below.

<img width="424" height="190" alt="Screenshot 2026-09-28 140736" src="https://github.com/user-attachments/assets/fa272a82-0115-4b34-815b-a1a36aa2572d" />

<img width="960" height="472" alt="Screenshot 2026-09-28 140911" src="https://github.com/user-attachments/assets/582e7293-824f-4b9e-a850-3c666946c7cb" />

## Printing

The pictures/video of the printing process are shown below, as well as the final product unattached and attached.

<img width="408" height="550" alt="Screenshot 2026-09-28 153642" src="https://github.com/user-attachments/assets/a9c0e616-8d5a-45e4-a1e6-1400115e0795" />

<video controls width="320" src="https://github.com/user-attachments/assets/bc23fb6f-ea1c-47a4-b61d-b130ef605c10"></video>

[IMAGE OF UNATTACHED HERE]

[IMAGE OF ATTACHED HERE]

## Lessons Learned

The main lesson I learned from this project was to focus on the most complex geometry to make first then focus on building around it in SolidWorks. I learned this by struggling to find a way to create the model the first time because of the part of the snap fit that I tried to start with. The final CAD model for this project is given below.

[Gear Mount.zip](https://github.com/user-attachments/files/32770916/Gear.Mount.zip)

Time to finish was about 4-5 hours.

## References

- https://www.amazon.com/Neiko-01407A-Electronic-Digital-Stainless/dp/B000GSLKIW/ref=sr_1_1_sspa?dib=eyJ2IjoiMSJ9.SHbnhkINMRgAbv3QFeu9nAd8ZSzRob5H4BOviBWtQnCDut8K-w2KFRkH48cqEP_9vSqEu6AtQOpjXr_ACuKfpcekFgl3bwMazoeu50aG9yosXj0cwB9UIn54C7SEATRubrlt6PjOmFNcCx9rU1mjCJc9COrLAtZ0fpJ-HpD_wHBm8nxo6MEMkOKqDJ71MOKqF6qtQk3xmBLLukhUEl5FiCiA0SJ0cNXL1Y6Uv1Vlw8o._en8Hl9UzuDIuFUkbr6o128ZqBLhdV0Wbr2aURRJVU0&dib_tag=se&keywords=neiko%2Bdigital%2Bcaliper&qid=1790624263&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1






















