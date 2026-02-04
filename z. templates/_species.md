---
cssclasses:
  - bfrpg-srd
  - bfrpg
  - clean-embeds
aliases: []
age: "## + #d# years"
height: "## + #d# inches"
lifespan: "### years"
requirements: ""
size: medium
speed: "30 ft"
tags: [humanoid]
type: species
weight: ### + (height roll * #d#) lbs
---
> [!infobox|left]
> ![[_images/species_pic.png]]
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

## Features
