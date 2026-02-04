---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [hin, hobs, hobbish, neachbeag, rakas, ahzinsahn, litenmenskeligh, hob, parvushom, kleinermensch, malychelovek, halfling, halflings]
age: "20 + 3d6 years"
height: "25 + 2d6 inches"
lifespan: "120 years"
requirements: "DEX 9+, WIS 9+"
size: small
speed: "25 ft"
tags: [humanoid]
type: species
weight: 29 + (height roll * 1d3) lbs
---
> [!infobox|left]
> ![[z. assets/images/Hob.png]]
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
Aside from their height, slightly pointed ears and thick-soled hairy feet, hobs seem to be the most similar to humans among the great variety of species.  Even their own ethnicities seem to follow the same patterns as those of humans.  They are most frequently found living among humans, though also occasionally among elves, dwarves and other cultures.  There do exist, however, a handful of hob-centric towns, villages and nomadic troupes scattered around the many kingdoms.

Hobs mature at the same rate as humans but live slightly longer, some reaching as much as 120 years.  However, they are among the smallest of species, typically averaging between 3 and 4 feet in height and 30 to 60 pounds.
## Features
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Fortitude of Iron]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Small Stature]]