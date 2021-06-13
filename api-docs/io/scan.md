---
tags: [api, io.lib]
label: scan
---
# scan
Scans an input.
!!!primary Blocking function
Calling this function will halt the execution.
!!!
### Syntax
```
bl scan
```
##### Registers
- ``r0`` [!badge variant="danger" text="required"] Type: [!badge variant="info" text="String"](/api-docs/datatypes/#string) will contain the scanned string.
### Example
```
bl scan
```
### History
- [!badge text="0.1"] added
