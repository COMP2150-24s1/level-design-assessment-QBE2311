[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Alexander Travers
### Student number: 46414843

## 1. Player Experience

### 1.1. Discovery

The player learns a number of concepts throughout the level. 
- The combat utility of the staff and gun, from facing enemies in gradually more difficult positions. 

![A Spitter on an elevated platform, and a Chomper in a recessed section of floor. Both are easily within staff reach.](DocImages/Enemies1.png)

![A Spitter on a floating platform, with a number of other platforms nearby. No solid ground is visible.](DocImages/Enemies2.png)

![A Spitter and Chomper attacking the player within an enclosed space. Behind the player is a pit, restricting their ability to retreat.](DocImages/Enemies3.png)

- The limits of the player character's jumping abilities, through carefully placed platforms just beyond said limits. 

![From near the start of the level, the player can see a key on an elevated platform. However, the player's jump is simply not high enough to reach it.](DocImages/JumpLimits.png)

- And, notably, capability of the pushable boxes for puzzle solving in multiple aspects, namely in combination with pressure plates and acid.

![A pushable box and a pressure plate are present in this area. When pressed, the plate opens the door to the key, but the door closes when the plate is no longer pressed.](DocImages/BoxAndPressurePlate.png)

![By pushing the box onto the pressure plate, the door remains open, and the key can be collected.](DocImages/BoxOnPressurePlate.png)

![Pushable boxes can be seen floating in acid, providing a platform to stand on. A box can also be seen on the shore, and can be pushed in for another platform.](DocImages/BoxesInAcid.png)

The player learns these concepts each in relative isolation before being required to make use of their knowledge, allowing them time to familiarise themselves with and understand it properly before applying it.

### 1.2. Drama

The most readily accessible area of the level is fairly calm, with only a few enemies and light platforming present. 
![The first level section, composed of relatively simple platforming with only a handful of enemies.](DocImages/LevelSection1.png)


The next area ramps up, including numerous dangerous crystal spikes as well as providing the player with both a gun and a combat encounter in much tighter quarters.
![The second level section, a crystal cave and minor enemy arena.](DocImages/LevelSection2.png)
Once this area is cleared, however, the player exits the cave and is provided with a health box and a key, eliciting a sense of relief, safety, and progression.


From here, the player moves to the final area, a subterrainean acid lake with pushable boxes floating on the surface. The acid, returning the player to their last checkpoint immediately if hit, is a notably more concerning hazard than the crystals. In addition, the boxes bob slightly in the acid, making platforming noticeably more difficult to perform safely. This section also has a relatively low ceiling, leading to much more tense jumps. Once the player has obtained this area's key, they still are not safe. They must also make their way back out the way they came, before being able to relax properly.
![The third level section, with a number of floating boxes upon the lake of acid, and one spitter placed to incentivise utilising the player's ranged capabilities.](DocImages/LevelSection3.png)
Once this section is cleared and escaped, the player is home free, and all tension is relieved.


### 1.3. Challenge

The main challenges in my level are placed in such a manner that the difficulty escalates gradually, but simultaneously does not require the player to engage one kind of challenge for an extended period of time. For example, the level's first notable challenge is engaging a few enemies in simple combat:
![A Spitter on an elevated platform, and a Chomper in a recessed section of floor. Both are easily within staff reach.](DocImages/Enemies1.png)
But the next difficulty to overcome is one of platforming, to ensure nothing becomes stale. Then a fairly simple puzzle.

Once the key has been retrieved, the next most accessible area contains somewhat more hazardous platforming, and more close quarters enemies:
![The second level section, a crystal cave and minor enemy arena.](DocImages/LevelSection2.png)

And once this area is concluded, the final area is the most difficult platforming of the stage, and must be completed twice, but is varied enough internally to (ideally) remain interesting.
![The third level section, with a number of floating boxes upon the lake of acid, and one spitter placed to incentivise utilising the player's ranged capabilities.](DocImages/LevelSection3.png)

### 1.4. Exploration

The level is laid out in a nonlinear fashion, with the entrance to the second and third sections readily visible from the start of the level. It is the intention that seeing these paths will inspire curiosity in the player to investigate them further, and progress through the level in a natural fashion.

Aesthetically, the three areas are distinctly different.
The first section is entirely open-air platforms, floating in the sky. It is intended to feel free, unrestrained, but also precarious.
![The first level section, its open nature readily apparent and demonstrated by the lack of walls (both structural and background).](DocImages/LevelSection1.png)

The second is a rough, craggy cave area entirely enclosed and covered in crystals. It is intended to give a sense of a natural formation, entirely untouched by human hands.
![The second level section, crystalline and natural in structure, with uneven walls and a ceiling that gives the impression of stalactites.](DocImages/LevelSection2.png)

The third is a buried ruin with grass and dirt seeping in, the bricks giving way to nature's reclamation. It is intended to give a sense of abandonment, of peoples long since gone, and the questions raised by their absence.
![The third level section, constructed of ancient stone slabs. An acid lake is present, with strange, stonelike cubes floating upon its surface. Dirt can be seen intruding through the ceiling, implying that it has given way in the past.](DocImages/LevelSection3.png)

## 2. Core Gameplay

### 2.1. Weapon Pickup (Staff), Passthrough Platforms, Chompers & Spitters, Health Pickups
![](DocImages/Storyboard1-1.png) <br>
![](DocImages/Storyboard1-2.png) <br>
![](DocImages/Storyboard1-3.png) <br>
![](DocImages/Storyboard1-4.png) <br>
![](DocImages/Storyboard1-5.png) <br>
![](DocImages/Storyboard1-6.png) <br>
![](DocImages/Storyboard1-7.png) <br>
![](DocImages/Storyboard1-8.png) <br>
![](DocImages/Storyboard1-9.png) <br>
I chose to introduce the Staff early so as to allow for enemies to be present throughout the level without the player feeling defenseless. In addition, the enemies here are encountered in a configuration that makes them fairly easy to deal with, suiting their introductory role. Furthermore, the presence of health pickups earlier in the level than the player might need them would encourage curiosity in the player as to what they do, and considering a new player will likely take damage from their first enemy encounter, I believe they will naturally discover the purpose of health kits shortly after. In hindsight, a destructible object between the staff and enemies would be good design, to ensure the player is aware of the function of their new staff before encountering any enemies.

### 2.2. Moving Platforms
![](DocImages/MovingPlat1.png) <br>
![](DocImages/MovingPlat2.png) <br>
![](DocImages/MovingPlat3.png) <br>
![](DocImages/MovingPlat4.png) <br>
![](DocImages/MovingPlat5.png) <br>
![](DocImages/MovingPlat6.png) <br>
![](DocImages/MovingPlat7.png) <br>
![](DocImages/MovingPlat8.png) <br>
I chose to arrange fallthrough platforms in such a way that there are higher platforms just out of reach without using the moving platform. Therefore, the player will likely attempt to jump from the easily-accessible stationary platforms, fail, and realise the utility of the moving platform as a traversal option.

### 2.3. Keys
![](DocImages/KeyIntro1.png) <br>
![](DocImages/KeyIntro2.png) <br>
![](DocImages/KeyIntro3.png) <br>
![](DocImages/KeyIntro4.png) <br>
I chose to place the first key the player will likely encounter behind a simple puzzle, to demonstrate that it is likely an object of value. And, once the player collects said key, the visual feedback from the UI will reinforce this perception and encourage their collection.

### 2.4. Spikes
![](DocImages/Spikes1.png) <br>
![](DocImages/Spikes2.png) <br>
![](DocImages/Spikes3.png) <br>
![](DocImages/Spikes4.png) <br>
![](DocImages/Spikes5.png) <br>
The player is introduced to spikes in a very unassuming manner, without any major complications. The jump required to clear the spikes is simply somewhat precise, increasing the likelihood of an unaware player accidentally hitting the spikes and taking damage, therefore becoming educated in their function.

### 2.5. Weapon Pickup (Gun)
![](DocImages/Gun1.png) <br>
![](DocImages/Gun2.png) <br>
![](DocImages/Gun3.png) <br>
![](DocImages/Gun4.png) <br>
The player discovers the gun right next to a switch conspicuously out of staff range, and a vertical shaft that is too tall to climb. this will naturally encourage the player to attempt to shoot the switch, which will in turn raise the player up the shaft.

### 2.6. Checkpoints & Acid
![](DocImages/AcidCheckpoint1.png) <br>
![](DocImages/AcidCheckpoint2.png) <br>
![](DocImages/AcidCheckpoint3.png) <br>
![](DocImages/AcidCheckpoint4.png) <br>
![](DocImages/AcidCheckpoint5.png) <br>
![](DocImages/AcidCheckpoint6.png) <br>
![](DocImages/AcidCheckpoint7.png) <br>
![](DocImages/AcidCheckpoint8.png) <br>
![](DocImages/AcidCheckpoint9.png) <br>
(The player encounters Checkpoints at other places throughout the level, but this point is where they are most likely to first be of major use.)
The use of a moving platform in this encounter amplifies the likelihood that a player will fail to pass this challenge on their first attempt. Therefore, they are likely to experience acid's "one-hit respawn" properties, which make it far more effective in slowing progress than spikes. In addition, as respawning places the player at a checkpoint, they will now be informed as to the function of said checkpoints, should they not have gleaned it elsewhere.

## 3. Spatiotemporal Design
 
### 3.1. Molecule Diagram
![](DocImages/LevelMolecule.png) <br>

### 3.2. Level Map – Section 1
![](DocImages/DiagramSection1.png) <br>

### 3.3.	Level Map – Section 2
![](DocImages/DiagramSection2.png) <br>

### 3.4.	Level Map – Section 3
![](DocImages/DiagramSection3.png) <br>

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

Iterative design helped to improve my level via the streamlining and re-evaluation of the placement of multiple main level elements. The earliest prototype design I have for the level as a whole can be seen below, with an attached key for what any given colour represents.

![](DocImages/LayoutPrelim10x.png) <br>
![](DocImages/LayoutPrelimKey.png) <br>

There are numerous minor changes from this intended design in the final level, mainly in the form of decisions that will ensure the player has a smooth flow through the level (Using bridges to close off areas that are not intended to be traversed yet, preventing the player from pushing a box off the platform it is intended to remain on, etc.) A good example of this is in the upper exit from area 2's cave. In the preliminary prototype, it was possible to drop to the acid lake from here, sending the player back to the mid-area-2 checkpoint, and likely frustrating them greatly. This flaw remained until the level was greyboxed, at which point it became apparent and was corrected.

Additionally, playtesting early greyboxed versions of the level, (included below) revealed a number of additional minor flaws:
- Platforms were placed in such a way that intended encounters could be skipped.
- Ceiling tiles were too low in multiple cases, leading to unintentionally difficult platforming.
- Spike hitboxes were poorly oriented, leading to the player taking damage when it felt unwarranted.

![A greyboxed version of the first level section. The area is not noticeably altered in layout from the final product.](DocImages/GreyboxedLevelSection1.png) <br>
![A greyboxed version of the second level section. There are spikes in a few places which they are not in the final level, and the box-dropping mechanism is entirely different, with the shaft accessible from the top.](DocImages/GreyboxedLevelSection2.png) <br>
![A greyboxed version of the third level section. The bridge that is required to be hit to enter the area is not present, allowing a player to potentially drop through the moving platform and softlock themselves at the bottom. Additionally, the moving platform in the acid is not present, nor the health pickup at the other side of the lake.](DocImages/GreyboxedLevelSection3.png) <br>

One particular aspect I believe could be improved through further iterative design is the introduction of the weapons. In both cases, they are introduced to the player, and shortly afterwards the player is expected to use them in combat with little practice. A smoother introduction, likely with some puzzles requiring use of the weapons, such as destructible pillars and shootable switches, would feel less jarring for the player, and improve the sense of flow throughout the stage.