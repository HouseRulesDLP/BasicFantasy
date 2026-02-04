---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [quendi, elfs, siog, aelf, ellon, perreh, alv,dryadalis, alph, alfar, aelph, erle, olve]
age: "80 + 2d10 years"
height: "52 + 2d10 inches"
lifespan: "400 years"
requirements: "DEX 9+, CHA 9+"
size: medium
speed: "35 ft"
tags: [humanoid, fae]
type: species
weight: 80 + (height roll * 2d4) lbs
---
> [!infobox|left]
> ![[z. assets/images/Elf.png]]
> ###### `=this.file.name`
> ```dataviewjs
> let pg = dv.current(); // only look at the current page.
> let table = "###### Attributes\n";
> table += "| Attribute | Value |\n" +
>             "| --------- | ----- |\n"; // table headers
> let tags = Object.entries(pg.tags).map(([key, value]) => value).join(', ');
> dv.header(3, pg.title);
> table += "| **Requirements:** | " + pg.requirements + " |\n";
> table += "| **Starting Age:** | " + pg.age + " |\n";
> table += "| **Height:** | " + pg.height + " |\n";
> table += "| **Weight:** | " + pg.weight + " |\n";
> table += "| **Size:** | " + pg.size + " |\n";
> table += "| **Speed** | " + pg.speed + " |\n";
> table += "| **Tags:** | " + tags + " |\n";
> dv.paragraph(table);
> ```

# `=this.file.name`
###### (**AKA**: `=this.aliases`)
Elves are as much of the Fey world as they are of the mortal realm.  While this has granted them many advantages, such as a long life (typically living to be 400 years or more and not considered adults until nearly a century old) and a greater capacity for resisting baleful magics, it also makes them seem among the most alien of all the common species.  They are slender in build and typically average around 5' 3" and 135 lbs.

## Features
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Autumn Folk]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Fae Blooded]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Iron Allergy]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Keen Senses]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#True Name]]