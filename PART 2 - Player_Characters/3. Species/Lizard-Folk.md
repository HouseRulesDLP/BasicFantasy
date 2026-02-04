---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: [slith, saurian, saurians, lacerta, hish, sleestack]
age: "10 + 1d6 years"
height: 68 + 2d8 inches"
lifespan: "75 years"
requirements: "STR 9+, CON 9+"
size: medium
speed: "30 ft"
tags: [humanoid, reptile]
type: species
weight: 150 + (height roll * 2d6) lbs
---
> [!infobox|left]
> ![[z. assets/images/lizard-folk.png]]
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
Lizard-Folk typically stand between 6 and 7 feet in height, weighing in between 150 and 350 pounds.  They have tails they use for balance and a scaly hide that can turn light blows.  They mature quicker then humans, reaching adulthood by 15 years of age, and have a lifespan of around 60 years.  

There are three primary subspecies of lizard-folk: aquatic, desert and temperate.

### Aquatic
Aquatic lizard-folk have adapted to surviving in water.

### Desert
Desert lizard-folk have many ways of surviving the desert.

### Temperate
Well-suited to the plains and forests of temperate climes.
## Features
All Lizard-Folk have the following 5 features in common:
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Colorblind (full)]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Fallen Empire]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Natural Weapons (fangs)]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Scales]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Vulnerability (cold)]]

---
The remaining features depend on which subspecies of reptilian you are.

### Aquatic
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Lung Capacity]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Swimming]]
### Desert
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Desert Adaptation]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Sure-Footed (sand)]]
### Temperate
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Camouflage]]
![[PART 2 - Player_Characters/3. Species/z. Species_Abilities#Wide Vision]]