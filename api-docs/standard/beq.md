---
tags: [api, std.lib]
label: beq
---
# beq
Branch if equal ([CMP](/api-docs/standard/datatypes.md#register) == 0).
### Syntax
```
beq <branch>
```
##### Parameters
- *branch* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
### Example
```
beq foo
//...
foo:
```
### History
- [!badge text="0.1"] added
