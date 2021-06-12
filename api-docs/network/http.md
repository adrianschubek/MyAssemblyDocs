---
tags: [api, net.lib]
title: http
---
# http
Opens a http request.
!!!info
Make sure to [include](/api-docs/include) the ``net.lib`` library first.
!!!
!!!light Experimental Feature
This feature can be unstable and should not be used in production yet.
!!!
### Syntax
```
bl http
```
##### Registers
- ``r0`` [!badge variant="danger" text="required"] Type: [!badge variant="info" text="String"](/api-docs/datatypes/#string) result will be stored here
- ``r1`` [!badge variant="danger" text="required"] Type: [!badge variant="info" text="String"](/api-docs/datatypes/#string) url
### Example
```
bl http
```
### History
- [!badge text="0.2"] added
