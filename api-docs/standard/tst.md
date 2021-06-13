---
tags: [api, std.lib]
label: tst
---
# tst
Compares two values using bitwise AND operator and sets the [CMP](/api-docs/standard/datatypes.md#register) register.

- CMP = 1 if `x` & `y` == 1
- CMP = 0 if `x` & `y` == 0
### Syntax
```
tst <x> <y>
```
##### Parameters
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
- *y* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
### Example
```
tst r0, r1
tst r2, 8
tst 12, 55
```
### History
- [!badge text="0.1"] added
