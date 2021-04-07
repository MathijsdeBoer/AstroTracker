# Introduction

The Stars!

The stars?

Yes! The stars! And those other stellar objects, too, I guess.

What about them?

Have you never wanted to take a photo of them?

Well sure, but my (phone) camera is not good enough to get nice results I can share on my [insert social media] page. Even the moon can be tricky!

A-ha! But it does not have to be that hard, you just need to know how to use your equipment to get the results you want!

But how?

Don't worry, people have been taking stellar pictures with cheap hardware for _years_, if they can get their amazing results, your modern smartphone can do it for sure.

## Stellar photography

Depicting the stars is an art as [old as time](https://en.wikipedia.org/wiki/History_of_astronomy). It should therefore not be surprising that, not long after it was invented, this was also extended to photography. While the initial [Daguerrotype](https://en.wikipedia.org/wiki/Daguerreotype) style photographs were only usable for bright objects, it wasn't too long after that new developments in photography allowed for more sensitivity to the dimmer objects. For reference, the first successful Daguerrotype image of the sun's corona in 1851 took an 84 seconds exposure!

<img src="https://upload.wikimedia.org/wikipedia/commons/3/38/1851_07_28_Berkowski.jpg" width=400 alt="Daguerrotype of the sun, Johann Julius Friedrich Berkowski, 1851">

Johann Julius Friedrich Berkowski, 1851

It wasn't untill the widespread availability of [dry plate photography](https://en.wikipedia.org/wiki/Dry_plate) that astrophotography became a more manageable process. Henry Draper, for example, used a 51 minute exposure in 1880 to be the first person to capture the Orion Nebula. Where his colleague, Andrew Ainslie Common, built his own telescope in his shed and used several hour-long exposures of the same nebula to show stars that the human eye can not see three years later.

<img src="https://upload.wikimedia.org/wikipedia/en/f/fe/Henry_Drape_Orion_nebula_1880_inverted.jpg" width=400 alt="Orion Nebula, Henry Draper, 1880">

Henry Draper, 1880

<img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Orion-Nebula_A_A_Common.jpg" height=300 alt="Orion Nebula, Andrew Ainslie Common, 1883">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/04/18_inch_newtonian_telescope_back_yard_Ealing_London_Andrew_Ainslie_Common.png" height=300 alt="The telescope used by Andrew Ainslie Common, built into his shed, built in 1876, unknown date">

Left: Andrew Ainslie Common, 1883, right: The telescope built by him

If people that built their own telescopes in their backyards, with the technology of the day that fights against them in almost any conceivable way, can take the types of pictures shown above, we sure as hell can do it with the seas of information that can be found on the internet! Right?

Source(s): Wikipedia

## So what do _I_ need?

A camera.

Joking aside, you don't need a good camera. Amateur astrophotographers have been using old webcams for about as long as they have been available. More recently, Raspberry Pis have had some level of use, too. That is not to say that a phone does not work. At the other end of the scales you have your DSLR/Mirrorless cameras, and dedicated astrocameras. These may be out of the price range of many people though. It's worth mentioning that entry level DSLRs tend to be in the $300 bracket, and are usable for things other than pretty star pictures.

The main issue that most budding astrophotographers face is that they simply don't have a stable enough platform to take their pictures with. While you can freehand a DSLR to take photos of the moon, getting Andromeda may not be as simple. A good tripod or other stable mount may be needed. Because these other objects are so dim, you need to increase the amount of time your camera takes to take a picture. That, or you find a lens with a insanely large aperture, probably at an equally insane price.

But my pictures are still blurry!

Yes, well, while the camera may be perfectly still, the earth isn't. You may have missed it, but once every 24 hours or so, we do a full rotation! This has the effect of the illusion that the sky is moving around us. Whether we are moving, or the sky is has little bearing on the result: The stars start streaking.

<img src="https://upload.wikimedia.org/wikipedia/commons/6/6c/%E6%98%9F%E3%81%AE%E8%BB%8C%E8%B7%A1%E5%8D%81%E6%B4%A5%E5%B7%9D%E3%83%BB%E4%B8%8A%E6%B9%AF%E3%81%AB%E3%81%A6Img042.jpg" width=400 alt="Star trails, Akiyoshi's Room">

Star trails, Akiyoshi's Room, unknown date

While this has its artistic merit, it might not be what you want. There's two main ways to solve this. We can decrease exposure time, reducing the amount of light per photo. This has the issue that you need to take a lot more photos to gather the same amount of light. Stacking is used to combine these images after the fact. Alternatively we find a way to keep the camera pointed at the same point in the sky. Enter: The astrotracker!

In this repository, we're exploring the design, and implementation details of such a device. What considerations do we have to make, and how do we go about implementing it? Answers to these questions will hopefully be answered when I have the time to work on this project. External contributions are also very welcome, and even encouraged!
