---
node_id: simple-placement
parent: README.md
children: []
depth: 1
created_at: 2026-04-03
---

## When to Use
For tasks that involve moving a single object from its current location to a destination without any intermediate processing steps

## Knowledge
Objects are commonly found on furniture surfaces like coffeetables, tvstands, countertops; single object movement is straightforward; no special tools or processing required

## SOP
1) Search for target object at likely locations, 2) Take the object, 3) Go to destination, 4) Place the object

## Cases
**Case 1:** "put some remotecontrol on armchair" - Success, 5 steps
- Trajectory: 
Step 1: go to coffeetable 1
  -> You arrive at coffeetable 1. On the coffeetable 1, you see a creditcard 3, a creditcard 2, and a laptop 1.
Step 2: go to tvstand 1
  -> You arrive at tvstand 1. On the tvstand 1, you see a creditcard 1, a remotecontrol 3, a remotecontrol 2, a statue 1, and a television 1.
Step 3: take remotecontrol 2 from tvstand 1
  -> You pick up the remotecontrol 2 from the tvstand 1.
Step 4: go to armchair 1
  -> You arrive at armchair 1. On the armchair 1, you see a newspaper 1.
Step 5: move remotecontrol 2 to armchair 1
  -> You move the remotecontrol 2 to the armchair 1.

**Case 2:** "put some book on armchair" - Success, 4 steps
- Trajectory:
Step 1: go to coffeetable 1
  -> You arrive at coffeetable 1. On the coffeetable 1, you see a book 1, a laptop 1, a remotecontrol 2, a statue 2, a vase 4, and a vase 3.
Step 2: take book 1 from coffeetable 1
  -> You pick up the book 1 from the coffeetable 1.
Step 3: go to armchair 1
  -> You arrive at armchair 1. On the armchair 1, you see a creditcard 1, a pillow 2, and a remotecontrol 1.
Step 4: move book 1 to armchair 1
  -> You move the book 1 to the armchair 1.

## Stats
success_rate: 100
uses: 2