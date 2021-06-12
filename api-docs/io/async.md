---
tags: [api, io.lib]
title: async
---
# async
Starts a function asynchronously.
!!!info
Make sure to [include](/api-docs/include) the `` io.lib`` library first.
!!!
!!!light Experimental Feature
This feature can be unstable and should not be used in production yet. 
!!!
### Syntax
```
async <controller> <function>
```
##### Parameters
- *controller* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Register"](/api-docs/datatypes/#register)
- *function* [!badge variant="danger" text="required"] Type: [!badge variant="info" text="Branch"](/api-docs/datatypes/#branch) 
### Example
```
async r0, main
```
### History
- [!badge text="0.2"] added
