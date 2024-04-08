[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Alexander Travers
### Student number: 46414843

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

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
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

The most readily accessible area of the level is fairly calm, with only a few enemies and light platforming present. 
![The first level section, composed of relatively simple platforming with only a handful of enemies.](DocImages/LevelSection1.png)


The next area ramps up, including numerous dangerous crystal spikes as well as providing the player with both a gun and a combat encounter in much tighter quarters.
![The second level section, a crystal cave and minor enemy arena.](DocImages/LevelSection2.png)
Once this area is cleared, however, the player exits the cave and is provided with a health box and a key, eliciting a sense of relief, safety, and progression.


From here, the player moves to the final area, a subterrainean acid lake with pushable boxes floating on the surface. The acid, returning the player to their last checkpoint immediately if hit, is a notably more concerning hazard than the crystals. In addition, the boxes bob slightly in the acid, making platforming noticeably more difficult to perform safely. This section also has a relatively low ceiling, leading to much more tense jumps. Once the player has obtained this area's key, they still are not safe. They must also make their way back out the way they came, before being able to relax properly.
![The third level section, with a number of floating boxes upon the lake of acid, and one spitter placed to incentivise utilising the player's ranged capabilities.](DocImages/LevelSection3.png)
Once this section is cleared and escaped, the player is home free, and all tension is relieved.


### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

### 2.2. Checkpoints

### 2.3. Chompers

### 2.4. Health Pickups

### 2.5. Keys

### 2.6. Moving Platforms

### 2.7. Passthrough Platforms

### 2.8. Spikes

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.