---
cssclasses:
  - bfrpg
  - clean-embeds
---
- [Poisons and Antitoxins](#Poisons%20and%20Antitoxins)
	- [Poison Properties](#Poison%20Properties)
	- [Poison Descriptions](#Poison%20Descriptions)
		- [Arsenic](#Arsenic)
		- [Assassin's Blood](#Assassin's%20Blood)
		- [Basilisk Venom](#Basilisk%20Venom)
		- [Belladonna](#Belladonna)
		- [Black Lotus](#Black%20Lotus)
			- [Dust](#Dust)
			- [Essence](#Essence)
			- [Extract](#Extract)
		- [Burnt Othur Fumes](#Burnt%20Othur%20Fumes)
		- [Carcass Crawler Mucus](#Carcass%20Crawler%20Mucus)
		- [Cyanide](#Cyanide)
		- [Essence of Ether](#Essence%20of%20Ether)
		- [Giant Scorpion Venom](#Giant%20Scorpion%20Venom)
		- [Giant Snake Venom](#Giant%20Snake%20Venom)
		- [Giant Spider Venom](#Giant%20Spider%20Venom)
		- [Grey Lotus Dust](#Grey%20Lotus%20Dust)
		- [Malice](#Malice)
		- [Midnight Tears](#Midnight%20Tears)
		- [Oil of Taggit](#Oil%20of%20Taggit)
		- [Milk of the Poppy](#Milk%20of%20the%20Poppy)
		- [Pale Tincture](#Pale%20Tincture)
		- [Poison Ivy](#Poison%20Ivy)
		- [Purple Lotus Extract](#Purple%20Lotus%20Extract)
		- [Purple Worm Venom](#Purple%20Worm%20Venom)
		- [Rhododendron](#Rhododendron)
		- [Sleeping Drought](#Sleeping%20Drought)
		- [Snake Venom](#Snake%20Venom)
		- [Torpor](#Torpor)
		- [Truth Serum](#Truth%20Serum)
		- [Wyvern Venom](#Wyvern%20Venom)
		- [Yellow Lotus Smoke](#Yellow%20Lotus%20Smoke)

## Poisons and Antitoxins
Poisons come in many different forms and the table below serves as a non-exhaustive list of examples containing some of the more well-known poisons.

Antitoxins are derived from specific poisons and typically have a cost 2-3 times that of the poison that it counters.

Creating either a poison or antidote requires an alchemist (or someone with the potion/poison making skill), a recipe or sample and time.  See the rules on potion making for more details.

### Poison Properties
- **Rarity:** How hard it is to find the poison in question.  This is already factored into the price.
- **Save:** Which saving throw is used to resist the poison.
- **Potency:** The [Target Number](Introduction.md#Task%20Target%20Numbers) of the saving throw.
- **Application:** How the poison must be administered:
	- *Injection* - The skin of the target must be broken and the poison introduced into the bloodstream.
	- *Ingested* - The poison can be delivered in food or drink.  Injection is also effective.
	- *Inhaled* - These poisons typically come in the form of a gas or powder that must be inhaled.  Can also be ingested or injected.
	- *Contact* - Contact with bare skin is enough to administer this poison.  Injection, Ingestion and Inhalation also work.
- **Onset:** The amount of time before the victim will begin showing symptoms and must make their first saving throw.
- **Successful/Failed Save:** The effects of the poison if the victim succeeds or fails their saving throw.

<table>
    <thead>
        <tr>
            <th class="left-align"><b>Name</b></th>
            <th class="right-align"><b>Cost</b></th>
            <th><b>Rarity</b></th>
            <th><b>Save</b></th>
            <th><b>Potency</b></th>
            <th><b>Application</b></th>
            <th><b>Onset</b></th>
            <th class="left-align"><b>Successful Save</b></th>
            <th class="left-align"><b>Failed Save</b></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="left-align"><a class="internal-link" href="#arsenic">Arsenic</a></td>
            <td class="right-align">110sp</td>
            <td>Uncommon</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Ingested</td>
            <td>2p4 minutes</td>
            <td class="left-align">Poisoned for 1p4 turns, taking 1d4 poison damage per turn.</td>
            <td class="left-align">Poisoned for 3p4 turns, taking 1d4 poison damage per turn.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#Assassin's Blood">Assassin’s Blood</a></td>
            <td class="right-align">1,500sp</td>
            <td>Very Rare</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Injection</td>
            <td>Immediate</td>
            <td class="left-align">1d6 poison damage</td>
            <td class="left-align">Poisoned for 2p6 watches + 1d12 poison damage.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#basilisk venom">Basilisk Venom</a></td>
            <td class="right-align">600sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Hard (18+)</td>
            <td>Injection</td>
            <td>Immediate</td>
            <td class="left-align">Paralysis (1p4 rounds)</td>
            <td class="left-align">Paralysis + 1d6 poison damage / round for 2p4 rounds</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#belladonna">Belladonna</a></td>
            <td class="right-align">80sp</td>
            <td>Uncommon</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Ingested</td>
            <td>2p4 minutes</td>
            <td class="left-align">Take 1p4 poison damage and suffer Disadvantage on visual perception and ranged attacks for 1p6 rounds.</td>
            <td class="left-align">Poisoned for 1p4 turns, taking 1d4 poison damage per turn.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#dust">Black Lotus Dust</a></td>
            <td class="right-align">2,250sp</td>
            <td>Very Rare</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Inhaled</td>
            <td>Immediate</td>
            <td class="left-align">none</td>
            <td class="left-align">Poisoned until next Long Rest and permanently lose 1d6 Constitution.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#essence">Black Lotus Essence</a></td>
            <td class="right-align">3,380sp</td>
            <td>Very Rare</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Inhaled</td>
            <td>Immediate</td>
            <td class="left-align">none</td>
            <td class="left-align">Unconsciousness for 4p4 hours.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#extract">Black Lotus Extract</a></td>
            <td class="right-align">4,500sp</td>
            <td>Very Rare</td>
            <td>Doom</td>
            <td>Very Hard (21+)</td>
            <td>Ingested</td>
            <td>2p4 rounds</td>
            <td class="left-align">Loose half remaining HP.</td>
            <td class="left-align">Reduced to 0 HP, unconscious and dying.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#burnt othur fumes">Burnt Othur Fumes</a></td>
            <td class="right-align">1,350sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Inhaled</td>
            <td>Immediate</td>
            <td class="left-align">none</td>
            <td class="left-align">Poisoned and 3d6 poison damage plus 1d6 poison damage / round for 2p4. rounds.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#carcass crawler mucus">Carcass Crawler Mucus</a></td>
            <td class="right-align">680sp</td>
            <td>Uncommon</td>
            <td>Hold</td>
            <td>Moderate (12+)</td>
            <td>Contact</td>
            <td>Immediate</td>
            <td class="left-align">Poisoned for 1p4 rounds</td>
            <td class="left-align">Paralyzed for 2p4 rounds</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#cyanide">Cyanide</a></td>
            <td class="right-align">450sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Ingested</td>
            <td>2p4 rounds</td>
            <td class="left-align">Take 3d6 poison damage and Poisoned for 1p4 Turns.</td>
            <td class="left-align">Take 6d6 poison damage and Poisoned for 3p4 Turns.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#essence of ether">Essence of Ether</a></td>
            <td class="right-align">200sp</td>
            <td>Uncommon</td>
            <td>Hold</td>
            <td>Tricky (15+)</td>
            <td>Inhaled</td>
            <td>Immediate</td>
            <td class="left-align">Poisoned for 1p6 rounds</td>
            <td class="left-align">Fall unconscious for 1p4 Watches.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#giant scorpion venom">Giant Scorpion Venom</a></td>
            <td class="right-align">600sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Injection</td>
            <td>Immediate</td>
            <td class="left-align">Take 3d6 poison damage.</td>
            <td class="left-align">Take 6d6 poison damage and poisoned for 2p4 minutes.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#giant snake venom">Giant Snake Venom</a></td>
            <td class="right-align">510sp</td>
            <td>Uncommon</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Injection</td>
            <td>Immediate</td>
            <td class="left-align">Poisoned for 2p4 rounds, taking 1d4 poison damage per round.</td>
            <td class="left-align">Poisoned for 3p6 rounds, taking 1d4 poison damage per round.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#giant spider venom">Giant Spider Venom</a></td>
            <td class="right-align">300sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Injection</td>
            <td>Immediate</td>
            <td class="left-align">Take 1d6 poison damage.  If reduced to 0 HP, automatically stablized.</td>
            <td class="left-align">Take 2d6 poison damage and Paralyzed + Poisoned for 3p4 Turns.  If reduced to 0 HP, automatically stablized.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#grey lotus dust">Grey Lotus Dust</a></td>
            <td class="right-align">1,130sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Inhaled</td>
            <td>Immediate</td>
            <td class="left-align">none</td>
            <td class="left-align">Berserk for 3p6 rounds.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#malice">Malice</a></td>
            <td class="right-align">900sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Contact</td>
            <td>Immediate</td>
            <td class="left-align">Poisoned for 1p4 rounds</td>
            <td class="left-align">Poisoned and Blinded for 2p6 Turns</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#midnight tears">Midnight Tears</a></td>
            <td class="right-align">1,500sp</td>
            <td>Very Rare</td>
            <td>Doom</td>
            <td>Hard (18+)</td>
            <td>Ingested</td>
            <td>special</td>
            <td class="left-align">Poisoned plus 1d4 poison damage / hour while asleep.</td>
            <td class="left-align">Poisoned + 1d6 damage / hour while asleep.  Cannot awaken normally.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#milk of the poppy">Milk of the Poppy</a></td>
            <td class="right-align">120sp</td>
            <td>Rare</td>
            <td>Hold</td>
            <td>Hard (18+)</td>
            <td>Ingested</td>
            <td>2p4 minutes</td>
            <td class="left-align">Poisoned for 1p4 turns.</td>
            <td class="left-align">Poisoned and Slowed for 2p6 Turns.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#oil of taggit">Oil of Taggit</a></td>
            <td class="right-align">90sp</td>
            <td>Rare</td>
            <td>Hold</td>
            <td>Moderate (12+)</td>
            <td>Ingested</td>
            <td>2p4 rounds</td>
            <td class="left-align">Poisoned for 1p4 rounds</td>
            <td class="left-align">Fall unconscious for 1p4 Watches.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#pale tincture">Pale Tincture</a></td>
            <td class="right-align">1,880sp</td>
            <td>Very Rare</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Contact</td>
            <td>2p4 minutes</td>
            <td class="left-align">none</td>
            <td class="left-align">Poisoned + 1d6 damage per long rest.  No natural healing.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#poison ivy">Poison Ivy</a></td>
            <td class="right-align">60sp</td>
            <td>Common</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Contact</td>
            <td>2p4 minutes</td>
            <td class="left-align">none</td>
            <td class="left-align">Poisoned for 2p6 Turns</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#purple lotus extract">Purple Lotus Extract</a></td>
            <td class="right-align">680sp</td>
            <td>Rare</td>
            <td>Hold</td>
            <td>Tricky (15+)</td>
            <td>Ingested</td>
            <td>2p4 minutes</td>
            <td class="left-align">Poisoned for 2p4 rounds.</td>
            <td class="left-align">Poisoned and Paralyzed for 4p6 minutes.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#purple worm venom">Purple Worm Venom</a></td>
            <td class="right-align">3,000sp</td>
            <td>Very Rare</td>
            <td>Doom</td>
            <td>Hard (18+)</td>
            <td>Injection</td>
            <td>Immediate</td>
            <td class="left-align">Poisoned for 3p4 rounds, taking 1d6 poison damage per round.</td>
            <td class="left-align">Poisoned for 3p6 rounds, taking 1d8 poison damage per round.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#rhododendron">Rhododendron</a></td>
            <td class="right-align">80sp</td>
            <td>Uncommon</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Ingested</td>
            <td>2p4 Turns</td>
            <td class="left-align">Poisoned for 2p4 Turns.</td>
            <td class="left-align">Poisoned and ½ Strength until next Long Rest.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#sleeping drought">Sleeping Drought</a></td>
            <td class="right-align">30sp</td>
            <td>Common</td>
            <td>Hold</td>
            <td>Tricky (15+)</td>
            <td>Ingested</td>
            <td>2p4 rounds</td>
            <td class="left-align">Poisoned for 1p4 rounds</td>
            <td class="left-align">Fall unconscious for 2p6 Turns</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#snake venom">Snake Venom</a></td>
            <td class="right-align">40sp</td>
            <td>Common</td>
            <td>Doom</td>
            <td>Moderate (12+)</td>
            <td>Injection</td>
            <td>1p4 minutes</td>
            <td class="left-align">none</td>
            <td class="left-align">Poisoned + 1d4 poison damage / round for 2p4 rounds</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#torpor">Torpor</a></td>
            <td class="right-align">230sp</td>
            <td>Uncommon</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Ingested</td>
            <td>2p4 minutes</td>
            <td class="left-align">none</td>
            <td class="left-align">Poisoned and unconscious for 6p6 hours.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#truth serum">Truth Serum</a></td>
            <td class="right-align">1,000sp</td>
            <td>Very Rare</td>
            <td>Spell</td>
            <td>Moderate (12+)</td>
            <td>Ingested</td>
            <td>2p4 minutes</td>
            <td class="left-align">none</td>
            <td class="left-align">Cannot knowingly speak a lie for 2p6 turns.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#wyvern venom">Wyvern Venom</a></td>
            <td class="right-align">680sp</td>
            <td>Rare</td>
            <td>Doom</td>
            <td>Tricky (15+)</td>
            <td>Injection</td>
            <td>Immediate</td>
            <td class="left-align">Poisoned for 2p4 rounds, taking 1d4 poison damage per round.</td>
            <td class="left-align">Poisoned for 3p4 rounds, taking 1d6 poison damage per round.</td>
        </tr>
        <tr>
            <td class="left-align"><a class="internal-link" href="#yellow lotus smoke">Yellow Lotus Smoke</a></td>
            <td class="right-align">1,130sp</td>
            <td>Very Rare</td>
            <td>Spell</td>
            <td>Moderate (12+)</td>
            <td>Inhaled</td>
            <td>2p4 rounds</td>
            <td class="left-align">Poisoned for 2p4 rounds.</td>
            <td class="left-align">Poisoned, Paralyzed and Blinded for 4p4 hours.</td>
        </tr>
    </tbody>
</table>

### Poison Descriptions
#### Arsenic
A naturally occurring substance, this poison is pale yellow in color and tastes slightly bitter, though it is odorless.  Victims suffer abdominal pain, vomiting, diarrhea and other digestive ailments.

#### Assassin's Blood
An alchemical mixture comprised of several poisonous plants and fungi, this poison is colorless though it has a faint ferric scent and a prominent bitter taste.  This poison restricts the victim's breathing.

#### Basilisk Venom
This poison extracted from the venom glands of a basilisk has an immediate effect of paralysis.

#### Belladonna
Also known as Nightshade, this preparation based on the black berries of belladonna causes at first visual disorders (dilation of the pupils) then an acceleration of the heartbeat and internal bleeding. The poison looks like a black liquid which however passes relatively unnoticed in food or wine.

#### Black Lotus
A lotus flower with large black blossoms that grows in the deepest of jungles.

##### Dust
Breathing the dark grey pollen of the infamous black lotus renders the victim weak and sickly, potentially unto death for those of weak constitution.

##### Essence
The scent of the black lotus induces a coma-like sleep haunted by vivid and often terrifying dreams.

##### Extract
Refined from the juice of the black lotus, this is one of the most deadly of poisons, immediately shutting down the victims cardio-vascular system.

#### Burnt Othur Fumes
The smoke of burnt othur plant causes pain and inflammation of the lungs, leading to extreme coughing, potentially leading to death via asphyxiation.

#### Carcass Crawler Mucus
This powerful paralytic must be harvested from the mucous glads of a dead or incapacitated carcass crawler.  These secretions are known to have a numbing paralytic effect.

#### Cyanide
This blackish poison has a characteristic odor of bitter almonds. Sold in salt-like powder, it causes death in just a few seconds.  Initial symptoms include headache, dizziness, increased heart rate, shortness of breath and vomiting.  This is quickly followed by seizures, loss of consciousness and cardiac arrest.

#### Essence of Ether
An alchemical mixture comprised of several species of bog plants.  The fumes of this liquid will render a subject unconscious for several hours.  Frequently used as an anesthetic.

#### Giant Scorpion Venom
This poison must be harvested from a dead or incapacitated giant scorpion.  This venom causes muscle contractions and can also cause cardio-vascular complications.

#### Giant Snake Venom
This poison must be harvested from a dead or incapacitated giant poisonous snake.  It has the same properties as [[Snake Venom](#Snake%20Venom)], but greater in quantity and intensity.

#### Giant Spider Venom
This poison must be harvested from a dead or incapacitated giant spider.  This necrotic venom damages flesh and muscle, causing paralysis and (potentially) a gruesome death.

#### Grey Lotus Dust
A flower that grows in fetid tropical and subtropical swamps.  It's pollen is known to cause a homicidal rage in those that inhale too deeply.

#### Malice
This alchemical mixture is comprised of several species of fungi native to mountainous regions.  It attacks the victim's eyesight, leading to effects from blurred vision to full blindness for an hour or more.

#### Midnight Tears
A colorless, odorless, and tasteless liquid distilled from the extract of several hundred species of poisonous plants, fungi, and animals. Exposed creatures suffer no effect until until they enter a deep sleep (long rest), if it has not been neutralized before then.  Victims who fail their save do not wake up naturally and must pass another Doom save to be woken up with outside assistance.

#### Oil of Taggit
This poison is refined from the sap of the highland Taggit Bush's root.  Victims of this poison fall into a deep slumber.  However, it lacks any numbing properties, rendering it ineffective as an anesthetic.

#### Milk of the Poppy
Refined from the juices of the poppy, this compound will render creatures sluggish and insensate, often for hours.  Some cultures mix this with wine to be used as a painkiller and sleep aid.

#### Pale Tincture
An alchemical mixture of liquid extracts from several poisonous animals, this poison is odorless and tasteless, though it is milky white in color.  It causes fever and sweating in its victims, who are incapable of natural healing until the poison has run its course.

#### Poison Ivy
The resin scraped off the leaves of the poison ivy plant causes itching and irritation to exposed skin.

#### Purple Lotus Extract
Refined from the juice of the purple lotus plant (which grows in fetid swamp and marshland), this poison paralyzes the victim, but leaves them fully aware of their surroundings.

#### Purple Worm Venom
This poison must be harvested from a dead or incapacitated purple worm.  It has many properties in common with [Giant Scorpion Venom](#Giant%20Scorpion%20Venom).

#### Rhododendron
The poison made from the pollen and nectar of certain types of Rhododendron plant causes severe diarrhea and vomiting.

#### Sleeping Drought
A mixture of various plants, in small doses, this is a simple sleep aid.  In larger doses, it can render a victim unconscious for an hour or more.

#### Snake Venom
Venom harvested from poisonous snakes, the most notorious of which is the Black Adder.  This neurotoxin causes heart palpitations and distressed breathing.

#### Torpor
An alchemical mixture comprised of several species of highland plants, this poison is faintly green in color and has a weak pine scent, though it has no taste.  This compound renders victims unconscious (or at least groggy) for several hours.  In small doses, it is regularly used as an anesthetic.

#### Truth Serum
An alchemical concoction created from a multitude of ingredients, a recipe known only to some of the best alchemists, and is entirely colorless, odorless, and tasteless.  Exposed victims are compelled to speak truthfully for the poison's duration.

#### Wyvern Venom
This poison must be harvested from a dead or incapacitated wyvern.  This particularly deadly venom causes extensive internal hemorrhaging.

#### Yellow Lotus Smoke
The yellow lotus plant, native to various temperate to tropical swamps and bogs, burns to produce a yellowish smoke.  This smoke is known to cause trance-like visions and is frequently used in oracular rituals.
