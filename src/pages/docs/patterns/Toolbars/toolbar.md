---
title: "Toolbar"
description: "A toolbar is a set of actions related to a context grouped in a bar."
layout: "guide"
weight: 1
---

### Description

{$page.description}

### Usage

A toolbar is a generic bar that helps grouping actions in a way that they are visually organized for any context of use in Lexicon. Its height changes depending on the height of the elements it contains. The toolbar always maintains the vertical alignment.

You only need to define the number of blocks or containers that you want to have in your toolbar and place the elements inside it. These blocks or containers are of 2 different types:

* Field: is used to make tight groups.
* Content: is used to span as much as possible in the rest of the space. In case there are several contents the available space is equally divided.

### Layout

For a better understanding of the previous sections, here are some example layouts:

Example 1: Three consecutive fields

![toolbar layout example with three fields](../../../images/toolbarLayoutExample1.png)

Example 2: Three consecutive contents

![toolbar layout example with three contents](../../../images/toolbarLayoutExample2.png)

Example 3: Field - Content - Field

![toolbar layout example with field - content - field](../../../images/toolbarLayoutExample3.png)

Example 4: Field - Field - Content - Content

![toolbar layout example with field - field - content - content](../../../images/toolbarLayoutExample4.png)

### Attributes

* A toolbar has a maximum height of 56px.
* The top and bottom margins are 12px to small size components and 8px to default size components as the search field.
* Left and right margins are always 16px.
* The distance between components inside a toolbar is 16px.