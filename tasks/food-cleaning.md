---
node_id: food-cleaning
parent: README.md
children: []
depth: 1
created_at: 2026-04-03
---

## When to Use
Use this memory when the task involves cleaning food items (typically vegetables) using a sinkbasin. This pattern applies when you need to locate a food item, clean it at the sinkbasin, and then place it at a specified destination.

## Knowledge
- Food items requiring cleaning are typically found on dining tables, countertops, or inside fridges
- The sinkbasin is the primary appliance for cleaning food items in the environment
- Food items may need to be searched across multiple locations as they are not always where expected
- vegetables like lettuce are common items that require cleaning before use
- The cleaning action requires the food item to be taken to the sinkbasin location first
- After cleaning, the item should be transported to the final destination location

## SOP
1. Search for the target food item across likely locations (dining tables, countertops, fridges)
2. Take the food item from its current location
3. Go to the sinkbasin
4. Clean the food item using the sinkbasin
5. Go to the specified destination location
6. Place/move the cleaned food item at the destination

## Cases
Task: "Your task is to: clean some lettuce and put it in countertop."
Result: Success
Steps: go to fridge 1, open fridge 1, go to countertop 1, go to countertop 2, go to diningtable 1, take lettuce 1 from diningtable 1, go to sinkbasin 1, clean lettuce 1 with sinkbasin 1, go to countertop 1, move lettuce 1 to countertop 1

trajectory:
Step 1: go to fridge 1
  -> You arrive at fridge 1. The fridge 1 is closed.
Step 2: open fridge 1
  -> You open the fridge 1. The fridge 1 is open. In it, you see a egg 1, and a tomato 1.
Step 3: go to countertop 1
  -> You arrive at countertop 1. On the countertop 1, you see nothing.
Step 4: go to countertop 2
  -> You arrive at countertop 2. On the countertop 2, you see a apple 1, a bowl 1, a bread 1, a butterknife 1, a plate 1, and a spatula 1.
Step 5: go to diningtable 1
  -> You arrive at diningtable 1. On the diningtable 1, you see a cup 1, a dishsponge 3, a fork 1, a houseplant 1, a knife 2, a lettuce 2, a lettuce 1, a mug 1, a papertowelroll 1, a peppershaker 2, a potato 2, a potato 1, a saltshaker 2, a soapbottle 1, a spoon 3, and a spoon 2.
Step 6: take lettuce 1 from diningtable 1
  -> You pick up the lettuce 1 from the diningtable 1.
Step 7: go to sinkbasin 1
  -> You arrive at sinkbasin 1. On the sinkbasin 1, you see a knife 1.
Step 8: clean lettuce 1 with sinkbasin 1
  -> You clean the lettuce 1 using the sinkbasin 1.
Step 9: go to countertop 1
  -> You arrive at countertop 1. On the countertop 1, you see nothing.
Step 10: move lettuce 1 to countertop 1
  -> You move the lettuce 1 to the countertop 1.

## Stats
success_rate: 0
uses: 0