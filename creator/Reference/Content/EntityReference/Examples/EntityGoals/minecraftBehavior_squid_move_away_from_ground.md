---
author: mammerla
ms.author: v-jillheaden
title: Entity Documentation - minecraft:behavior.squid_move_away_from_ground
ms.prod: gaming
---

# Entity Documentation - minecraft:behavior.squid_move_away_from_ground

`minecraft:behavior.squid_move_away_from_ground` compels an entity to swim away from the ground blocks.

> [!NOTE]
> This behavior can only be used by the `squid` entity type.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|priority|*not set*|Integer|The higher the priority, the sooner this behavior will be executed as a goal.|

## Example

```json
"minecraft:behavior.squid_move_away_from_ground":{
    "priority": 2
}
```

## Vanilla entities examples

### squid

```json
"minecraft:behavior.squid_move_away_from_ground": {
    "priority": 1
},
```

## Vanilla entities using `minecraft:behavior.squid_move_away_from_ground`

- [glow_squid](../../../../Source/VanillaBehaviorPack_Snippets/entities/glow_squid.md)
- [squid](../../../../Source/VanillaBehaviorPack_Snippets/entities/squid.md)
