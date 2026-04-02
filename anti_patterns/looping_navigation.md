---
node_id: looping_navigation
parent: anti_patterns
children: []
depth: 2
created_at: 2024-11-28
---
# Looping Navigation Pattern

## When to Use
This anti-pattern describes a behavior to avoid. It occurs when the agent repeatedly moves between the same locations without taking meaningful action.

## Knowledge
- The agent can get stuck in navigation loops between two or more locations
- This usually happens when the agent is uncertain about the next step
- The agent continues to issue 'go to' commands even when already at the target location
- Navigation loops waste steps and time, leading to task failure

## SOP
To avoid this pattern:
1. Track current location before issuing movement commands
2. If at the target location, take a different action (e.g., examine, take, put)
3. If stuck between two locations, try a new action or explore a third location
4. Use 'inventory' and 'look' commands to reassess the situation

## Cases
**Case 1**: Repeated armchair navigation (2024-11-28)
- Task: Put two credit cards in dining table
- Problem: Agent repeatedly moved between armchair 1 and armchair 2
- Loop pattern: go to armchair 2 → go to armchair 1 → repeat
- Steps wasted: 40+ repetitive navigation steps
- Outcome: Task failed due to inefficient navigation

**Case 2**: Failed dining table navigation
- Commander 'go to diningtable' was issued but agent remained at armchair 2
- Multiple attempts to reach dining table all failed
- Agent became stuck at armchair 2 location

## Stats
- Total steps in failed attempt: 73
- Navigation loop steps: ~40 (54.8% of total)
- Unique locations visited: 6
- Task completion: 0%
