---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/Mojang/MinecraftScriptingApiDocsGenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: mojang-minecraft.EntityMovementSkipComponent Class
description: Contents of the mojang-minecraft.EntityMovementSkipComponent class.
---
# EntityMovementSkipComponent Class
>[!IMPORTANT]
>These APIs are experimental as part of GameTest Framework. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to GameTest Framework APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

## Extends
- [*IEntityComponent*](IEntityComponent.md)

When added, this move control causes the mob to hop as it moves.

## Properties
### **id**
`read-only id: string;`

Identifier of this component. Should always be minecraft:movement.skip.

Type: *string*


### **maxTurn**
`read-only maxTurn: number;`

The maximum number in degrees the mob can turn per tick.

Type: *number*


