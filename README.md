# Less Input Delay
This is a **software modification** to Super Smash Bros. Ultimate that removes 1 frame of input
delay.

This is performed by disabling graphical vsync and manually timing the game's core logic to run on
the vsync timer.

## Installation
You can install this by grabbing the latest `libless_delay.nro` file from this repository's
Releases page and placing it here: `sd:/atmosphere/contents/01006A800016E000/romfs/skyline/plugins/libless_delay.nro`

You will also need skyline, which you can find from basically any Ultimate modding tutorial.

## Pitfalls
On some stages/some matchups/some characters, when the graphics pipeline is getting flooded with
rendering commands, you **may** encounter purely visual frame drops.

These frame drops, as I just said, are entirely visual. I have been playing with this for 3 weeks
and have encountered absolutely zero noticeable frame drops.

You **will** encounter some form of frame drops when recording or streaming using SysDVR/SysDVR-patches.
These are unavoidable and can be reduced by dropping your recording framerate from 60fps -> 30fps
or disabling them entirely.

## Wifi Safeness?
This is a client side mod that changes the graphics pipeline in a very slight way. Because it is client
side, this will work online in all capacities and offline in all capacities. I do not recommend using this
to practice offline unless the tournaments that you go to are also running this mod because you'll
quickly realize how much you hate that extra 1 frame (well maybe not in Ultimate's engine, but it's
very noticeable in HDR which this was originally developed for).

## Visual indicator for wifi brackets?
I didn't care this time around, there will be no visual indicator. It is indicated to me that
Ultimate players do not care about online competitive integrity as there have been numerous forks
of the original source code for my online arena latency slider that allow for disabling
the arena UI text that says you have it. 

## Enjoy playing a faster game!