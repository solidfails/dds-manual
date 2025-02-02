<style>
.right{
    float:right;
}
.center{
    text-align:center;
}

.left{
    float:left;
}
</style>

# 1B: Swerve Drivebase Project

<span class="left">[< 1A: Sketching & Part Design](1A-sketchingPartDesign.md)</span> <span class="right">[1C: Gearbox Projects >](1C-gearboxes.md)</span>
<br>

For your first project, we’ll be making a swerve drive base. (Editor’s note: the use of unsimplified models is deliberate, will use simplfied models in 2B Project. ) In this project we will go step-by-step as we introduce new concepts. Remember to apply the skills you have already learned.

![Swerve Assembly](\img\design-guide\stage1a\Stage 1A Swerve\Assembly_1.webp){width=45% height=45%}

It is important to learn how to design a swerve drive base since it is the most commonly used competitive drivetrain in FRC, and everything you design goes on top of it. 

!!! note
    Notice how it’s made out of aluminum box tubing. You’ll find that this is most common “structural” part. You can think of this like the bricks for a house. Box tubing use used in everything, it is most commonly found in 2 inch by 1 inch, 1 inch by 1 inch, and 2 inch by 2 inch sizes. It is also found in 1/8 inch and 1/16 inch thicknesses.


!!! note
    For the rest of the tutorial, box tubing will be referred to by their shorthand name (based on their size), such as 2x1, 1x1, and 2x2.

A swerve drivebase is composed of four swerve modules. Each module has a motor which is used to power and steer the wheel. This allows you to move in any direction.

To start, we will be making a sketch on the right plane. This will be representing the right side of our robot and help us determine the length of the drive train. Name the sketch “Robot Layout” 

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 1.webp){width=45% height=45%}

Make a center point rectangle and do a vertical constraint on the center point of the rectangle to the origin point. (The black and white circle) Make the rectangle 2 inches high. This rectangle represents the box tube that you saw above. Then dimension the rectangle 1.75 inches above the origin. 

Now we have a drivetrain side of unknown length, that is 2 inches wide and 1.75 inches above the ground

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 2.webp){width=45% height=45%}

Let’s define the length of the drivetrain. We can do this by dimensioning the rectangle to a set size, we’ll do 26.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 3.webp){width=45% height=45%}

This means that our drivebase is 26 inches long.

To make things a bit easier, let’s also draw our wheels.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 4.webp){width=45% height=45%}

We can do this by making a 3 inch rectangle that is constrained horizontally to the origin (the wheel raises the drivetrain by 1.75 inches). We can then make a mirror line by drawing a line in the center, then mirroring as so.

Now, let’s make the whole thing construction. We’ll be using this as a reference point to define the length and width of the square drivetrain. If we need to change the chassis dimensions, we can go back to “Robot Layout” and change it.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 5.webp){width=45% height=45%}

Let’s confirm the sketch.

Now we’ll be modeling the drivetrain tubes. We’ll be ending with something that looks like this.

![tubes.png](\img\design-guide\stage1a\Stage 1A Swerve\Tubes.webp){width=45% height=45%}

!!! note
    Notice how the part studio has all the tubes of the drive train shown here.


Make a plane and set the plane as “line angle”

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 6.webp){width=45% height=45%}

Then click the line on the bottom of the drivetrain sketch that we made before. (Click the the highlighted line)

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 7.webp){width=45% height=45%}

Then, press the checkmark and confirm the plane. Planes allow us to create sketches that are placed away from the original starting planes. Let’s now make a sketch, making the sketch plane the new plane we just created. You can do this by clicking the plane.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 8.webp){width=45% height=45%}

Now, press the “Top” button on the view cube and get a top view. For our next steps we’ll be viewing directly from the top, sketching out the “top” of the drivetrain tubes. 

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 9.webp){width=45% height=45%}

Start by making a center point rectangle, then dragging out once you highlight the top edge of the dotted line. If you remember previously, that edge was the edge of your drivetrain which you defined as the length of the drivetrain. See how the left side of the rectangle is already 26 inches! We want to make this a square, so let’s use the equal constraint (e key), then press the top of the square and the left side of the square. This should make both sides equal to each other, and the whole sketch should be black.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 10.webp){width=45% height=45%}

Use the offset tool and offset the square inwards by 1 inch, this will define the side of your drive rails.

