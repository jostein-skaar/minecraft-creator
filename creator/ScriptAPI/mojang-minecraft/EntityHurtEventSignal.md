---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/Mojang/MinecraftScriptingApiDocsGenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: mojang-minecraft.EntityHurtEventSignal Class
description: Contents of the mojang-minecraft.EntityHurtEventSignal class.
---
# EntityHurtEventSignal Class
>[!IMPORTANT]
>These APIs are experimental as part of GameTest Framework. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to GameTest Framework APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

Manages callbacks that are connected to when an entity is hurt.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)
  
### **subscribe**
`
subscribe(callback: (arg: EntityHurtEvent) => void, options?: EntityEventOptions): (arg: EntityHurtEvent) => void
`

Adds a callback that will be called when an entity is hurt.
#### **Parameters**
- **callback**: (arg: [*EntityHurtEvent*](EntityHurtEvent.md)) => *void*
- **options**?: [*EntityEventOptions*](EntityEventOptions.md) = `null`

#### **Returns** (arg: [*EntityHurtEvent*](EntityHurtEvent.md)) => *void*


### **unsubscribe**
`
unsubscribe(callback: (arg: EntityHurtEvent) => void): void
`

Removes a callback from being called when an entity is hurt.
#### **Parameters**
- **callback**: (arg: [*EntityHurtEvent*](EntityHurtEvent.md)) => *void*


> [!WARNING]
> This function can throw errors.

