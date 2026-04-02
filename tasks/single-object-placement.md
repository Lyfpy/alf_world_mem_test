---
node_id: single-object-placement
parent: README.md
children: []
depth: 1
created_at: 2025-06-17
---

## When to Use
Use this strategy when you need to move a single object from its current location to a specified target location. This is the most basic placement task pattern requiring minimal navigation and object handling.

## Knowledge
Single-object placement follows a straightforward fetch-and-place pattern: inventory check, locate source, retrieve object, navigate to target, place object. No staging or complex routing is needed. Key efficiency comes from direct navigation without unnecessary stops. Objects are typically visible at the source location without requiring searching.

## SOP
1. Check inventory (verify not carrying required object)
2. Navigate directly to object's source location
3. Pick up/take the required object
4. Navigate directly to target location
5. Place/move the object to target

## Cases
**Task**: Put some cd on sidetable  
**Objects**: cd 1 on diningtable 1  
**Target**: sidetable 1  
**Strategy used**: Direct fetch-and-place  
**Navigation pattern**: inventory → diningtable 1 (source) → sidetable 1 (target)  
**Total steps**: 5  
**Key insight**: Straightforward single-object transfer requires minimal complexity  
**Outcome**: Success achieved with basic fetch-and-place pattern  

**Task**: Put some spraybottle on toilet  
**Objects**: spraybottle 2 in cabinet 2 (discovered after checking cabinet 1 first)  
**Target**: toilet 1  
**Strategy used**: Direct fetch-and-place with source discovery  
**Navigation pattern**: inventory → cabinet 1 → cabinet 2 (source) → toilet 1 (target)  
**Total steps**: 7  
**Key insight**: Multi-location source discovery is sometimes needed to locate the required object  
**Outcome**: Success achieved with direct fetch-and-place pattern after source discovery  

## Stats
success_rate: 1
uses: 2