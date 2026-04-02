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
- Common objects that need cleaning: kitchen utensils (butcherknife), dishes, silverware, food items (lettuce)
- Cleaning step is required before final placement - cannot just move dirty object directly
- Objects may be found on various surfaces (countertops, tables, dining tables) that need to be cleaned
- After cleaning, objects must be moved to their final destination
- Countertops are common destinations for cleaned kitchen items
- Cleaning SOP applies to both kitchenware and food items - anything that can be washed at a sinkbasin

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
- **Episode: clean some lettuce and put it in countertop** (Success, Score: 1.00, Steps: 47)
  - **Strategy**: Found lettuce 1 on diningtable 1 after extensive search of 16 cabinets and 5 drawers, took it to sinkbasin 1 for cleaning, then moved it to countertop 1.
  - **Key Insight**: Cleaning tasks work for food items too - lettuce can be cleaned at sinkbasin just like kitchen utensils. Demonstrates the cleaning SOP applies beyond just kitchenware.
  - **Efficiency Note**: Excessive searching (31 steps exploring cabinets/drawers) before finding lettuce. Only 6 steps were needed for actual task execution once lettuce was found: take → go to sinkbasin → clean → go to countertop → place.
  - **Learning**: Verify object locations systematically; consider checking primary surfaces (dining tables, countertops) before extensive cabinet/drawer searches.

## Stats
success_rate: 100
uses: 2
- Success Rate: 100% (2/2 episodes)
- Average Steps: 27.00
- Common Target Objects: Kitchen utensils, butcherknife, lettuce
- Common Cleaning Stations: Sinkbasin
- Common Destinations: Countertop