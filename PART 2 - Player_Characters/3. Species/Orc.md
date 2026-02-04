---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [targh, orcs, mouk, ork, ghash, domuz, gries, orc, ork, sveeniyah]
age: "14 + 1d6 years"
height: "68 + 2d8 inches"
lifespan: "65 years"
requirements: "STR 9+, CON 9+"
size: medium
speed: "30 ft"
tags: [humanoid]
type: species
weight: 175 + (height roll * 2d6) lbs
---
> [!infobox|left]
> ![[z. assets/images/Orc.png]]
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
Orcs are a physically powerful race slightly taller than humans but much stockier and more muscled.  They typically stand between 6 and 7 feet in height, but their naturally stooped posture makes them seem not much taller than the average human.  They have goat-like eyes, little hair, large pointed ears and a pair of tusks that protrude from their lower jaw.  Their skin is typically shades of grey, red, yellow or green.  The orcish lifespan is slightly less than that of a human, typically maturing around age 15 and living around 65 years.

Their features are superficially similar to those of Goblins, causing some to believe that the species are related but neither Orcs nor Goblins consider this to be true.
## Features
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Colorblind (cool)]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Infravision]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Relentless Endurance]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Strong Back]]