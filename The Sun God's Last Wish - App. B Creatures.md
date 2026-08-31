# Appendix B: Creatures

This appendix contains the full stat blocks for every named combatant in *Vaelithra V: The Sun God's Last Wish*, referenced throughout *Parts III* and *IV*. Unlike reflavored *Monster Manual* stock, these are fully custom creatures.

## Anthony Ra, Sun Ray I

Head of House Ra. A man in his fifties, hair beginning to gray, but still carrying himself like the warrior he's always been — his gaze sharp, but calm. He wears a simple golden Haori marked with House Ra's sun emblem. Anthony isn't a man of many words, but he's quietly, deeply proud of his son, Fradonic. He fights the Avatar of Kael'zar alongside the six other Sun Rays to protect House Ra, until his own sword breaks beneath him.

```statblock
layout: Basic 5e Layout
source: Vaelithra V - The Sun God's Last Wish
name: Anthony Ra, Sun Ray I
size: Medium
type: Humanoid
alignment: Lawful Good
cr: 8
ac: 18
hp: 120
hit_dice: 16d8+48
speed: 30ft
stats: [18,16,16,13,16,16]
saves:
  - STR: 7
  - CON: 6
  - WIS: 6
skillsaves:
  - Insight: 6
  - Intimidation: 6
  - Perception: 5
damage_resistances: Radiant
senses: Passive Perception 15
languages: Common
traits:
  - name: House Ra's Blessing
    desc: Anthony's weapon attacks are magical and deal an additional 4 (1d8) Radiant damage.
  - name: Unshakable Resolve
    desc: Anthony has advantage on saving throws against being Frightened.
actions:
  - name: Multiattack
    desc: Anthony makes two Katana attacks.
  - name: Katana
    desc: "Melee Attack Roll: +7, reach 5 ft. Hit: 8 (1d8 + 4) Slashing damage plus 4 (1d8) Radiant damage."
creature: Anthony Ra, Sun Ray I
```

## Vikram Sanjaya, Chief of Soyo Gumi

Chief of Soyo Gumi, commanding all seven Sun Ray Commanders as well as every member of Nisshoku Gumi and Gyokko Gumi. He attends Fradonic's induction as Sun Ray VII as guest of honor, then fights on the front line beside Anthony and the Sun Rays when the Avatar of Kael'zar arrives — the one who calls all three branches of Soyo Gumi to stand together "as Dewanegara" in the adventure's darkest hour.

```statblock
layout: Basic 5e Layout
source: Vaelithra V - The Sun God's Last Wish
name: Vikram Sanjaya, Chief of Soyo Gumi
size: Medium
type: Humanoid
alignment: Lawful Neutral
cr: 9
ac: 19
hp: 135
hit_dice: 18d8+54
speed: 30ft
stats: [18,16,16,14,17,18]
saves:
  - STR: 7
  - CON: 6
  - WIS: 6
skillsaves:
  - Intimidation: 7
  - Insight: 6
  - Perception: 6
senses: Passive Perception 16
languages: Common
traits:
  - name: Commander's Presence
    desc: While Vikram is within 30 feet of an ally that can see or hear him, that ally has advantage on saving throws against being Frightened.
actions:
  - name: Multiattack
    desc: Vikram makes two Commander's Blade attacks.
  - name: Commander's Blade
    desc: "Melee Attack Roll: +7, reach 5 ft. Hit: 10 (1d10 + 5) Slashing damage."
  - name: Rallying Command (1/Day)
    desc: Vikram shouts an order to every ally he can see within 60 feet. Each of those allies can use their reaction to make one weapon attack or move up to their speed.
creature: Vikram Sanjaya, Chief of Soyo Gumi
```

## Sera

Lady Miji's personal attendant — or so House Ra believes. In truth, Sera is the **Human Vaelithra** bound to the fragment of Vaeil's soul sealed within the Solar Crest, having accompanied every generation of Lady House Ra for centuries while she waited for the next Keeper to be chosen. She almost never fights directly, preferring to protect and guide those she serves.

