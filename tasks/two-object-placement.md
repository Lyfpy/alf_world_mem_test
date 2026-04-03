---
node_id: two-object-placement
parent: README.md
children: []
depth: 1
created_at: 2026-04-03
---

## When to Use
This memory should be retrieved for tasks that involve picking up two identical objects and placing them in the same destination location. The pattern applies when the task explicitly mentions "put two [object] in [location]" or similar phrasing requiring moving two identical items to one place.

## Knowledge
- Two-object placement tasks require finding both instances of the target object before completion
- Objects may be located in different areas and require systematic searching
- The destination location may need to be opened/unlocked before placing objects
- Search patterns should be systematic: check obvious locations first, then expand to less obvious areas
- Objects can be found in containers, on surfaces, or in disposal areas like garbage cans
- Once the first object is placed, the second object often requires additional searching

## SOP
1. Go to the likely location of the first target object
2. Pick up the first instance of the target object
3. Go to the destination location
4. Open/unlock the destination if necessary
5. Place the first object in the destination
6. Begin systematic search for the second instance of the target object
   - Check nearby surfaces and containers
   - Explore different rooms/areas
   - Check disposal areas like garbage cans
7. Pick up the second instance of the target object
8. Return to the destination location
9. Place the second object in the destination

## Cases
**Case: Two lettuce to fridge**
- Task: "put two lettuce in fridge"
- Result: Success
- Trajectory:
  - Step 1: go to countertop 1 → You arrive at countertop 1. On the countertop 1, you see a apple 1, a papertowelroll 1, a tomato 2, and a tomato 1.
  - Step 2: go to countertop 2 → You arrive at countertop 2. On the countertop 2, you see a dishsponge 2, a houseplant 1, a lettuce 1, a mug 1, a plate 1, and a winebottle 3.
  - Step 3: take lettuce 1 from countertop 2 → You pick up the lettuce 1 from the countertop 2.
  - Step 4: go to fridge 1 → You arrive at fridge 1. The fridge 1 is closed.
  - Step 5: open fridge 1 → You open the fridge 1. The fridge 1 is open. In it, you see a bowl 1, a egg 1, a pot 1, a potato 2, and a potato 1.
  - Step 6: move lettuce 1 to fridge 1 → You move the lettuce 1 to the fridge 1.
  - Step 7: go to countertop 3 → You arrive at countertop 3. On the countertop 3, you see a apple 2, a book 1, a bread 1, a butterknife 3, a butterknife 2, a fork 1, a knife 1, a lettuce 2, a pan 1, a peppershaker 3, a plate 2, a statue 1, and a tomato 3.
  - Step 8: take lettuce 2 from countertop 3 → You pick up the lettuce 2 from the countertop 3.
  - Step 9: go to fridge 1 → You arrive at fridge 1. The fridge 1 is open. In it, you see a bowl 1, a egg 1, a lettuce 1, a pot 1, a potato 2, and a potato 1.
  - Step 10: move lettuce 2 to fridge 1 → You move the lettuce 2 to the fridge 1.

**Case: Two toiletpaper to toilet**
- Task: "find two toiletpaper and put them in toilet"
- Result: Success
- Trajectory:
  - Step 1: go to toiletpaperhanger 1 → You arrive at toiletpaperhanger 1. On the toiletpaperhanger 1, you see nothing.
  - Step 2: go to countertop 1 → You arrive at countertop 1. On the countertop 1, you see a candle 1, and a spraybottle 1.
  - Step 3: go to cabinet 1 → You arrive at cabinet 1. The cabinet 1 is closed.
  - Step 4: open cabinet 1 → You open the cabinet 1. The cabinet 1 is open. In it, you see nothing.
  - Step 5: go to cabinet 2 → You arrive at cabinet 2. The cabinet 2 is closed.
  - Step 6: take toiletpaper 2 from garbagecan 1 → You pick up the toiletpaper 2 from the garbagecan 1.
  - Step 7: go to toilet 1 → You arrive at toilet 1. On the toilet 1, you see a soapbar 1, and a soapbottle 1.
  - Step 8: move toiletpaper 2 to toilet 1 → You move the toiletpaper 2 to the toilet 1.
  - Step 9: go to garbagecan 1 → You arrive at garbagecan 1. On the garbagecan 1, you see a toiletpaper 3.
  - Step 10: take toiletpaper 3 from garbagecan 1 → You pick up the toiletpaper 3 from the garbagecan 1.
  - Step 11: go to toilet 1 → You arrive at toilet 1. On the toilet 1, you see a soapbar 1, a soapbottle 1, and a toiletpaper 2.
  - Step 12: move toiletpaper 3 to toilet 1 → You move the toiletpaper 3 to the toilet 1.

