---
tags: [api, io.lib]
label: printf
---
# printf
Fromats and prints a string.
### Syntax
```
bl printf
```
##### Registers
- ``r0`` [!badge variant="danger" text="required"] Type: [!badge variant="info" text="String"](/api-docs/datatypes/#string) Format string
- ``r1`` to ``r12``  [!badge variant="secondary" text="optional"] Type: [!badge variant="info" text="String"](/api-docs/datatypes/#string) or [!badge variant="info" text="Number"](/api-docs/datatypes/#number) Parameters inserted in placeholders
### Example
```
bl printf
```
### History
- [!badge text="0.1"] added
