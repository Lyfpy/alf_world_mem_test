---
node_id: object-cleaning-and-placement
parent: README.md
children: []
depth: 1
created_at: 2024-12-19
---

## When to Use
Use this memory when you need to clean an object (typically using sinkbasin) before placing it at a target location. This pattern applies when the task explicitly mentions cleaning requirements or when the object needs to be washed before being placed on a clean surface.

## Knowledge
- Objects must be cleaned using sinkbasin before placement on clean surfaces
- Cleaning is an essential step that must happen before the placement step
- The typical sequence is: locate object → pick up object → clean object at sinkbasin → transport to target → place object
- Sinkbasin is the standard cleaning station in AlfWorld environments
- Some objects (like utensils) often require cleaning before being placed on countertops or other food preparation surfaces

## SOP
1. Locate the target object in its current position
2. Navigate to and pick up the object
3. Navigate to the sinkbasin (cleaning station)
4. Clean the object using the sinkbasin 
5. Navigate to the target placement location
6. Place the cleaning object at the target location
7. Confirm the object is both clean and properly placed

## Cases
Task was "clean some butterknife and put it in countertop", the agent took butterknife 1 from countertop 2, cleaned it with sinkbasin 1, and placed it on countertop 1. The trajectory shows the cleaning step is essential and must happen before placement.

## Stats
success_rate: 0
uses: 0