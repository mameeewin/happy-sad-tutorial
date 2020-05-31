# Smiley-frowny-tutorial

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
  


