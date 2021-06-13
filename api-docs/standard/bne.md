---
tags: [api, std.lib]
label: bne
---
# bne
Branch if not equal ([CMP](/api-docs/standard/datatypes.md#register) != 0).
### Syntax
```
bne <branch>
```
##### Parameters
- *branch* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/standard/datatypes.md#branch)
### Example
```
bne foo
//...
foo:
```
### History
- [!badge text="0.1"] added
