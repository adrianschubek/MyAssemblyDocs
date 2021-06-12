---
tags: [api, std.lib]
label: mov
---
# mov
Sets a register to a value.
### Syntax
```
mov <target> <source>
```
##### Parameters
- *target* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/datatypes/#branch)
- *source* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/datatypes/#branch) or [!badge variant="info" text="Number"](/api-docs/datatypes/#number)
### Example
```
mov r0, r1
mov r2, 33
```
### History
- [!badge text="0.1"] added
