---
tags: [api, std.lib]
label: div
---
# div
Divides two numbers. `result` = `x` / `y`.
### Syntax
```
div <result> <x> <y>
```
##### Parameters
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *y* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
### Example
```
div r0, r1, 5
div r2, r2, -7
div r0, r0, r4
```
### History
- [!badge text="0.1"] added
