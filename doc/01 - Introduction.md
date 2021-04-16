# Introduction

The Stars!

The stars?

Yes! The stars! And those other stellar objects, too, I guess.

What about them?

Have you never wanted to take a photo of them?

Well sure, but my (phone) camera is not good enough to get nice results I can share on my [insert social media] page.
Even the moon can be tricky!

A-ha!
But it does not have to be that hard, you just need to know how to use your equipment to get the results you want!

But how?

Don't worry, people have been taking stellar pictures with cheap hardware for _years_, if they can get their amazing results, your modern smartphone can do it for sure.

## Stellar photography

Depicting the stars is an art as [old as time](https://en.wikipedia.org/wiki/History_of_astronomy).
It should therefore not be surprising that, not long after it was invented, this was also extended to photography.
While the initial [Daguerrotype](https://en.wikipedia.org/wiki/Daguerreotype) style photographs were only usable for bright objects, it wasn't too long after that new developments in photography allowed for more sensitivity to the dimmer objects.
For reference, the first successful Daguerrotype image of the sun's corona in 1851 took an 84 seconds exposure!

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/38/1851_07_28_Berkowski.jpg" width=400 alt="Daguerrotype of the sun, Johann Julius Friedrich Berkowski, 1851">
<p>Johann Julius Friedrich Berkowski, 1851</p>
</div>

It wasn't untill the widespread availability of [dry plate photography](https://en.wikipedia.org/wiki/Dry_plate) that astrophotography became a more manageable process.
Henry Draper, for example, used a 51 minute exposure in 1880 to be the first person to capture the Orion Nebula.
Where his colleague, Andrew Ainslie Common, built his own telescope in his shed and used several hour-long exposures of the same nebula to show stars that the human eye can not see three years later.
A similar process is still used today, known as "stacking".

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/en/f/fe/Henry_Drape_Orion_nebula_1880_inverted.jpg" width=400 alt="Orion Nebula, Henry Draper, 1880">
<p>Henry Draper, 1880</p>
</div>

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Orion-Nebula_A_A_Common.jpg" height=275 alt="Orion Nebula, Andrew Ainslie Common, 1883">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/04/18_inch_newtonian_telescope_back_yard_Ealing_London_Andrew_Ainslie_Common.png" height=275 alt="The telescope used by Andrew Ainslie Common, built into his shed, built in 1876, unknown date">
<p>Left: Andrew Ainslie Common, 1883, right: The telescope built by him</p>
</div>

If people that built their own telescopes in their backyards, with the technology of the day that fights against them in almost any conceivable way, can take the types of pictures shown above, we sure as hell can do it with the seas of information that can be found on the internet! Right?

Source(s): Wikipedia

## Collecting light

As you may have picked up on, or already knew, taking photos of things requires one element you don't have a lot of at night: light!
Generally speaking, short of going to a brighter area a camera has three things it can do to increase the amount of light that gets to the sensor; increase the diameter of the lens aperture, take a longer exposure, increase the ISO.
The aperture can only open so far, and is generally not enough to make up for the low light alone.
The ISO, simply said, is the camera multiplying the amount of measured light with some value.
Unfortunately, in systems with a low amount of measured data, noise has a strong effect on the end result.
Finally, if you increase the exposure time, you collect light over a longer amount of time, easy!
But hold on!
Doing this also increases the effect of motion blur, which isn't something you want for nice and crispy shots!

All these settings, and they all have their drawbacks!

## So what do _I_ need?

A camera.

Joking aside, you don't really need a good camera, but it's nice if you do.
Amateur astrophotographers have been using old webcams for about as long as they have been available.
More recently, Raspberry Pis have had some level of use, too.
That is not to say that a phone does not work.
At the other end of the scales you have your DSLR/Mirrorless cameras, and dedicated astrocameras.
These may be out of the price range of many people though.
It's worth mentioning that entry level DSLRs tend to be in the $300 bracket, and are usable for things other than pretty star pictures.

The main issue that most budding astrophotographers face is that they simply don't have a stable enough platform to take their pictures with.
While you can freehand a DSLR to take photos of the moon, getting Andromeda may not be as simple.
A good tripod or other stable mount may be needed.
Because these other objects are so dim, you need to increase the amount of time your camera takes to take a picture.
That, or you find a lens with a insanely large aperture, probably at an equally insane price.

But my pictures are still blurry!

Yes, well, while the camera may be perfectly still, the earth isn't.
You may have missed it, but once every 24 hours or so, we do a full rotation!
This has the effect of the illusion that the sky is moving around us.
Whether we are moving, or the sky is has little bearing on the result: The stars start streaking.

<div style="text-align:center">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6c/%E6%98%9F%E3%81%AE%E8%BB%8C%E8%B7%A1%E5%8D%81%E6%B4%A5%E5%B7%9D%E3%83%BB%E4%B8%8A%E6%B9%AF%E3%81%AB%E3%81%A6Img042.jpg" width=400 alt="Star trails, Akiyoshi's Room">
<p>Star trails, Akiyoshi's Room, unknown date</p>
</div>

While this has its artistic merit, it might not be what you want.
There's two main ways to solve this. We can decrease exposure time, reducing the amount of light per photo.
This has the issue that you need to take a lot more photos to gather the same amount of light.
Stacking is used to combine these images after the fact.
Alternatively we find a way to keep the camera pointed at the same point in the sky. Enter: The star tracker!

## Star trackers

Star trackers are neat little devices that counter the rotation of the earth.
Generally attached to a nice and steady tripod, they slowly rotate the camera around to, you guessed it, track the stars' motion.
This way you can get a nice and sharp picture of a moving subject in dark settings.

Commercial products already exist to fulfill this purpose.
Their price varies, but they will generally be in the $400 area, depending on your location.
Why spend that amount of money, when you can spend more on materials, time and failures to build one your own?

## Purpose

This writeup is meant for the reader to use as a reference, explanation or supporting document for our design.
Some of you may have other tools you can use that you might want to incorporate in your production process.
It's not unreasonable that at least a few of you have a lathe, CNC, laser cutter, et cetera.
These tools might provide you with better results than a 3D printer can, but you might have to redesign some part(s).
The writeup would then function as a reference to why we did what we did, for you to interpret and adapt to your own needs.

In this repository, we're exploring the design, and implementation details of a star tracker.
What considerations do we have to make, and how do we go about implementing it?
Answers to these questions will hopefully be answered when I have the time to work on this project.
External contributions are also very welcome, and even encouraged!
