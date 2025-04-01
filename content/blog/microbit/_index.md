---
title: Micro:bit
summary: Create | Learn | Code
date: 2025-02-05
authors:
  - admin
tags:
  - Microbit
  - Create
  - Learn
  - Code
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com)"
---

Microb:bit

## What it is
![microbit](https://microbit.org/static/microbit-smile-leds-478a1ba3c16d65f2e4c0acfa3c0157b9.png)

Here are some blocks: 

```blocks
basic.showString("Hello world")
```

and more blocks:


```blocks
basic.forever(() => {
    basic.showLeds(`
        . # . # .
        # . # . #
        # . . . #
        . # . # .
        . . # . .
        `)
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .
        `)
})
```




