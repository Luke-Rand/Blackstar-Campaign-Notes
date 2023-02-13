---
world: Blackstar
system: Pathfinder 2e
---

# Blackstar-Campaign-Notes
 Notes from the Blackstar Pathfinder Campaign

## Player Characters
```dataview
TABLE played_by AS "Played By", ancestry AS "Ancestry", class AS "Class"
WHERE type= "pc"
```
## Factions
```dataview
TABLE
FROM "👪 Factions"
```


## Prominent NPCs
```dataview
TABLE description AS "Description", faction AS "Faction"
WHERE type= "npc"
```


## Sessions
```dataview
TABLE date AS "Date", summary AS "Summary" 
FROM "🎲 Sessions"
SORT date ASCENDING
```
