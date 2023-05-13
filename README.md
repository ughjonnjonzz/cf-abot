# ABOT: An aBundance of Tables
_a simple D&D 5e character-building module for Foundry VTT, by CelestialFirestorm_

Need to build a character in a hurry? Need a kickstart to the creative process? Just want to throw everything at the wall and see what sticks?
Have I got the module for you!

Contained in this tidy little package are 30+ (yes, over _thirty_) functional rolling tables for choosing everything from mechanically-important options:
  - Race (1) + Subrace (9)
  - Class (1) + Subclass (13)
  - Background (1)
  - Feats (1)

to flavorful personality details a lively character simply can't do without!
  - assigned gender (1)
  - gender identity (1)
  - romantic (1) & sexual (1) orientation
  - alignment (1)

# Installation & Use
`https://raw.githubusercontent.com/ughjonnjonzz/cf-abot/main/module.json`

All of the tables included in ABOT can be rolled with directly from the Compendium folders, or imported to the RollTables tab for easier access.

There are three Compendiums in ABOT: Mechanical Choices, Sub Info, and Personality Choices. The Sub Info Compendium contains all the tables for Subraces and Subclasses that are called by the Race and Class tables, respectively. This is for ease of importing the main Mechanical tables, if you only want those. But the Subrace and Subclass tables are also totally functional tables, so if you need to roll for something specific (i.e. you know your class but can't decide on a subclass), you can dig out the Sub table you need and roll on it, too!

I do recommend making sure results are sent to the chat. If an entry on a list calls a child Sub list, you won't know what the actual result was without that chat output. With Races you have good odds of it not mattering, but with Classes it's pretty much required.

# Dependencies
None! There is absolutely no coding involved with the function of this module -- just plug it in, turn it on, and you're ready to roll!

Though I would be remiss to not mention Plutonium. You don't need it to run ABOT, but ABOT certainly wouldn't exist without its help in automating a lot of the table-making process. Highly recommended!

# Conflicts
I honestly can't forsee any conflicts with something as simple as ABOT. It doesn't alter or modify any part of Foundry's functionality, only makes use of the existing RollTable and Compendium features. So I guess if there are modules that tweak either of those, it _might_ cause some funky things in ABOT's tables?

I also can't speak to any previous or upcoming versions of Foundry itself. I've only used v10, so if prior or future versions handle RollTable or Compendium differently than v10, ABOT might not work for them.

Guess I should also mention that these tables are specifically for Dungeons and Dragons 5th Edition. Will the tables function and roll within worlds using other systems? Sure. But the information gathered from them would be entirely useless, so I don't see why you would bother.

# The Tables
Everything from this point will be talking about the actual content of the tables themselves. I won't list the entire selection of Races, Backgrounds, or Feats for both space-saving and sanity reasons -- you'll just have to install the module to read those yourself ;)

  - [Mechanical Choices](README.md#mechanical-choices)
    - [Race + Subrace](README.md#race--subrace)
    - [Class + Subclass](README.md#class--subclass)
    - [Background](README.md#background)
    - [Feats](README.md#feats)
  - [Personality Choices](README.md#personality-choices)
    - [assigned gender](README.md#assigned-gender)
    - [gender identity](README.md#gender-identity)
    - [orientations](README.md#orientations)
    - [alignment](README.md#alignment)

## Mechanical Choices
Despite being far more important to the actual _game_, I've personally found dealing with these choices to be much easier; both in picking them for my own characters, and in building these tables. They're very objective, while personality choices are fluid and changeable. But I'll get into that more in that section.

### Race + Subrace
Most Races are pretty straightforward, where the abilities you get are set. But some are more complicated, with subraces or racial traits you have to choose from the get-go. Here are the Races that call on child subrace tables before outputting a result.

| Core Race | Subrace(s) |
| --------- | ---------- |
| Dragonborn | Base; Chromatic; Draconblood; Gem; Metallic; Ravenite |
| Dwarf | Duergar; Hill; Mark of Warding; Mountain |
| Elf* | Drow; High; Mark of Shadow; Pallid; Wood |
| Genasi | Air; Earth; Fire; Water |
| Gnome* | Forest; Mark of Scribing; Rock |
| Half-Elf | Base; Aquatic Elf Descent; Drow Descent; Mark of Detection; Mark of Storm; Moon Elf or Sun Elf Descent; Wood Elf Descent |
| Half-Orc | Base; Mark of Finding |
| Halfling | Ghostwise; Lightfoot; Lotusden; Mark of Healing; Mark of Hospitality; Stout |
| Human | Base; Mark of Handling; Mark of Making; Mark of Passage; Mark of Sentinel; Variant; Variant, Mark of Finding |
| Tiefling | Base; Asmodeus; Baalzebul; Dispater; Fierna; Glasya; Levistus; Mammon; Mephistopheles; Variant, Devil's Tongue; Variant, Hellfire; Variant, Infernal Legacy; Variant, Winged; Zariel |

\*Certain subraces of Elves (Astral, Kalashtar, Sea, Shadar-Kai, Triton) and Gnomes (Autognome, Deep) are listed as separate entries on the Race table, hence not being included here.

And then there are Aasimar and Shifters. Depending on which source material you use, the different forms of those two Races might be listed as subraces instead of racial traits. For the record, any race that has been printed more than once, I ran with the latest printing, which in most cases means _Mordenkaiden Presents: Monsters of the Multiverse_. And MPMM does _not_ have the Aasimar and Shifter options listed as subraces, so I didn't include them in the subrace category.

### Class + Subclass
Naturally since every Class has a couple of subclass options, every entry on the Class table calls its own child subclass table.

| Class | Subclass |
| ----- | -------- |
| Artificer | Alchemist; Armorer; Artillerist; Battle Smith |
| Barbarian | Ancestral Guardian; Battlerager; Beast; Berserker; Storm Herald; Totem Warrior; Zealot; Wild Magic |
| Bard | Creation; Eloquence; Glamour; Lore; Spirits; Swords; Valor; Whispers |
| Cleric | Arcana; Death; Forge; Grave; Knowledge; Life; Light; Nature; Order; Peace; Tempest; Trickery; Twilight; War |
| Druid | Dreams; Spores; Stars; Land; Moon; Shepherd; Wildfire |
| Fighter | Gunslinger*; Arcane Archer; Battle Master; Cavalier; Champion; Echo Knight; Eldritch Knight; Psi Warrior; Purple Dragon Knight (Banneret); Rune Knight; Samurai |
| Monk | Mercy; Shadow; Ascendant Dragon; Astral Self; Drunken Master; Four Elements; Kensei; Long Death; Open Hand; Sun Soul |
| Paladin | Conquest; Devotion; Glory; Redemption; Ancients; Crown; Watchers; Vengeance; Oathbreaker |
| Ranger | Beast Master; Drakewarden; Fey Wanderer; Gloom Stalker; Horizon Walker; Hunter; Monster Slayer; Swarmkeeper |
| Rogue | Arcane Trickster; Assassin; Inquisitive; Mastermind; Phantom; Scout; Soulknife; Swashbuckler; Thief |
| Sorcerer | Aberrant Mind; Clockwork Soul; Divine Soul; Draconic Bloodline; Lunar Sorcery; Shadow Magic; Storm Sorcery; Wild Magic |
| Warlock | Archfey; Celestial; Fathomless; Fiend; Genie; Great Old One; Hexblade; Undead; Undying |
| Wizard | Bladesinging; Chronurgy; Graviturgy; Scribes; Abjuration; Conjuration; Divination; Enchantment; Evocation; Illusion; Necromancy; Transmutation; War |

\*I actually wasn't planning to include any Mercerbrew (mainly because I don't know a lot of it and because it's not on 5e.tools) but Plutonium imported it anyway somehow?? I debated about it and decided to keep it. Gunslingers are fun and I recommend playing one at some point -- as long as your DM allows it, of course.

### Background
There are some backgrounds that are very specific to certain campaigns that aren't generally applicable to homebrew games or even other official modules. Most of them are from _Dragonlance: Shadow of the Dragon Queen_ and they are _very_ specific to Krynn and/or that module, as well as some _Baldur's Gate_- and _Explorer's Guide to Wildmount_-flavored takes on existing Backgrounds. I chose not to include those in the Backgrounds table because they are applicable in so few circumstances. Some others (_Acquisitions Incorporated_ and _Sword Coast Adventurer's Guide_ come to mind) are fairly specific to setting as well, but are tweakable for general use, so those are included.

### Feats
Like the Backgrounds table, there are some Feats that only exist within the context of certain official modules -- again, mainly _DragonLance: Shadow of the Dragon Queen_. Those particular Feats even go so far as to have a prerequisite of "Dragonlance Campaign" to be able to take them. So for obvious reasons, I chose not to include those in the Feats table.

For both Background and Feats, if something isn't on the table and you feel it should be included, I'm more than willing to listen to your reasoning.

## Personality Choices
Okay, here's where things get tricky. Mechanical choices are objective; personality choices are very personal and highly mutable. _Hopefully_ the rest of the creation process will spark some ideas as to _who_ your new character is, but if you still need suggestions (or are building a completely randomized character for whatever reason), these tables are at your disposal as well.

They are **suggestions, not facts.** And they are the most bare-bones, basic, normie-accessable options I could think of, which is _on purpose_.

They are also more weighted toward certain options, in an effort to reflect some semblance of realism. The distributions will be detailed in each section.

If I missed anything obvious that should be on these lists, feel free to suggestion them.

### assigned gender
I don't know what the actual percentage of the population is intersex, so I kinda defaulted to a 10% chance, while male and female share the other 90% evenly.

**Die Roll:** 1d100
| Assigned Gender | Number Range |
| --------------- | ------------ |
| Male | 01 - 45 |
| Female | 46 - 90 |
| Intersex | 91 - 100 |

### gender identity
This one is by far the most weighted in one direction.

**Die Roll:** 1d100
| Gender Identity | Number Range |
| --------------- | ------------ |
| Cis | 01 - 90 |
| Nonbinary | 91 - 95 |
| Binary Trans | 96 - 100 |

### orientations
These are probably the least weighted lists, leaning more toward hetero, but it's much more evenly distributed between all options. Because that's more fun to me. If you want to change the ranges when you use these tables, feel free.

**Die Roll:** 1d6
| Orientation | Number Range |
| ----------- | ------------ |
| hetero | 1 - 2 |
| bi | 3 |
| homo | 4 |
| pan | 5 |
| a (non) | 6 |

### alignment
There's no weighting in this list, because this is arguably the least important personality choice. Remember: alignment is _descriptive_, not _prescriptive_. It means different things to different people, and it can change over time. Like everything else in this section, this is just to give you an idea of who your character is, not to force you into one direction or another.

**Die Roll:** 1d9
| Alignment | Number Range |
| --------- | ------------ |
| Lawful Good | 1 |
| Lawful Neutral | 2 |
| Lawful Evil | 3 |
| Neutral Good | 4 |
| True Neutral | 5 |
| Neutral Evil | 6 |
| Chaotic Good | 7 |
| Chaotic Neutral | 8 |
| Chaotic Evil | 9 |
