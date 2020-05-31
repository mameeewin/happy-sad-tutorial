# Smiley-frowny-tutorial
https://makecode.microbit.org/beta#tutorial:github:mameeewin/happy-sad-tutorial/README
## Step 1
show a string
```blocks
basic.forever(function () {
	basic.showString("Hello!")
})

```
## Step 2
show happy face
```blocks
basic.forever(function () {
	basic.showString("Hello!")
basic.showString(":)")

})

```
## Step 3
Use showLeds :) and delete showString :) And Do It The Same
```blocks
basic.forever(function () {
    basic.showString("Im Happy")
    basic.showLeds(`
        . # . # .
        . . . . #
        . . . . #
        . . . . #
        . # . # .
        `)
    basic.pause(100)
    basic.showString("Im Sad")
    basic.showLeds(`
        . # . . #
        . . . # .
        . . . # .
        . . . # .
        . # . . #
        `)
    basic.pause(100)
})

```
## Step 4
you Did the Happy Sad And smile face and Sad face go on do it on your own
But what if we want to control it
```blocks
input.onButtonPressed(Button.A, function () {
    basic.showString("Im Happy")
    basic.showLeds(`
        . # . # .
        . . . . #
        . . . . #
        . . . . #
        . # . # .
        `)
})
input.onButtonPressed(Button.AB, function () {
    basic.showIcon(IconNames.Surprised)
})
input.onButtonPressed(Button.B, function () {
    basic.showString("Im Sad")
    basic.showLeds(`
        . # . . #
        . . . # .
        . . . # .
        . . . # .
        . # . . #
        `)
})
basic.forever(function () {
	
})

```
## Step 5
Try it in Your micro:bit!!
  




> Open this page at [https://mameeewin.github.io/happy-sad-tutorial/](https://mameeewin.github.io/happy-sad-tutorial/)

## Tutorial
*[tutorial](/Happy-Sad/tutorial)

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/mameeewin/happy-sad-tutorial** and import

## Edit this project ![Build status badge](https://github.com/mameeewin/happy-sad-tutorial/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/mameeewin/happy-sad-tutorial** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/mameeewin/happy-sad-tutorial/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
