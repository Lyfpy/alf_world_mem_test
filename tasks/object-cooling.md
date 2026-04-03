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

**Case 3: Bowl cooling and microwave placement**
- Task: Bowl cooling and microwave placement
- Result: Success
- Actions: go to countertop 1 → go to countertop 2 → go to diningtable 1 → go to cabinet 1 → open cabinet 1 → go to cabinet 2 → open cabinet 2 → go to cabinet 3 → open cabinet 3 → take bowl 1 from cabinet 3 → go to fridge 1 → cool bowl 1 with fridge 1 → go to microwave 1 → open microwave 1 → move bowl 1 to microwave 1
- Details: Found bowl 1 in cabinet 3 after checking multiple storage locations, cooled it in fridge 1, placed the cooled bowl in microwave 1

**Case 4: Bowl cooling to shelf**
- Task: "put a cool bowl in shelf"
- Result: Success (8 steps)
- Actions: go to countertop 1 → go to countertop 2 → go to countertop 3 → take bowl 1 from countertop 3 → go to fridge 1 → cool bowl 1 with fridge 1 → go to shelf 1 → move bowl 1 to shelf 1
- Details: Found bowl on countertop 3, cooled it in fridge 1, placed on shelf 1
- Trajectory:
Step 1: go to countertop 1
  -> You arrive at countertop 1. On the countertop 1, you see a butterknife 1, a mug 2, a pan 1, a spatula 2, and a vase 2.
Step 2: go to countertop 2
  -> You arrive at countertop 2. On the countertop 2, you see a apple 2, a dishsponge 2, a fork 3, a houseplant 1, a knife 2, a lettuce 1, a pan 2, a peppershaker 3, a plate 1, a potato 2, and a spoon 2.
Step 3: go to countertop 3
  -> You arrive at countertop 3. On the countertop 3, you see a book 1, a bowl 1, a bread 1, a glassbottle 3, a glassbottle 2, a kettle 1, a knife 1, a papertowelroll 1, a plate 2, a soapbottle 2, and a statue 1.
Step 4: take bowl 1 from countertop 3
  -> You pick up the bowl 1 from the countertop 3.
Step 5: go to fridge 1
  -> You arrive at fridge 1. The fridge 1 is closed.
Step 6: cool bowl 1 with fridge 1
  -> You cool the bowl 1 using the fridge 1.
Step 7: go to shelf 1
  -> You arrive at shelf 1. On the shelf 1, you see a peppershaker 1.
Step 8: move bowl 1 to shelf 1
  -> You move the bowl 1 to the shelf 1.

## Stats
success_rate: 1.0
uses: 5