```statblock
layout: Basic 5e Layout
source: Vaelithra V - The Sun God's Last Wish
name: Sera
size: Medium
type: Humanoid
alignment: Neutral Good
cr: 2
ac: 13
hp: 38
hit_dice: 7d8+7
speed: 30ft
stats: [10,14,13,15,18,16]
skillsaves:
  - Insight: 7
  - Perception: 7
  - History: 5
senses: Passive Perception 17
languages: Common, Celestial
traits:
  - name: Fragment of Vaeil
    desc: Sera is the Human Vaelithra bound to the Solar Crest. She almost never fights directly, preferring to protect and guide the ones she serves.
  - name: Innate Spellcasting
    desc: |-
      Sera's spellcasting ability is Wisdom (spell save DC 15). She can innately cast the following spells, requiring no material components:

       At will: guidance, light
       1/day each: sanctuary, lesser restoration
actions:
  - name: Unarmed Strike
    desc: "Melee Attack Roll: +2, reach 5 ft. Hit: 2 Bludgeoning damage."
creature: Sera
```

## Miji Ra, Lady of House Ra

Lady of House Ra, a Silver Dragonborn who welcomes everyone with unreserved warmth — the exact opposite of her husband Anthony. She laughs often, teases Fradonic mercilessly, and does everything she can to put his fiancée Lambda at ease.

```statblock
layout: Basic 5e Layout
source: Vaelithra V - The Sun God's Last Wish
name: Miji Ra, Lady of House Ra
size: Medium
type: Humanoid (Silver Dragonborn)
alignment: Neutral Good
cr: 2
ac: 14
hp: 44
hit_dice: 8d8+8
speed: 30ft
stats: [12,12,13,13,15,18]
skillsaves:
  - Insight: 5
  - Persuasion: 6
damage_resistances: Cold
senses: Passive Perception 12
languages: Common, Draconic
traits:
  - name: Breath Weapon (Recharge 5-6)
    desc: Miji exhales a blast of frost in a 15-foot cone. Each creature in the area must make a DC 12 Constitution saving throw, taking 11 (2d10) Cold damage on a failed save, or half as much on a success.
actions:
  - name: Fan
    desc: "Melee Attack Roll: +3, reach 5 ft. Hit: 3 (1d4 + 1) Bludgeoning damage."
creature: Miji Ra, Lady of House Ra
```

## Lambda Rospira

A red-skinned Tiefling with curving black horns, Fradonic Ra's fiancée. She isn't from a noble family, and was visibly nervous the first time she was introduced to House Ra — until Lady Miji welcomed her as family on the spot. She plays no combat role in this adventure; she is the reason Fradonic keeps getting back up.

```statblock
layout: Basic 5e Layout
source: Vaelithra V - The Sun God's Last Wish
name: Lambda Rospira
size: Medium
type: Humanoid (Tiefling)
alignment: Neutral Good
cr: 1/2
ac: 12
hp: 27
hit_dice: 6d8
speed: 30ft
stats: [10,13,11,12,14,15]
skillsaves:
  - Insight: 4
  - Persuasion: 4
damage_resistances: Fire
senses: Darkvision 60 ft., Passive Perception 12
languages: Common, Infernal
actions:
  - name: Dagger
    desc: "Melee Attack Roll: +3, reach 5 ft. Hit: 3 (1d4 + 1) Piercing damage."
creature: Lambda Rospira
```

## Fradonic Ra, Heir of the Sun

House Ra's heir and newly-inducted Sun Ray VII, awakened as the **Heir of the Sun** in *Part IV* once the Solar Crest's fragment of Vaeil's soul fully passes into him. Silver dragon scales spread across his arms, his eyes burn gold, and dragon wings wreathed in sunlight unfurl from his back. This stat block replaces any prior representation of Fradonic once he awakens; he fights beside the party for the remainder of the adventure.

