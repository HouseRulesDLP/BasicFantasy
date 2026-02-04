---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [ogre, jotunla, fathachine, baraznuk, devinsanlar, norsanore, giantgen, riesen, gigantlyudi, ogres]
age: "16 + 1d10 years"
height: "80 + 2d10 inches"
lifespan: "80 years"
requirements: "STR 11+, CON 9+"
size: large
speed: "30 ft"
tags: [humanoid, giant]
type: species
weight: 300 + (height roll * 2d12) lbs
---
> [!infobox|left]
> ![[z. assets/images/Giantkin.png]]
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
Giantkin are believed to have the blood of true giants running in their veins. There are many myths and legends for how this came about (typically involving some mad god or wizard trying to breed a mighty army), but regardless of their origin, they are a true species capable of having their own young. They most often live in small communities on the outskirts of civilization, finding human-sized settlements and housing cramped and uncomfortable. The typical Giantkin stands between 7 and 8 1/2 feet in height and weights many times more than the average human. They mature at roughly the same rate as humans and a typical lifespan is somewhere around 80 years.
## Features
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Giant Strength]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Hardy]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Massive]]