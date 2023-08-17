---
title: "Edge Case: Listas aninhadas e mistas"
categories:
  - Edge Case
tags:
  - content
  - css
  - edge case
  - lists
  - markup
last_modified_at: 2017-03-09T14:25:52-05:00
---

Listas aninhadas e mistas são uma fera interessante. É um caso de canto para garantir que as listas dentro das listas não quebrem a ordem de numeração da lista ordenada e os estilos de lista sejam profundos o suficiente.

## Ordered -- Unordered -- Ordered

1. ordered item
2. ordered item 
  * **unordered**
  * **unordered** 
    1. ordered item
    2. ordered item
3. ordered item
4. ordered item

## Ordered -- Unordered -- Unordered

1. ordered item
2. ordered item 
  * **unordered**
  * **unordered** 
    * unordered item
    * unordered item
3. ordered item
4. ordered item

## Unordered -- Ordered -- Unordered

* unordered item
* unordered item 
  1. ordered
  2. ordered 
    * unordered item
    * unordered item
* unordered item
* unordered item

## Unordered -- Unordered -- Ordered

* unordered item
* unordered item 
  * unordered
  * unordered 
    1. **ordered item**
    2. **ordered item**
* unordered item
* unordered item