```statblock
layout: Basic 5e Layout
source: Vaelithra V - The Sun God's Last Wish
name: Fradonic Ra, Heir of the Sun
size: Medium
type: Humanoid (Half Dragonborn, Human)
alignment: Lawful Good
cr: 10
ac: 20
hp: 210
hit_dice: 20d8+120
speed: 40ft
stats: [18,24,22,16,18,20]
saves:
  - DEX: 11
  - CON: 10
  - WIS: 8
skillsaves:
  - Acrobatics: 11
  - Athletics: 8
  - Perception: 8
  - Stealth: 15
damage_resistances: Cold, Radiant, Necrotic
damage_immunities: Fire
condition_immunities: Frightened
senses: Darkvision 60 ft., Passive Perception 18
languages: Common, Draconic
traits:
  - name: Blessing of Ra
    desc: Fradonic's weapon attacks are magical and deal an additional 9 (2d8) Radiant damage.
  - name: Solar Awakening
    desc: When this statblock first enters combat, Fradonic regains all hit points, ends all conditions affecting him, and every allied creature within 30 feet regains 20 hit points.
  - name: Sun's Grace
    desc: Fradonic ignores difficult terrain and opportunity attacks while moving.
  - name: Dragonblood Awakening
    desc: Once per turn, when Fradonic deals Radiant damage, he may immediately move up to 15 feet without provoking opportunity attacks.
actions:
  - name: Multiattack
    desc: Fradonic makes three Solar Fang attacks.
  - name: Solar Fang
    desc: "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 10 (1d8 + 6) Piercing damage plus 18 (4d8) Radiant damage."
  - name: Solar Breath (Recharge 5-6)
    desc: Fradonic exhales divine sunlight in a 30-foot cone. Creatures in the area must make a DC 18 Dexterity saving throw, taking 45 (10d8) Radiant damage on a failed save, or half as much on a success. Fiends have disadvantage on this saving throw.
  - name: Dawn Rush
    desc: Fradonic moves up to his speed without provoking opportunity attacks. He may make one Solar Fang attack against every creature he moves adjacent to during this movement (maximum three attacks).
bonus_actions:
  - name: Ray Step
    desc: Fradonic teleports up to 30 feet to an unoccupied space he can see that is in bright light or sunlight.
reactions:
  - name: Sun's Protection
    desc: When an ally within 30 feet is hit by an attack, Fradonic flashes between them. The attack is redirected to Fradonic instead, and he has resistance against all damage from that attack.
legendary_description: Fradonic can take 2 legendary actions, choosing from the options below. Only one legendary action may be used at a time and only at the end of another creature's turn.
legendary_actions:
  - name: Solar Fang
    desc: Fradonic makes one Solar Fang attack.
  - name: Flash Step (Costs 1)
    desc: Fradonic teleports up to 20 feet.
  - name: Brilliant Slash (Costs 2)
    desc: Fradonic makes one Solar Fang attack. On a hit, the target emits bright light until the end of Fradonic's next turn and cannot benefit from being Invisible.
creature: Fradonic Ra, Heir of the Sun
```

## Avatar of Kael'zar

A towering, fire-wreathed figure that descends on Atrakaj demanding "Ra's inheritance," burning through the city's strongest warriors with almost gentle inevitability. This is not the true Kael'zar, only an Avatar — a fragment sent to answer one question: does Ra's successor truly exist? Everything it does over the course of *Parts III* and *IV*, including the violence, is in service of that test. It withdraws, satisfied rather than defeated, once Fradonic proves himself in the climactic duel of *Part IV*.

