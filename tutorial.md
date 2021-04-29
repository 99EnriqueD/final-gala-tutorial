# Final-Gala Tutorial

## Step 1
Hello there, Thanks for checking out team RVO-Society's final gala booth!
This short tutorial will give you a taste of what it's like to program with MakeCode, a simple programming language we used in our IoTeach product.
If you get stuck, be sure to ask any of us in the booth. We are happy to help!
Let's go!

## Step 2
"Hello world!" is a classic phrase in the programming world. 
It's a way to show that our code actually runs.
Let's make your (virtual) micro:bit say "Hello world!" by adding a ``||basic:show string||`` block to the ``||basic:on start||`` block that's already in your program. 
You can find it in the ``||basic:Basic||`` folder of the same color.

```blocks
basic.showString("Hello world!")
```

## Step 3
Great, we can use the micro:bit's led lights for far more than showing messages in English.
After we're done greeting the world, we can show a propeller (or whatever else you like) by adding a ``||basic:show leds||`` block to the ``||basic:on forever||`` block that's already in your program.
You can toggle individual leds on/off by clicking on the squares in the ``||basic:show leds||`` block.

```blocks
basic.forever(function () {
    basic.showLeds(`
    . # . . .
    . # . # #
    . . # . .
    # # . # .
    . . . # .
    `)
})
```

## Step 4
Since we are programming on a micro:bit (albeit a virtual one), let's use some of that (virtual) hardware!
Add an ``||input: on button A pressed||`` block anywhere outside of the ``||basic:on forever||`` or ``||basic:on start||`` blocks.
This will run any blocks inside of it whenever the micro:bit's A button is touched.

```blocks
input.onButtonPressed(Button.A, function () {
})
```

## Step 5
The micro:bit als has a number of built-in sensors. 
Let's have the micro:bit display the current (virtual) light brightness whenever we press its ``||input:A||`` button.
Use the ``||basic:show number||`` block along with the ``||input:light level||`` to accomplish this.
Be sure to use the hint if you get stuck!

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showNumber(input.lightLevel())
})
```

## Step 6
On your virtual micro:bit you can change how bright its environment is. 
After you press the ``||input:A||`` button, a half-filled circle will appear on your virtual micro:bit.
Go ahead and change its light level by dragging up or down on this circle with your mouse.
Press the ``||input:A||`` again button and, voila, the correct number appears on the micro:bit's leds.

## Step 7
That's all for this tutorial! 
Play around with your program by changing the message in ``||basic:show string||``, changing the picture that is shown afterwards in ``||basic:show leds||``, or display light levels when pressing the ``||input:B||`` button instead!

Go to the last step for a few fun links :)

## Step 8
You made it,
I hope you enjoyed this little tutorial we made for you! Check out the links below for more programming fun!

Click [here](https://makecode.microbit.org/#tutorial:github:99enriqued/final-gala-simulator/tutorial) to try the simulator of the IoTeach health game in MakeCode.
Click [here](https://makecode.microbit.org/#tutorial:github:99enriqued/receiver-tutorial/tutorial) to try your hand at one of the tutorials for young students that is shipped with the IoTeach project box. 

