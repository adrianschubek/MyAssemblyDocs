---
tags: [api, std.lib]
label: sys
---
# sys
Calls a system function.
!!!danger Internal API
This is an internal function and should not be used in user code as function names and implementations depend on the version and specific platform.
Use [bl](/api-docs/bl) instead.
!!!
### Syntax
```
sys <function>
```
##### Parameters
- *function* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Name"](/api-docs/datatypes/#name)
### Example
```
sys printf
```
### History
- [!badge text="0.1"] added