```statblock
layout: Basic 5e Layout
source: Vaelithra V - The Sun God's Last Wish
name: Avatar of Kael'zar
size: Large
type: Fiend (Avatar, Demon)
alignment: Chaotic Evil
cr: 12
ac: 19
hp: 315
hit_dice: 30d10+150
speed: 40ft
stats: [24,18,20,16,18,22]
saves:
  - STR: 11
  - CON: 10
  - WIS: 8
  - CHA: 10
skillsaves:
  - Athletics: 11
  - Intimidation: 10
  - Perception: 8
damage_immunities: Fire
damage_resistances: Cold, Lightning, Necrotic; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks
condition_immunities: Charmed, Frightened
senses: Truesight 120 ft., Passive Perception 18
languages: Abyssal, Infernal, Common, Telepathy 120 ft.
traits:
  - name: Legendary Resistance (3/Day)
    desc: If Avatar of Kael'zar fails a saving throw, it can choose to succeed instead.
  - name: Avatar Manifestation
    desc: Reducing Avatar of Kael'zar to 0 hit points does not destroy Kael'zar. Instead, the avatar disperses into infernal flames and ash before disappearing.
  - name: Aura of Wrath
    desc: Creatures that start their turn within 20 feet of Kael'zar must succeed on a DC 18 Wisdom saving throw or have disadvantage on attack rolls against creatures other than Kael'zar until the start of their next turn.
  - name: Living Wrath
    desc: Kael'zar's claw attacks are magical and ignore resistance to Fire damage.
  - name: Burning Rage
    desc: While below half hit points, Avatar of Kael'zar deals an extra 9 (2d8) Fire damage with all melee attacks.
actions:
  - name: Multiattack
    desc: Avatar of Kael'zar makes three Wrath Claw attacks.
  - name: Wrath Claw
    desc: "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 19 (2d10 + 8) Slashing damage plus 13 (3d8) Fire damage."
  - name: Infernal Rend (Recharge 5-6)
    desc: Kael'zar tears through reality with blazing claws. All creatures in a 20-foot cone must make a DC 18 Dexterity saving throw, taking 36 (8d8) Fire damage plus 18 (4d8) Slashing damage on a failed save, or half as much on a successful one.
  - name: Wrath Eruption (Recharge 6)
    desc: Kael'zar slams both claws into the ground. Each creature within 30 feet must succeed on a DC 18 Strength saving throw or take 31 (7d8) Fire damage, be knocked prone, and pushed 15 feet away. On a success, the creature takes half damage and isn't pushed or knocked prone.
  - name: Brand of Wrath
    desc: Kael'zar marks one creature it can see within 60 feet. Until the end of Kael'zar's next turn, the marked creature cannot benefit from being Invisible, and Kael'zar deals an extra 9 (2d8) Fire damage against it.
reactions:
  - name: Burning Rebuke
    desc: When a creature within 10 feet damages Kael'zar, that creature must succeed on a DC 18 Dexterity saving throw or take 13 (3d8) Fire damage.
legendary_description: Avatar of Kael'zar can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature's turn.
legendary_actions:
  - name: Wrath Claw
    desc: Kael'zar makes one Wrath Claw attack.
  - name: Relentless Pursuit (Costs 1)
    desc: Kael'zar moves up to half his speed without provoking opportunity attacks.
  - name: Crushing Presence (Costs 2)
    desc: One creature Kael'zar can see within 30 feet must succeed on a DC 18 Strength saving throw or be knocked prone.
  - name: Infernal Roar (Costs 3)
    desc: Each creature of Kael'zar's choice within 30 feet must succeed on a DC 18 Wisdom saving throw or become Frightened until the end of its next turn.
lair_actions:
  - name: Hellfire Burst
    desc: At initiative count 20 (losing initiative ties), infernal flames erupt at a point Kael'zar can see within 120 feet. Creatures within a 15-foot radius must make a DC 18 Dexterity saving throw, taking 22 (4d10) Fire damage on a failed save, or half as much on a successful one.
  - name: Wrathful Tremor
    desc: The battlefield violently shakes. Each creature of Kael'zar's choice on the ground must succeed on a DC 18 Dexterity saving throw or fall prone.
  - name: Oppressive Presence
    desc: Kael'zar's aura expands until initiative count 20 of the next round. The radius of Aura of Wrath increases to 40 feet.
creature: Avatar of Kael'zar
```
