---
node_id: object-placement
parent: README.md
children: []
depth: 1
created_at: 2026-04-02
---

## Children Overview
*No child nodes yet*

## When to Use
Use this node for tasks that involve moving objects from one location to another, particularly household items like creditcards, books, CDs, etc.

## Knowledge
- Object placement tasks require finding target objects and moving them to specified locations
- Objects are often found on furniture surfaces (dresser, armchair, countertop)
- Common target locations include diningtable, countertop, sidetable
- Creditcards are small objects that can be easily moved between surfaces

## SOP
1. Go to the target object's location
2. Pick up the object using "take [object] from [location]" 
3. Go to the destination location
4. Place object using "move [object] to [destination]"
5. Repeat for additional objects if needed
6. Use inventory command to track carried items
7. Use examine command to verify object collections at locations

## Cases
- **Episode: Put two creditcard in diningtable** (Success, Score: 1.00, Steps: 25)
  - **Strategy**: Found creditcard 1 on dresser 1, creditcard 2 already on armchair 1. Moved both to diningtable 1.
  - **Key Insight**: Objects may be distributed across multiple furniture pieces. Systematic search of all surfaces is required.
  - **Efficiency Note**: Initial detours to empty drawers/countertop were unnecessary but harmless.

## Stats
success_rate: 100
uses: 1
- Success Rate: 100% (1/1 episodes)
- Average Steps: 25
- Common Target Objects: Creditcards, books, CDs
- Common Destinations: Diningtable, countertop, sidetable