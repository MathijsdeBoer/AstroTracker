# 10k : 1 Planetary Gearbox

## Iteration 1

## Design Decisions

This is an initial design for the gearbox that should bring down our stepper motor's rotation to our targeted 10k : 1 reduction.
It was designed with 3D printing in mind, and as such already has some tolerances built in.
The reduction stages are selected as defined in our writeup:

    4 * 4 * 5 * 5 * 5 * 5 = 10,000

Where the `: 1` is left out for clarity.

A module of 2.0 mm for the gears was chosen as a good compromise between size and gear strength.
As we should expect users to attach some expensive equipment to the end, we should probably err on the side of caution, lest the $5000 camera drops on the floor after the teeth shear off.

The current implementation does not, however, use the helical or herringbone (double helical) cut.
Firstly, the used tool to generate the gears has a bug where the module changes as the helical angle increases, which made designing for size more difficult.
Secondly, as the application is not a high-RPM one, the helical cut may not be required after all.

Gear thickness was left at the default 10mm.
Some room for optimization may be found here, though care should be taken to not remove too much as to not reduce gear strength too much.

In terms of planetary gear setups, we've opted to fit as many as physically would fit per stage.
This works out to 5 planetary gears for the 4 : 1 stages, and 4 for the 5 : 1 stages.
This could be reduced to 3
However, we've again erred on the side of caution and opted to distribute any forces through as many gears as we could fit.

The carriers and planetary gears were designed to be fitted with 608 sized ball bearings.
This size of bearing is relatively ubiquitous and should be comparatively cheap.
These should keep things moving quite smoothly, though no tests on designs without bearings have been performed.
Removal of these bearings in favour of a simpler rod and hole setup might also allow us to reduce the thickness of the carriers, reducing overal size.

Finally, we added a little galaxy design to the gears, because it looks neat while reducing a little bit of material.
