---
node_id: object-cooling
parent: README.md
children: []
depth: 1
created_at: 2026-04-03
---

## When to Use
Use this memory when tasked with cooling objects (food items or containers) using the fridge and then placing them at a specified destination location.

## Knowledge
- Fridge must be accessed to cool objects - may need to open it first if closed
- Objects can be cooled regardless of their current location (countertop, other surfaces)
- After cooling, objects can be placed at any target destination (countertop, table, etc.)
- The sequence follows: find object → go to fridge → cool object → place at destination
- Both food items and containers can be cooled using the same fridge interaction pattern

## SOP
1. Locate the target object to be cooled
2. Go to the refrigerator
3. Open the refrigerator if it's closed
4. Take/pick up the object from its current location
5. Go back to the refrigerator 
6. Cool the object using the refrigerator
7. Go to the specified destination location
8. Place/move the cooled object at the destination

## Cases
**Case 1: Lettuce cooling**
- Task: "cool some lettuce and put it in countertop"
- Result: Success
- Actions: go to fridge 1 → open fridge 1 → go to countertop 1 → take lettuce 1 from countertop 1 → go to fridge 1 → cool lettuce 1 with fridge 1 → go to countertop 1 → move lettuce 1 to countertop 1
- Details: Found lettuce on countertop 1, cooled it in fridge 1, returned to place on countertop 1

**Case 2: Bowl cooling**
- Task: "put a cool bowl in countertop"
- Result: Success
- Actions: go to countertop 1 → go to countertop 2 → take bowl 1 from countertop 2 → go to fridge 1 → cool bowl 1 with fridge 1 → go to countertop 1 → move bowl 1 to countertop 1
- Details: Found bowl on countertop 2, cooled it in fridge 1, placed on countertop 1

## Stats
success_rate: 0
uses: 0