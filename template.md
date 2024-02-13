---
title:  'Title Slide'
subtitle: "Title Subtitle"
author:
- Johnny Tran
date: 2024
keywords: [powerpoint]
monofont: Source Code Pro
lang: en-US
version: 0.1.0
slide-level: 2
---
::: notes
TODO
:::

# Section Header
## Title and Content
* Level 1
   * Level 2
      * Level 3
         * Level 4
            * Level 5

## Two Content
:::::::::::::: {.columns}
::: {.column width="50%"}

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula.

:::
::: {.column width="50%"}

### Foo
#### Bar
##### Fizz
###### Bang

:::
::::::::::::::

## Two Content w/ Title
:::::::::::::: {.columns}
::: {.column width="80%"}
### Column 1
* Level 1
   * Level 2
      * Level 3
         * Level 4
            * Level 5
:::
::: {.column width="20%"}
### Column 2
Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula.

:::
::::::::::::::

## Comparison
:::::::::::::: {.columns}
::: {.column width="50%"}

| Heading | Heading | Heading |
| --- | --- | --- |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |

:::
::: {.column width="50%"}

![Alt text looks like this](diagram.svg){width=25%}

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

## Code
Python:
```python
s = "hello world!"
print s
```
Something else:
```
Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula.
```
