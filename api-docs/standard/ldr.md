---
tags: [api, std.lib]
label: ldr
---
# ldr
Loads a [datavar](/api-docs/standard/datatypes.md#datavar).
!!!info
Loading a datavar into a register will load its memory address rather than its value.
To get its actual value load the same register again using ldr.
```
a = 500
//...
ldr r0, a
ldr r0, [r0]
// r0 is now 500
```
!!!
### Syntax
```
ldr <branch> <var>
```
##### Parameters
- *branch* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
- *var* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#datavar)
### Example
```
a = 100
//...
ldr r0, a
```
### History
- [!badge text="0.1"] added
