---
tags: [api, std.lib]
label: neg
---
# neg
Negates a value. `result` = -`x`.
### Syntax
```
neg <result> <x>
```
##### Parameters
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
### Example
```
neg r0, r1
neg r2, 6
neg r0, -7
```
### History
- [!badge text="0.1"] added
