---
node_id: object-examination
parent: README.md
children: []
depth: 1
created_at: 2026-04-03
---

## When to Use
This memory should be retrieved for tasks involving examining or looking at objects, especially when there are challenges or specific spatial relationships mentioned (like "under", "behind", "inside"). Use it when initial examination doesn't reveal the target and systematic exploration is needed.

## Knowledge
- Examining objects requires understanding spatial relationships and positioning
- Going to a location and examining it may not reveal all objects or their relationships
- Spatial qualifiers like "under" require finding the reference object (e.g., desklamp) first
- Systematic exploration can become repetitive loops if the target location/object is not found
- Taking and putting objects doesn't necessarily help with examination tasks focused on spatial relationships
- Multiple locations may need to be explored when specific objects or locations are not immediately visible

## SOP
1. Identify the target object and any spatial modifiers (e.g., "under", "behind")
2. If spatial modifier present, first locate the reference object (e.g., desklamp)
3. Go to relevant locations containing the target object
4. Examine the location and objects thoroughly
5. If examination doesn't reveal the spatial relationship, explore other locations
6. Avoid repetitive loops between the same few locations
7. Consider that some objects may not be immediately visible or may not exist in the current environment
8. Use systematic exploration of all available locations rather than fixating on one area

## Cases
Case 1: "look at bowl under the desklamp" - Failed
- Step 1: go to desk 1 -> You arrive at desk 1. On the desk 1, you see a alarmclock 1, a book 1, a bowl 1, a pen 2, and a pencil 1.
- Step 2: examine desk 1 -> On the desk 1, you see a alarmclock 1, a book 1, a bowl 1, a pen 2, and a pencil 1.
- Step 3: take bowl 1 from desk 1 -> You pick up the bowl 1 from the desk 1.
- Step 4: examine desk 1 -> On the desk 1, you see a alarmclock 1, a book 1, a pen 2, and a pencil 1.
- Step 5: look -> You are facing the desk 1. Next to it, you see nothing.
- Step 6: examine bowl 1 -> This is a normal bowl 1. In it, you see nothing.
- Steps 7-50: Repetitive loop between desk 1 and bed 1, multiple attempts to examine bowl 1 and desk 1, trying drawer 1, taking/putting bowl 1, never finding desklamp or successfully examining bowl "under" it

## Stats
success_rate: 0
uses: 0