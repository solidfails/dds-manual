# Featurescripts

Onshape has its own scripting language to create custom features to automate aspects of design called [Featurescript](https://www.onshape.com/features/custom-features). There are a lot of featurescripts (what we call the custom features) that make designing for FRC much easier.

### How To Install Featurescripts

1. Open any Onshape document and go inside of a part studio
2. Click the rightmost button on the toolbar <img align="center" src="../../../../img/featurescripts/addCustomFeatures.webp">
    - **Note:** If you have previously added any Featurescripts one of those may show up as the right most icon. In that case click the dropdown to show the add button.
3. Paste the link of the document with the featurescript(s) in it into the search bar
    - **Note:** Some of the below featurescripts exist in the same document, so you can add multiple from the same link.

4. Select the featurescript(s) you want to add to your profile, then exit the box. They will be accessible in all documents from then on in the same drop-down in the toolbar where you added the feature.

<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/addingFeaturescriptsTutorial.webp">
      <source src="../../../../img/featurescripts/addingFeaturescriptsTutorial.webm" type="video/webm">
    </video>
  </figure>
</details>

!!! alternate
    When viewing a tab in a document that uses custom features, you can click a button near the top left that says 'custom features'. From here you can add custom features used in the document to your profile. This method is used in [stage 0](design-guide/stages/0.md/#featurescripts) to add Julia's Featurescripts when setting up Onshape.

## Recommended Featurescripts
Below is a collection of featurescripts we recommend you add to aid your design process.  

!!! tip
    The title of each featurescript or group of featurescripts links to its respective document. Right click the title and click "copy link address" for installing it to your profile using the above process.

### [Julia's Featurescripts](https://cad.onshape.com/documents/95c00401c440b44ad8799ef5/w/1f1ebce01a3b8eb6fa102975/e/b92d638809ae48771ecc7ad8)

**Extrude Individual** 

- Can extrude multiple regions as different parts with one feature, even if regions are adjacent
- Commonly used with tube converter to make punched aluminum tubes from a top view sketch
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/EI.webp">
      <source src="../../../../img/featurescripts/extrudeIndividual.mp4" type="video/mp4">
    </video>
  </figure>
</details>

**Tube Converter**

- Converts extrusions into punched tube, with customization and presets for hole pattern, wall thickness, and profile.
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/TC.webp">
      <source src="../../../../img/featurescripts/tubeConverter.mp4" type="video/mp4">
    </video>
  </figure>
</details>

**Shaft Generator**

- Generates a shaft, with options for hex, rounded hex (13.75mm OD), MAXSpline, etc.
- Options for retention type on both ends
- Can be generated in-place and with offsets
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/SG.webp">
      <source src="../../../../img/featurescripts/shaftGenerator.mp4" type="video/mp4">
    </video>
  </figure>
</details>

**Spacer Generator**

- Generates a spacer, with options for round, 3/8" hex, and 1/2" hex
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/S.webp">
      <source src="../../../../img/featurescripts/spacer.mp4" type="video/mp4">
    </video>
  </figure>
</details>

**FilletXpert (Fillet All Edges)**

- After selecting a face, it adds a fillet to the corners of that face (all edges normal to the selected face)
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/FAE.webp">
      <source src="../../../../img/featurescripts/filletEdges.mp4" type="video/mp4">
    </video>
  </figure>
</details>

**Chain Generator**

- Generates a simple chain path and sprockets with given tooth count of both sprockets and pitch
- Either in-place with points and generates the closest chain length or takes a c-c distance
- Options for simplified or realistic
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/CG.webp">
      <source src="../../../../img/featurescripts/chainGen.mp4" type="video/mp4">
    </video>
  </figure>
</details>

**Contextless Belts**

- Similar to chain generator, generates a simplified belt given the tooth counts of both sprockets and pitch
- Either in-place and generates the closest belt, or takes a c-c distance without context and does the same
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/CB.webp">
      <source src="../../../../img/featurescripts/contextlessBelts.mp4" type="video/mp4">
    </video>
  </figure>
</details>

**3D Printed Mass**

- Modifies 3D-printed parts to have accurate mass with given material, infill, and wall thickness
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/3DP.webp">
      <source src="../../../../img/featurescripts/3DPMass.mp4" type="video/mp4">
    </video>
  </figure>
</details>

### [Vent Featurescript](https://cad.onshape.com/documents/702f94d6e4ffb0c64f611f87/w/f6ac7d31494b1215bb9c8a61/e/4bf4eb130870ebdf0008c5a4)

- Used for pocketing and lightening plates
- Uses sketch regions to determine pocket and rib placement
<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/V.webp">
      <source src="../../../../img/featurescripts/vent.mp4" type="video/mp4">
    </video>
  </figure>
</details>

### [Abhi's Features & Configs](https://cad.onshape.com/documents/96d32fd4fe5341563a402ecd/v/042060f84c30390d82d806f8/e/d7f04278e0325b6d4426ca34?jumpToIndex=2635&showReturnToWorkspaceLink=true)
**Set Materials**

  - Parametrically set materials and appearances of parts in batches

**Set Properties**

  - Sets properties of parts in batches

**Sprocket**

  - Generate a sprocket for common types of chain

### [Thrifty Insert](https://cad.onshape.com/documents/c54b1ff25af8ec89778cac4f/v/5a909b5ad938a3116448922f/e/c4fc9251685f8516e9022bc6)
- Cuts a profile in a part at a given location and depth to fit a [thriftybot insert](https://www.thethriftybot.com/products/qty-5-aluminum-insert-for-3d-printed-parts) into, for 3D-printed parts to stop them from stripping while being driven on an axle.

### [SuperDerive](https://cad.onshape.com/documents/cfef86ed4f9635531599a973/v/07475511d9c61d4993261871/e/305f5ce7d2fdb46e12881f6f)
- Like the normal derive feature, but you can choose where the derived part is placed, duplicate it, perform a boolean operation, and even derive variables.

### [Assembly Mirror](https://cad.onshape.com/documents/0f7d68295ff4dab57adcf92c/v/88fbfa19a2e2555d18599db4/e/bcf3052f00f1f9d3d95a89c7?jumpToIndex=1392)
- Adds reflected mate connectors to a part so you can easily mate it reflected across a plane in an assembly (does not mirror geometry).

### [Auto Layout](https://cad.onshape.com/documents/576e01dbe4b0cc2e7f46a55d/v/f697250aa149b6846173f4b1/e/887d6e2324589bfd2058c3e1?jumpToIndex=2346)
- Given some derived plates, either transformed from an in-context assembly (to maintain part count) or derived from a part studio, it will automatically lay them out into sheets of a given size, sorted by thickness. This is used to prepare a file to route or waterjet parts out of material with a machine.

## Other Featurescripts

### [Alex's Featurescripts](https://cad.onshape.com/documents/9cffa92db8b62219498f89af/v/d1389fa34235160533671706/e/99672d1e329b38e647d90146)

**Robot Belt**

  - An alternative to contextless belts with an included belt calculator, but can get angry if the c-c distance isn't correct.

**Robot Spacer**

  - A more complex alternative to Julia's spacer generator, if you need more config options

**Spur Gear**

  - Generates a spur gear with a ton of different options
  - Can be useful for 3D-printed parts.

### [2471 Featurescripts](https://cad.onshape.com/documents/028ca8fb10baf53e1f6fce96/v/821c8b51ed0953526b51926e/e/a8b9e45297aac9f5688c871d)

**Advanced Variables**

  - Can create a compound variable with path length, angle between edges, distance between planes, angle between planes, distance between points, pulley center distance, and chain center distance
  - Very useful for complex belt and chain runs
  - Include measurements that Onshape can't normally do

**Belt & Pulley Generation**

  - Incredibly configurable belt and pulley generation
  - Belt width, pulley tooth count, offset and fit adjustment, belt type, etc.
  - Options for bore and flanges for both pulleys

**In-Place Bearings**

  - Place different types of bearings in place in a part studio

**Part Lighten**

  - Better than "Lighten" and more complex than "Vent"
  - Better control over ribs, cut depth, fillets, etc.
  - Gives a nice estimate of how much weight is being saved

**Part Numbering**

  - Numbers parts based off of a given standard

**Polybelt Generator**

  - Generates polycord and pulleys based off of selected points'

### [TLamp's Featurescripts](https://cad.onshape.com/documents/f46510f08cc311a34733cac2/v/f7f3a1c996c58466f6b88a37/e/8e9fbf1ac2f0980e4bc34951)

**MechSketch**

  - Incredibly useful, generates sketch profiles for a variety of things
  - Profiles for COTS parts like Maxspline, TTB inserts, maxtube, motors, and the versa patern
  - Profiles and holes for all electronics
  - Profile generator for pulleys and a spur gears

**CheeseIt!**

  - Advanced lightening pattern generation
  - Isogrid, hexagon, or circle pattern

**PatchIt!**

- Patches specified pockets in a part

### [Complex Belt Generator](https://cad.onshape.com/documents/b273b67c06b86b78b01b6f3a/w/f8670c98f827edfb8e96e7e9/e/9076725852f28d52fd6e796f)

- Generates a complex belt run based off of a sketch with pulley and idler circles


### [Gusset Generator](https://cad.onshape.com/documents/95c00401c440b44ad8799ef5/w/1f1ebce01a3b8eb6fa102975/e/b92d638809ae48771ecc7ad8)

- One of Julia's featurescripts
- Exists but not recommended due to load time

### [Lighten](https://cad.onshape.com/documents/573f7d70e4b0fddafb52148c/v/0edea0fa2707e715d040e74f/e/5eccf6d369b0312a728d77d3)

  - Less optimized and breaks more then vent.

### [Part Numbering Featurescript](https://cad.onshape.com/documents/443e443bb2a37736743bf314/w/6539c7379d36307a6a2cc01d/e/ef4e1b0c40e1dbf2ee36d02e)

- Used for quickly applying a system to number parts

## Troubleshooting
If a featurescript is not working as expected, the current version might be broken. You might have to update the featurescript. If it needs updating, the feature will show a blue icon to the right of it that, when hovered over, will say "change version of linked document."

1. The first way to update it is by individually by right clicking the feature you want updated in the feature list and clicking "Update linked document..."
2. The second, and slightly more permanent way (until the maintainer of the custom feature creates a new version), is by right clicking any of the featurescript icons in your toolbar or in the custom features dropdown and clicking "Update..." or "Update all..." From there, you can see the current versions of the custom features you have added to your profile and update selected ones to use the current latest version when you use a featurescript.

<details>
<summary>Video Tutorial</summary>
  <figure class="video_container">
    <video controls="true" allowfullscreen="true" poster="../../../../img/featurescripts/updatingFeaturescriptDocuments.webp">
      <source src="../../../../img/featurescripts/updatingFeaturescriptDocuments.webm" type="video/webm">
    </video>
  </figure>
</details>