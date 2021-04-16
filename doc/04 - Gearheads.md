# Gearheads

As we discussed, existing hobby grade motors probably won't be able to rotate at the desired 0.000696 RPM.
We'll need to design a gearbox that can take a higher RPM from the motor, and bring it down to the lower RPM.
Now, gearboxes are a whole can of worms we're going to open.

## The gear

_The Gear._
This little invention that you can [track back thousands of years](https://en.wikipedia.org/wiki/Gear#History) and is still in use today.
From gearboxes in cars to mechanical clocks to cameras and more!
The idea of a gear is that it interlocks with a similar object, and through it's rotation imparts a movement.
Gear ratios, the ratio of the amount of teeth between two or more gears, have the added benefit that they can increase or decrease the amount of torque, at the benefit or cost of rotational speed respectively.

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Gear_reducer.gif" height=400 alt="Animation of gears">
<p>Gears rotating. The smaller gear has a larger rotational velocity to keep up with the larger gear, Simiprof, 2013.</p>
</div>

Now, these things have been around for so long, that humans have tried a lot of things with them, and their design.
Equally ubiquitous are terms for describing very specific parts of the gear.
We won't be going into detail on these.
But we'll have warned you, lest we make a mechanical engineer very sad.

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/28/Gear_words.png" height=400 alt="Gear terminology">
<p>Terminology used to describe the anatomy of a gear, Honaroog, 2007.</p>
</div>

So what about these ratios?
This is pretty simple, really.
If you take the amount of teeth of one gear, and divide it by the amount of teeth on the other gear, you get the gear ratio.
For example: gear A has 10 teeth, and we interface it with gear B with 100 teeth.
In order for gear A to completely rotate gear B, it needs to rotate 10 times to "visit" the 100 teeth of gear B.
Ergo, the gear ratio here is 10 : 1.
10 rotations cause 1 rotation.
The reverse is also true, if we take gear B as our input gear now, every rotation of gear B causes 10 rotations of gear A.
This gear ratio is 1 : 10.
Some people like to use decimal numbers to indicate their ratios, such as 0.1 : 1.
Mainly for less evenly dividable values, such as 23 : 31 to 1 : 1.347.
This is purely a matter of preference, but the end results are the same.

### I like the cut of your ~~jib~~ Gear

Gears can come in a few shapes and sizes, as we've discussed, but they can also come in different cuts.
A cut determines how the teeth are shaped around the axis of rotation.
The most well know cuts are the straight cuts.

## Metal boxes

Taking a few of these gears, and putting them in a neat little box, is commonly referred to as a gearbox.
Shocker, we know.
But these little (or large) things have been very useful to us.

### Planetary gearset

While stargears are, to the best of our knowledge, not a real thing, sun gears and planetary gears are.
These are found in, get this, planetary gearboxes.
I wonder where they got this term from?
I guess we'll never know.

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Epicyclic_gear_ratios.png" height=400 alt="Planetary Gearset">
<p>A planetary gearset. Red is the ring gear, blue are the planetary gears, yellow is the sun gear and green is the carrier, Wapcaplet, 2006</p>
</div>

The planetary gearset has a few configurations.
Generally an input and output is defined, and the remaining element (the planetary gears and carrier are considerd part of the same element) is held stationary.
For example: you can take the sun gear as input, and the carrier as output, this would mean that you would need to hold the ring gear stationary
