---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [goblins, bilog, urzog, gulyabaneh, gooblin, orqui, kobalus, kobold, domovoy]
age: "10 + 1d4 years"
height: "46 + 2d8 inches"
lifespan: "50 years"
requirements: "DEX 9+, CON 9+"
size: small
speed: "25 ft"
tags: [humanoid, fae]
type: species
weight: 55 + (height roll * 2d4) lbs
---
> [!infobox|left]
> ![[z. assets/images/Goblin.png]]
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
Goblins are a species of naturally nocturnal fae humanoids most commonly found in the woods and mountains.  They stand 4 to 5 feet in height, have pointed ears, cat-like eyes, sharp teeth, long arms and spare or patchy body hair.  Their skin tones are some shade of gray, red, yellow or green.  They typically stand between 4 and 5 feet in height and have a lifespan rarely exceeding 50 years.

Their features are superficially similar to those of Orcs, causing some to believe that the species are related but neither Orcs nor Goblins consider this to be true.
## Features
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Fae Blooded]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Low-Light Vision]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Small Stature]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#True Name]]