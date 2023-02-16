---
world: Blackstar
system: Pathfinder 2e
---

# Blackstar Campaign Notes
Notes from the Blackstar Pathfinder2e Campaign

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

## Sessions
```dataview
TABLE date AS "Date", summary AS "Summary" 
WHERE type = "session" AND file.name != "Session Summary"
SORT date ASCENDING
```
