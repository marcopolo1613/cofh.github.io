---
title: 'Augment: Metallurgical Recovery'
nav: thermal-expansion
image:
  - alt: Metallurgical recovery augment
    file: thermal-expansion/augment-machine-smelter-flux.png
recipes:
  crafting:
    - augment-machine-smelter-flux
---

A **metallurgical recovery** [augment](/docs/augments/) provides a chance for an
[induction smelter](/docs/induction-smelter/) to not consume metallurgical
fluxes like [sand](https://minecraft.gamepedia.com/Sand) and [rich
slag](/docs/rich-slag/).


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}


Usage
-----

### Installation
A metallurgical recovery augment can be installed in the Augmentation tab in an
[induction smelter](/docs/induction-smelter/)'s GUI. It can be installed
multiple times, stacking its effects.

### Effects
Installed metallurgical recovery augments provide a chance for an [induction
smelter](/docs/induction-smelter/) to not consume a metallurgical flux after an
operation. However, they also increase the amount of energy required per
operation.

Metallurgical fluxes are items that are commonly used in smelter recipes:
[sand](https://minecraft.gamepedia.com/Sand), [soul
sand](https://minecraft.gamepedia.com/Soul_Sand), [rich slag](/docs/rich-slag/)
and [cinnabar](/docs/cinnabar/).

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Installed amount | Flux reuse chance | Energy increase |
|---
| 1 | 15% | + 10% |
| 2 | 30% | + 20% |
| 3 | 45% | + 30% |
| 4 | 60% | + 40% |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}
</div>
{::options parse_block_html="false" /}

If metallurgical recovery augments are installed together with other augments
that increase the amount of energy required per operation, their energy increase
percentages are added together before being applied to the amount of energy.
