---
author: mammerla
ms.author: v-jillheaden
title: Entity Documentation - minecraft:movement.jump
ms.prod: gaming
---

# Entity Documentation - minecraft:movement.jump

`minecraft:movement.jump` causes the entity to jump as it moves with a specified delay between jumps.

> [!IMPORTANT]
> In order to follow targets, this entity must have `minecraft:behavior.slime_attack`, otherwise the entity will jump in the direction it's looking in.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
| jump_delay| [0.0, 0.0]| Range [a, b]| Delay after landing when using the slime move control. |
| max_turn| 30.0| Decimal| The maximum number in degrees the entity can turn per tick. |

## Example

```json
"minecraft:movement.jump":{
    "jump_delay": [0.0, 0.0],
    "max_turn": 30.0
}
```

## Vanilla entities examples

### slime

```json
"minecraft:movement.jump": {
          "jump_delay": [ 0.5, 1.5 ]
        }
```

## Vanilla entities using `minecraft:movement.jump`

- [magma_cube](../../../../Source/VanillaBehaviorPack_Snippets/entities/magma_cube.md)
- [slime](../../../../Source/VanillaBehaviorPack_Snippets/entities/slime.md)