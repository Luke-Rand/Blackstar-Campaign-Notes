---
world: Blackstar
system: Pathfinder 2e
---

# Blackstar Campaign Notes
Notes from the Blackstar Pathfinder2e Campaign. These notes are an Obsidian notebook that is hosted in Github. If you would like to have your own copy of the notes, follow the below instructions:

1. Clone the Github repository [here](https://github.com/Luke-Rand/Blackstar-Campaign-Notes)
2. Download Obsidian [here](https://obsidian.md)
3. Unzip the downloaded repository and open it as a "Vault" using [these](https://help.obsidian.md/Getting+started/Create+a+vault#Open+existing+folder) instructions

I plan to eventually host these notes as a wiki but this is the best way for me to take campaign notes for now. Please feel free to fork my repo and create a pull request to contribute!

## Sessions
```dataview
TABLE date AS "Date", summary AS "Summary" 
WHERE type = "session" AND file.name != "Session Summary"
SORT date ASCENDING
```

## Player Characters
```dataview
TABLE played_by AS "Played By", ancestry AS "Ancestry", class AS "Class"
WHERE type= "pc"
```
## Factions
```dataview
TABLE summary AS "Summary"
WHERE type = "faction"
```


## Prominent NPCs
```dataview
TABLE summary AS "Summary", faction AS "Faction"
WHERE type = "npc"
```

## Locations
```dataview
TABLE summary AS "Summary"
WHERE type = "location" AND file.name != "Location"
```

## Important Items
```dataview
TABLE summary AS "Summary"
WHERE type = "item" AND important = true
```
