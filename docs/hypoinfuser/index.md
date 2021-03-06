---
title: Hypoinfuser
nav: thermal-innovation
image:
  - alt: Hypoinfuser (Basic)
    file: thermal-innovation/hypoinfuser-basic.png
  - alt: Hypoinfuser (Hardened)
    file: thermal-innovation/hypoinfuser-hardened.png
  - alt: Hypoinfuser (Reinforced)
    file: thermal-innovation/hypoinfuser-reinforced.png
  - alt: Hypoinfuser (Signalum)
    file: thermal-innovation/hypoinfuser-signalum.png
  - alt: Hypoinfuser (Resonant)
    file: thermal-innovation/hypoinfuser-resonant.png
  - alt: Hypoinfuser (Creative)
    file: thermal-innovation/hypoinfuser-creative.png
recipes:
  crafting:
    - hypoinfuser-basic
    - hypoinfuser-hardened
    - hypoinfuser-reinforced
    - hypoinfuser-signalum
    - hypoinfuser-resonant
---

A **hypoinfuser** (also known as an **injector**) is a tool that stores and
injects [fluid potions](/docs/potion-fluid/).


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting %}


Usage
-----

### Filling and draining
A hypoinfuser can hold the [fluid form](/docs/potion-fluid/) or any regular
[potion](https://minecraft.gamepedia.com/Potion). It can be filled and drained
manually by using it on a block that can hold fluid potions, or automatically
using a [fluid transposer](/docs/fluid-transposer/) or similar.

A basic hypoinfuser can store up to 2
[buckets](https://minecraft.gamepedia.com/Bucket) worth of a potion (2,000 mB).
This can be increased by upgrading the hypoinfuser to a higher [tier](#tiers).

A hypoinfuser only works with regular potions; it does not work with [splash
potions](https://minecraft.gamepedia.com/Splash_Potion) or [lingering
potions](https://minecraft.gamepedia.com/Lingering_Potion).

### Potion injection
A filled hypoinfuser is capable of automatically infusing the wielder with the
contained potion. This can be enabled and disabled by pressing "Cycle Item Mode"
(V by default) while holding the hypoinfuser.

An active hypoinfuser automatically infuses the wielder with the contained
potion when the potion's effect is not yet applied, and when the effect is about
to wear off. It infuses 50 mB of the potion at a time. The duration of the
applied effect is one fourth of the contained potion's duration. Potions with
instant effects are applied at half the power.

Potion effects automatically applied by a hypoinfuser do not have particle
effects.

A filled hypoinfuser can be used on other players or
[mobs](https://minecraft.gamepedia.com/Mob) to forcibly inject the potion into
them. When used in this way, it infuses 250 mB of the potion at a time. The
duration of the applied effect is half of the contained potion's duration.
Potions with instant effects are applied at half the power.

### Enchantments
A hypoinfuser can be enchanted with [Holding](/docs/holding/) to increase its
capacity.

| Holding level | Capacity multiplier |
|---
| I | × 1.5 |
| II | × 2 |
| III | × 2.5 |
| IV | × 3 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}


Tiers
-----

Hypoinfusers come in six [tiers](/docs/tiers/).

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Tier | Capacity | Note |
|---
| Basic | 2,000 mB |
| Hardened | 6,000 mB |
| Reinforced | 12,000 mB |
| Signalum | 20,000 mB |
| Resonant | 30,000 mB |
| Creative | N/A | Provides an unlimited amount of the potion it holds. |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-semi-compress}
</div>
{::options parse_block_html="false" /}
