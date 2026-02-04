---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [humans, humanity, duine, daonna, azgaltur, insahn, menskelligh, hilde, hominum, mensch, chelovek]
age: "16 + 1d8 years"
height: "56 + 2d12 inches"
lifespan: "75 years"
requirements: "none"
size: medium
speed: "30 ft"
tags: [humanoid]
type: species
weight: 100 + (height roll * 2d4) lbs
---
> [!infobox|left]
> ![[z. assets/images/Human.png]]
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
Humans are the most common species in all the world, and can be found in most any climate or region, no matter how hostile or remote.  They typically reach physical maturity around age 18 and have a typical lifespan of around 75 years.  They are normally between 5 and 6 ½ feet tall and weigh between 120 and 250 pounds.
## Features
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Intrepid]]