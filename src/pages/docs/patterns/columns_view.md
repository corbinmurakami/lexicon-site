---
title: "Columns View WIP"
description: "Columns view, also known as Miller columns or Cascading list, is a visualization type that allows to move faster in a tree view seeing several depth levels at same time."
layout: "guide"
weight: 1
hidden: yes
---
<span class="label label-info">PORTAL</span>

### Description

{$page.description}

### Usage

#### When to use it

Columns view is a good pattern to navigate through dictionaries being able to see and create categories in a fast way. But it can fit well in other scenarios when just the visualization is necessary to know the depth of the tree or discover elements at different levels.

#### When must not use it

Do not use this pattern if you need to show information further from the item title.

#### Behaviour

In this pattern it is pretty important to always update the row state in each of the columns and it is also important to update the breadcrumb as it is an important component in this pattern as it provides feedback on the element position in the tree.

