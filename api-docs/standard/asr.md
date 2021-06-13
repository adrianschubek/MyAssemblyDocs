---
tags: [api, std.lib]
label: asr
---
# asr
Arithmetic shift right.
### Syntax
```
asr <result> <x> <y>
asr <result> <z>
```
##### Parameters
###### Variant 1: `result` = `x` >> `y`
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *y* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
###### Variant 2: `result` = `result` >> `x`
- *result* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
### Example
```
asr r0, r1, 5
asr r0, r0, r4
asr r0, 8
asr r0, r2
```
### History
- [!badge text="0.1"] added
