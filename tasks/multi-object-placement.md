---
node_id: multi-object-placement
parent: README.md
children: []
depth: 1
created_at: 2025-06-17
---

## When to Use
Use this strategy when you need to place multiple objects on a target location and the objects are located in different areas. This is particularly useful for tasks involving collecting and moving multiple items to a single destination.

## Knowledge
Multi-object tasks benefit from staging areas when objects are in different locations. Staging reduces back-and-forth travel between multiple source locations and target. Choose staging location that's either centrally located or already contains some target objects. The core strategy is to collect all objects at a staging point, then systematically place them at the target.

## SOP
1. Inventory and locate all required objects
2. Identify optimal staging location (central or pre-populated with some objects)
3. Move all objects to staging area
4. Systematically transfer objects from staging to target location
5. Verify all objects placed correctly

## Cases
**Task**: Put two creditcard in diningtable  
**Objects**: creditcard1 on dresser1, creditcard2 on armchair1  
**Target**: diningtable1  
**Strategy used**: armchair1 as staging area (already contained creditcard2)  
**Navigation pattern**: Initial inefficient exploration (countertop1, sidetable1, bed1) followed by staging discovery  
**Total steps**: 27  
**Key insight**: Trial-and-error discovery led to optimal staging approach  
**Outcome**: Success achieved through persisted staging strategy  

**Task**: find two creditcard and put them in shelf  
**Objects**: creditcard 3 on desk 1, creditcard 4 on desk 1  
**Target**: shelf 1  
**Strategy used**: Direct sequential collection from single source location (desk1)  
**Navigation pattern**: Initial detour to bed1, then optimized direct desk1 → shelf1 route  
**Total steps**: 16  
**Key insight**: When all objects are at same location, staging is unnecessary - direct sequential placement is optimal  
**Outcome**: Success with efficient back-and-forth between desk and shelf  

## Stats
success_rate: 1.00
uses: 2
avg_steps: 21.5