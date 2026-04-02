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
- Common target locations include diningtable, countertop, sidetable, toilet
- Creditcards are small objects that can be easily moved between surfaces
- CDs are commonly found on dining tables
- Side tables are valid destinations for CD placement
- Spraybottles are bathroom items commonly found on countertops
- Toilets are valid destinations for object placement tasks

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
- **Episode: Put some cd on sidetable** (Success, Score: 1.00, Steps: 5)
  - **Strategy**: Found cd 1 on diningtable 1, picked it up and moved it to sidetable 1.
  - **Key Insight**: CD objects are commonly found on dining tables and can be directly moved to side tables.
  - **Efficiency Note**: Direct approach was efficient with no unnecessary detours - went straight to object location, picked it up, and delivered to destination.
- **Episode: Put two creditcard in diningtable (Efficient)** (Success, Score: 1.00, Steps: 14)
  - **Strategy**: Found creditcard 1 on dresser 1 and creditcard 2 on armchair 1, then moved both to diningtable 1.
  - **Key Insight**: Direct approach works well when object locations are known.
  - **Efficiency Note**: No unnecessary detours - systematic but focused movement between object locations and destination.
- **Episode: Put some cd on sidetable** (Success, Score: 1.00, Steps: 4)
  - **Strategy**: Found cd 1 on diningtable 1, went to sidetable 1 and placed it.
  - **Key Insight**: Consistent pattern - CDs are commonly found on dining tables and easily moved to side tables.
  - **Efficiency Note**: Very efficient execution - minimal steps wasted, direct path from object to destination.
- **Episode: Put two creditcard in diningtable** (Success, Score: 1.00, Steps: 12)
  - **Strategy**: Found creditcard 1 on dresser 1 and creditcard 2 on armchair 1, then moved both to diningtable 1.
  - **Key Insight**: Objects can be distributed across different furniture pieces - systematic search of dressers and armchairs is effective.
  - **Efficiency Note**: Most efficient execution yet - direct focused movements between object locations and destination with minimal detours.
- **Episode: Put some cd on sidetable** (Success, Score: 1.00, Steps: 4)
  - **Strategy**: Went to diningtable 1, found cd 1 among other items (alarmclock 2, cellphone 2, creditcard 2, keychain 3, keychain 2, pencil 3), picked it up, went to sidetable 1, and moved it there.
  - **Key Insight**: Dining tables often contain multiple objects requiring identification; CDs are consistently found on dining tables and can be efficiently moved to side tables.
  - **Efficiency Note**: Optimal execution with exactly 4 steps - the standard efficient pattern for this task type.
- **Episode: Put some spraybottle on toilet** (Success, Score: 1.00, Steps: 4)
  - **Strategy**: Found spraybottle 1 on countertop 1 (along with candle 2), picked it up, went to toilet 1, and moved it there.
  - **Key Insight**: Spraybottles are bathroom items commonly found on countertops; toilets are valid destinations for object placement.
  - **Efficiency Note**: Very efficient 4-step execution - direct approach from countertop to toilet.

## Stats
success_rate: 100
uses: 7
- Success Rate: 100% (7/7 episodes)
- Average Steps: 9.71
- Common Target Objects: Creditcards, books, CDs, spraybottles
- Common Destinations: Diningtable, countertop, sidetable, toilet