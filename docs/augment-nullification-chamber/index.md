---
title: 'Augment: Nullification Chamber'
nav: thermal-expansion
image:
  - alt: Nullification chamber augment
    file: thermal-expansion/augment-machine-secondary-null.gif
redirect_from:
  - /docs/thermal-expansion/augments/machine-secondary-nullifier/
recipes:
  crafting:
    - augment-machine-secondary-null
---

A **nullification chamber** is an [augment](/docs/augments/) that destroys
excess secondary products when an applicable [machine](/docs/machines/)'s
secondary output slot/tank is full.


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}


Usage
-----

### Installation
A nullification chamber can be installed in the Augmentation tab in a
[machine](/docs/machines/)'s GUI. It can only be installed in machines that can
produce secondary products, like [pulverizers](/docs/pulverizer/) and [induction
smelters](/docs/induction-smelter/).

### Effects
When a [machine](/docs/machines/)'s secondary output slot/tank is full, but the
machine still has room to produce its primary product, an installed
nullification chamber destroys any more produced secondary products. This allows
the machine to keep working regardless of whether its secondary output slot/tank
is full.
