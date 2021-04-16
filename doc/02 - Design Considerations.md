# Design considerations

The design of the star tracker needs to fulfill a number of prerequesites.
Mainly, it needs to be portable, accurate and in our case, reasonably simple to build.
As we expect that the main manufacturing method of our users is the use of 3D printers, we need to make sure that our designs do not incorporate too many fine details, or too much non-standard hardware if we need to incorporate nuts and bolt, for example.

Additionally, electronic components ought to be easily attainable.
While we'd like to design our own PCBs for our needs, it's probably more likely that Aruino or Raspberry Pi based systems are preferred due to their ubiquity, good support and widely available documentation.
Fancy solutions are nice, but simple solutions are better.
Nevertheless, if we can properly define our PCB specifications and requiremetns we can also design multiple implementations of the board based around a variety of microcontrollers.

## Existing products

If we consider existing star trackers, they share several similarities:

- They can be powered with batteries and with an external power source
- They are mountable on a tripod
- They allow the user to select several speeds
- Mounted cameras are easily aimed at the desired target
- Polar allignment methods are built into the device, or are easily attached
- Some have a go-to function at the cost of size

Taking these features into account, we'd like to distill them down into a so-called Minimum Viable Product (MVP).
This is generally regarded as the minimum amount of working features required to release.
For a star tracker, this is somewhat simple.
We want to turn a mounted camera such that it counteracts the rotation of the earth.
If we can achieve that, we can call it ready for release.

As this is an open source project, "release", of course, means "functional"
