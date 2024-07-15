---
title:  'Title Slide'
subtitle: "Title Subtitle"
author:
- Johnny Tran
date: 2024
keywords: [powerpoint]
# monofont: Source Code Pro
lang: en-US
version: 0.1.0
slide-level: 2
---

[//]: # (TODO comment)

# Section Header
## Title and Content

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

* Level 1
   * Level 2
      * Level 3
         * Level 4
            * Level 5
1. Level 1
   1. Level 2
      1. Level 3
         1. Level 4
            1. Level 5

## Two Content
:::::::::::::: {.columns}
::: {.column}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 

:::
::: {.column}

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

:::
::::::::::::::

## Two Content w/ Title
:::::::::::::: {.columns}
::: {.column}
### Left

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 

:::
::: {.column}
### Right

* Level 1
   * Level 2
      * Level 3
         * Level 4
            * Level 5
1. Level 1
   1. Level 2
      1. Level 3
         1. Level 4
            1. Level 5

:::
::::::::::::::

## Table
| Heading | Heading | Heading |
| --- | --- | --- |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |

## Comparison
:::::::::::::: {.columns}
::: {.column}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 

:::
::: {.column}

![Alt text looks like this](diagram.svg)

:::
::::::::::::::

::: notes
<!--
@startuml diagram
Alice -> Bob: Hello
Bob -> Alice: Hi!
Alice -> Charlie: Greetings!
@enduml
-->
:::

## Code Block
```{#python .python}
#!/usr/bin/env python
from __future__ import with_statement
from sys import path as thing

print(thing)

assert True  # keyword

def foo():  # function definition
    return []
```
