# Final-Gala Tutorial

## Step 1
During this tutorial we will show you how to make a propeller appear on the screen of the micobit. 
For this, we only need the ``||basic:forever||`` block. You can delete a block by dragging the block to the toolbox on the left of your screen. 
You can try this now for the ``||basic:on start||`` block.

## Step 2

Now we have to add a block that shows lights. You can find this block in the ``||basic:basis||`` group. Notice the color of the word ``||basic:showLeds||`` is blue. This gives an indication in which group we have to look for the block. 

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```

## Step 3
You can make a dot light up by clicking the middle button on the 'show leds' block. You can make it stop by clicking the button again. 

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . # . .
        . . . . .
        . . . . .
        `)
})
```
## Step  4 
We can now make a cross by clicking on 2 led lights above, under, left and right from the middle point.

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        . . # . .
        # # # # #
        . . # . .
        . . # . .
        `)
})
```
## Step 5
To make a nice looking propeller, we have to shift the dots clockwise. We can do this by clicking on the button to make the led light go dark and then clicking on the buttons next to it in a clockwise fashion.
For example to the right for the upper 2 lights, down for the right 2 lights and so on...

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . # .
        # # . # .
        . . # . .
        . # . # #
        . # . . .
        `)
})
```
## Step 5
Well done! If you want a more challenging coding excercise about the propeller, be sure to try out our other tutorial.
