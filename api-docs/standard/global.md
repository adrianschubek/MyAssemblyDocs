---
tags: [api, std.lib]
label: .global
---
# .global
Sets the global entry point to the specified branch.
!!!primary
A program must contain exactly one **.global** statement
!!!
### Syntax
```
.global <branch>
```
##### Parameters
- *branch* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/datatypes/#branch)
### Example
```
//...
.global main
main:
//...
```
### History
- [!badge text="0.1"] added
