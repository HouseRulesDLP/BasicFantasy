---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [dweorg, dyerven, gnome, svartal, khazad, dwarfs, dwarves, dwarfish, beag, troich, boogursh, dvarg, picinauco, pumilio, zwerg, karlikovyy]
age: "25 + 2d10 years"
height: "46 + 1d6 + 1d8 inches"
lifespan: "255 years"
requirements: "STR 9+, CON 9+"
size: medium
speed: "25 ft"
tags: [humanoid, fae/earth]
type: species
weight: 80 + (height roll * 2d8) lbs
---
> [!infobox|left]
> ![[z. assets/images/Dwarf.png]]
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
Dwarves are a short, stocky species; both male and female Dwarves average around 4 to 5 feet in height, yet weigh as much as a full grown human. Their long hair and thick beards are usually auburn, dark brown, gray or black. Many Dwarven cultures take great pride in their beards, sometimes braiding or forking them while others choose to shave. They have a fair to ruddy complexion. Dwarves have stout frames and a strong, muscular build. They are rugged and resilient, with the capacity to endure great hardships. They typically mature at the same rate as humans, have a lifespan of three to four centuries and usually aren’t considered adults until at least the age of 50.

## Features
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Dust of Ages]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Fortitude of Iron]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Hardy]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Low-Light Vision]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#True Name]]
