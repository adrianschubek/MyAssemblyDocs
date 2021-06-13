---
tags: [api, std.lib]
label: Datatypes
order: 9999
---
# Datatypes
A list of all available datatypes

---
### Name
A name is a sequence of characters used for e.g. variable names. <br>
For example ``foo``, ``r12``, ``bar987!`` are valid names.
!!!warning
It is discouraged to start a name with a character other than a char from ``a`` to ``z``.
!!!
---
### String
A string is a sequence of characters surrounded by quotation marks (""). <br>
For example ``"This is a string"``

---
### Number
A sequence of digits. First char can also be a ``-`` or ``+``.
Examples ``2021``, ``+1000``, ``-975``

---
### Boolean
Either ``true`` or ``false``

---
### Branch
A branch or jumpmark starts with a name and ends with a ``:``. Example: ``main:``.
!!!warning
A code line declaring a branch must only contain the branch.
!!!
!!!info
When referencing a branch leave out the ``:``
!!!

---
### Register
A register is holding a value. There are by default 16 registers ``r0`` to ``r15``.
- ``r0`` to ``r12`` user registers
- ``r13`` Link Register (LR)
- ``r14`` Comparison (CMP)
- ``r15`` Program Counter (PC)
!!!danger
The registers ``r14`` and ``r15`` are reserved for internal uses and should not be written to.
!!!
---
### Datavar
A variable declared in the ``.data``-block. Example: ``a = 512``, ``str = "foobar"`` or ``bool = true``.
General syntax ``<name> = <value>``.
!!!info
The value must be one of the following types: [String](/api-docs/datatypes#string), [Number](/api-docs/datatypes#number) or [Boolean](/api-docs/datatypes#boolean)
!!!
!!!warning
The name must be unique and not share its name with a [Register](/api-docs/datatypes#register)
!!!
!!!info
Loading a datavar into a register will load its memory address rather than its value.
```
a = 500
//...
ldr r0, a
// r0 now contains an address referencing a
```
!!!
---
### LoadedDatavar
A loaded var is a [Datavar](/api-docs/datatypes#datavar) loaded using e.g. [ldr](/api-docs/ldr).
!!!info
Loading a register referencing a datavar will load the actual value of this datavar.
```
// r0 is the memory address of a datavar
r0 = 19581040014
//...
ldr r0, [r0]
// r0 now contains the actual datavar value.
```
!!!
---
### Comment
Comments start with ``//`` and must be on a seperate line.

---
#### :icon-history: History 
- [!badge text="0.1"] introduced
