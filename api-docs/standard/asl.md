---
tags: [api, std.lib]
label: asl
---
# asl
Arithmetic shift left.
!!!info
This is an alias for [lsl](/api-docs/standard/lsl.md)
!!!
### Syntax
```
asl <result> <x> <y>
asl <result> <z>
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
asl r0, r1, 5
asl r0, r0, r4
asl r0, 8
asl r0, r2
```
### History
- [!badge text="0.1"] added
