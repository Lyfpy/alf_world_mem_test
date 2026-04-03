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

## Stats
success_rate: 0
uses: 0