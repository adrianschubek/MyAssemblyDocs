---
tags: [api, std.lib]
label: lsl
---
# lsl
Logical shift left.
!!!info
This is an alias for [asl](/api-docs/standard/asl.md)
!!!
### Syntax
```
lsl <result> <x> <y>
lsl <result> <z>
```
##### Parameters
###### Variant 1: `result` = `x` << `y`
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *y* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
###### Variant 2: `result` = `result` << `x`
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
### Example
```
lsl r0, r1, 5
lsl r0, r0, r4
lsl r0, 8
lsl r0, r2
```
### History
- [!badge text="0.1"] added
