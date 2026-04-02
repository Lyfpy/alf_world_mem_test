---
node_id: cleaning
parent: README.md
children: []
depth: 1
created_at: 2026-04-02
---

## Children Overview
*No child nodes yet*

## When to Use
Use this node for tasks that involve cleaning objects and then placing them at specified locations, particularly kitchenware and utensils that require washing before placement.

## Knowledge
- Cleaning tasks require finding dirty objects, washing them at appropriate cleaning stations, then delivering to final destination
- Sinkbasins are the primary cleaning stations for washing objects
- Common objects that need cleaning: kitchen utensils (butcherknife), dishes, silverware
- Cleaning step is required before final placement - cannot just move dirty object directly
- Objects may be found on various surfaces (countertops, tables) that need to be cleaned
- After cleaning, objects must be moved to their final destination
- Countertops are common destinations for cleaned kitchen items

## SOP
1. Locate the dirty object that needs cleaning
2. Pick up the object using "take [object] from [location]"
3. Go to the cleaning station (usually sinkbasin)
4. Clean the object using "clean [object] with [cleaning station]"
5. Go to the final destination location
6. Place the cleaned object using "move [object] to [destination]"
7. Verify object is clean and properly placed

## Cases
- **Episode: clean some butterknife and put it in countertop** (Success, Score: 1.00, Steps: 7)
  - **Strategy**: Found butterknife 1 on countertop 2, took it to sinkbasin 1 for cleaning, then moved it to countertop 1.
  - **Key Insight**: Cleaning tasks require an intermediate washing step before final placement; sinkbasins are the standard cleaning stations.
  - **Efficiency Note**: Direct approach was efficient - located object, cleaned it, and delivered to destination without unnecessary detours.

## Stats
success_rate: 100
uses: 1
- Success Rate: 100% (1/1 episodes)
- Average Steps: 7.00
- Common Target Objects: Kitchen utensils, butcherknife
- Common Cleaning Stations: Sinkbasin
- Common Destinations: Countertop