---
tags: [api, std.lib]
label: lsr
---
# lsr
Logical shift right.
### Syntax
```
lsr <result> <x> <y>
lsr <result> <z>
```
##### Parameters
###### Variant 1: `result` = `x` >>> `y`
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *y* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
###### Variant 2: `result` = `result` >>> `x`
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
### Example
```
lsr r0, r1, 5
lsr r0, r0, r4
lsr r0, 8
lsr r0, r2
```
### History
- [!badge text="0.1"] added
