---
node_id: put_two_creditcards_in_diningtable_failure
parent: failure_modes/put_object_failure.md
children: []
depth: 4
created_at: 2025-06-17
---
# Failure Case: Repetitive Item Handling in Put Task

## When to Use
Reference this case when:
- Putting multiple items in same location
- Task requires sequential item management
- Risk of getting stuck in item handling loops

## Knowledge
- Taking and immediately putting back same item leads to infinite loops
- Must track task completion state explicitly
- Once at target location, must complete action before leaving

## SOP
1. When handling multiple items:
   - Take all required items before moving to target
   - Go to target location ONCE
   - Put/drop items sequentially
   - Verify task completion
2. Avoid take/put cycles:
   - Only take item if you're going to use it elsewhere
   - Don't put item back where you took it from
3. State tracking:
   - Keep mental count of items placed
   - Don't leave target until all items placed

## Cases
###Episodic Evidence:
- Took creditcard1, immediately put it back on armchair (Step 15,19,23,27,31,35,39,43,47)
- Repeated this cycle 9 times without progress
- Finally went to diningtable with creditcard2 but didn't put it (Step 51)
- Wasted 73 total steps due to repetitive actions

## Stats
- Episodes with similar loops: 1/1 (100%)
- Average steps wasted: 50+
- Success rate: 0% when loops occur
- Root cause: Poor state management, target confusion