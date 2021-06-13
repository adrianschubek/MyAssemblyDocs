---
tags: [api, std.lib]
label: cmp
---
# cmp
Compares two values and sets the [CMP](/api-docs/standard/datatypes.md#register) register.

- CMP = 1 if `x` greater than `y`
- CMP = 0 if `x` equals `y`
- CMP = -1 if `x` less than `y`
### Syntax
```
cmp <x> <y>
```
##### Parameters
- *x* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
- *y* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch) or [!badge variant="info" text="Number"](/api-docs/standard/datatypes.md#number)
### Example
```
cmp r0, r1
cmp r2, 8
cmp 12, 55
```
### History
- [!badge text="0.1"] added