**Case: Two spraybottles to cabinet**
- Task: "put two spraybottle in cabinet"
- Result: Success
- Trajectory:
  - Step 1: go to countertop 1 → Found spraybottle 1 on countertop 1
  - Step 2: take spraybottle 1 from countertop 1 → Picked up first spraybottle
  - Step 3: go to cabinet 1 → Arrived at destination
  - Step 4: open cabinet 1 → Opened destination cabinet
  - Step 5: move spraybottle 1 to cabinet 1 → Placed first object
  - Step 6-16: Systematic search across shelf 1, sinkbasin 1, sinkbasin 2, bathtubbasin 1, cabinet 2, cabinet 3, cabinet 4, toilet 1 → Explored multiple locations
  - Step 17: go to garbagecan 1 → Found spraybottle 2 in garbagecan 1
  - Step 18: take spraybottle 2 from garbagecan 1 → Picked up second object
  - Step 19: go to cabinet 1 → Returned to destination
  - Step 20: move spraybottle 2 to cabinet 1 → Placed second object, task completed

**Case: Two cellphones to sidetable**
- Task: "put two cellphone in sidetable"
- Result: Success
- Trajectory:
  - Step 1: go to desk 1 → You arrive at desk 1. On the desk 1, you see a alarmclock 1, a book 3, a box 1, a keychain 1, a laptop 1, a pen 3, and a pen 1.
  - Step 2: go to shelf 1 → You arrive at shelf 1. On the shelf 1, you see a pen 2.
  - Step 3: go to cabinet 1 → You arrive at cabinet 1. The cabinet 1 is closed.
  - Step 4: open cabinet 1 → You open the cabinet 1. The cabinet 1 is open. In it, you see nothing.
  - Step 5: close cabinet 1 → You close the cabinet 1.
  - Step 6: open cabinet 2 → You open the cabinet 2. The cabinet 2 is open. In it, you see nothing.
  - Step 7: go to cabinet 3 → You arrive at cabinet 3. The cabinet 3 is closed.
  - Step 8: open cabinet 3 → You open the cabinet 3. The cabinet 3 is open. In it, you see nothing.
  - Step 9: go to cabinet 4 → You arrive at cabinet 4. The cabinet 4 is closed.
  - Step 10: open cabinet 4 → You open the cabinet 4. The cabinet 4 is open. In it, you see nothing.
  - Step 11: go to drawer 1 → You arrive at drawer 1. The drawer 1 is closed.
  - Step 12: open drawer 1 → You open the drawer 1. The drawer 1 is open. In it, you see nothing.
  - Step 13: go to drawer 2 → You arrive at drawer 2. The drawer 2 is closed.
  - Step 14: open drawer 2 → You open the drawer 2. The drawer 2 is open. In it, you see a creditcard 1.
  - Step 15: go to garbagecan 1 → You arrive at garbagecan 1. On the garbagecan 1, you see a pencil 2.
  - Step 16: examine garbagecan 1 → On the garbagecan 1, you see a pencil 2.
  - Step 17: go to bed 1 → You arrive at bed 1. On the bed 1, you see a book 2, a book 1, a cellphone 2, a cellphone 1, a pillow 3, a pillow 2, and a pillow 1.
  - Step 18: take cellphone 1 from bed 1 → You pick up the cellphone 1 from the bed 1.
  - Step 19: go to sidetable 1 → You arrive at sidetable 1. On the sidetable 1, you see a cd 1, and a pencil 1.
  - Step 20: move cellphone 1 to sidetable 1 → You move the cellphone 1 to the sidetable 1.
  - Step 21: go to bed 1 → You arrive at bed 1. On the bed 1, you see a book 2, a book 1, a cellphone 2, a pillow 3, a pillow 2, and a pillow 1.
  - Step 22: take cellphone 2 from bed 1 → You pick up the cellphone 2 from the bed 1.
  - Step 23: go to sidetable 1 → You arrive at sidetable 1. On the sidetable 1, you see a cd 1, a cellphone 1, and a pencil 1.
  - Step 24: move cellphone 2 to sidetable 1 → You move the cellphone 2 to the sidetable 1.

## Stats
success_rate: 1.0
uses: 3