Taking a look at the swerve drivetrain again, we can see there’s a cutout in each of the corners. We should define this in our sketch. From the edge of the corner, the gap is 4.25 inches long. 

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 11.webp){width=45% height=45%}

Draw two lines, one horizontally constrained and one vertically constrained and dimension them 4.25 as shown on one of the corners

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 12.webp){width=45% height=45%}

Then, Circular pattern the two lines you created, changing the pattern to four. It should look like this:

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 13.webp){width=45% height=45%}

Confirming the sketch should show the chassis as shown, with some blue lines. Why is that? 

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 14.webp){width=45% height=45%}

If you click on one of the points on the blue unconstrained lines, you can drag them around. This also reveals the center of rotation of the circular pattern

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 15.webp){width=45% height=45%}

Constrain the center of rotation to the origin using the coincident tool. 

Your sketch should look something like this now.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 16.webp){width=45% height=45%}

If we take the top view of a drivetrain, you can see how it looks similar. Removing the modules also shows the gaps we modeled.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 17.webp){width=45% height=45%}

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 18.webp){width=45% height=45%}

Let’s now sketch out the middle cross beam. We’ll make this out of 2x2 aluminum since 2x2 is stronger than 2x1.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 19.webp){width=45% height=45%}

Let’s make it 2 inches wide, and 2 inches away from the center (origin).

Now, let’s confirm the sketch. You can also rename the sketch to “Drivetrain Top” 

Now, lets create the tubes. Click the extrude individual featurescript. Extrude individual allows us to make multiple parts, one per sketch reason, with a single extrude feature.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 20.webp){width=45% height=45%}

Click the top faces of the sketch, and extrude.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 21.webp){width=45% height=45%}

Now use the tube converter featurescript and click on the four outer tubes.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 22.webp){width=45% height=45%}

We need to set the thickness as 0.125, as 0.125 thickness is “thick wall” tubing. 0.125 thick tubes are strong and allow for a strong and rigid frame that is resistant to collisions. Set 2 inch face style to “1 inch between holes”, and click the checkbox for center row. You can find this type of box tubing on various COTS vendors, which sell the pre-punched tubing for your convenience.

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 23.webp){width=45% height=45%}

(Source: West Coast Products)

Now confirm the tube converter.

Let’s do another tube converter for the 2x2 tube, but change the thickness to 1/16. The reason for this is because 1/16 2x2 is plenty strong, and allows for weight savings down the line.

Once you are done, change the appearance of all of your tubes to a color of your choosing. I’ll be using dark gray. You can do this by going to the parts menu and clicking all 5 parts, then right clicking and selecting “edit appearance for 5 parts”

![Untitled](\img\design-guide\stage1a\Stage 1A Swerve\1a-Swerve 24.webp){width=45% height=45%}

### Assemblies:

Now that we have our chassis, we need to assemble it in an “Assembly” 

Assemblies are where you assemble the final product. While in part studios, you create your parts, in assemblies, you assemble your parts into the final robot. 

Something to note is that both assemblies and part studios have an origin. We will need to make sure that our parts are in the same place in both the origin and part studio. We can do this through an origin mate connector.

Select the mate connector button on the top. 

![Connector 1](\img\design-guide\stage1a\Stage 1A Swerve\Mate-Connector.webp){width=45% height=45%}

Unhide the origin if it was hidden:

![Connector 2](\img\design-guide\stage1a\Stage 1A Swerve\Mate-Connector 1.webp){width=45% height=45%}

Follow the video below. 
<iframe width="560" height="315" src="https://www.youtube.com/embed/4jTYh0Rn5cU" frameborder="0" allowfullscreen></iframe>


Select the origin entity as the origin, then the owner entity as the 2x2 tube. The 2x2 tube will now have an mate connector at the origin.

Now that you have finished your part studio. You can follow this tutorial to do the rest of the assembly. Assemblies require a bit more explaining, which is why it's in video instead of the text above. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/9cMRIJJGGeE" frameborder="0" allowfullscreen></iframe>

<br>
<center>1B: Swerve Drivebase</center> 
<span class="left">[< 1A: Sketching & Part Design](1A-sketchingPartDesign)</span> <span class="right">[1C: Gearbox Projects >](1C-gearboxes.md)</span>
<br>
<br>