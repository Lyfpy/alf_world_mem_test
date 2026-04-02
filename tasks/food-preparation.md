---
node_id: food-preparation
parent: README.md
children: []
depth: 1
created_at: 2026-04-02
---

## Children Overview
*No child nodes yet*

## When to Use
Use this node for tasks that involve food preparation activities, particularly cooling/warming food items and then placing them at specified locations.

## Knowledge
- Food preparation tasks involve processing food items (cooling, warming) before final placement
- Fridge is used for cooling food items
- Microwave is used for warming food items
- Food items include: lettuce, apple, tomato, potato, egg, bread
- Processing step is required before final placement - cannot just move food directly
- After processing, food must be moved to their final destination
- Countertops are common destinations for prepared food items
- Common food locations: countertop, fridge, microwave

## SOP
1. Locate the food item that needs preparation
2. Pick up the food item using "take [object] from [location]"
3. Go to the preparation station (fridge for cooling, microwave for warming)
4. Process the food item using "cool [object] with [fridge]" or "warm [object] with [microwave]"
5. Go to the final destination location
6. Place the processed food using "put [object] on [destination]"
7. Verify food is properly placed

## Cases
- **Episode: cool some lettuce and put it in countertop** (Failure, Score: 0.00, Steps: 54)
  - **Strategy**: Found lettuce 1 on countertop 1, took it to fridge 1 for cooling, but failed to complete final placement step.
  - **Key Insight**: Food preparation requires two-phase approach - process (cool/warm) then place. Agent completed cooling but missed the final placement action.
  - **Efficiency Note**: Excessive searching of unnecessary locations (20+ cabinets/drawers) before finding lettuce. After cooling, agent failed to use "put" command for final placement.
  - **Critical Error**: After cooling, must explicitly place food item using "put [object] on [destination]" command.

## Stats
success_rate: 0
uses: 1
- Success Rate: 0% (0/1 episodes)
- Average Steps: 54.00
- Common Target Objects: Lettuce
- Common Processing Stations: Fridge
- Common Destinations: Countertop