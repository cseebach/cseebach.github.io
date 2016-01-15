---
title:  Ocean Temperature - Overview and Hull Design
subtitle: Looks Easy but Really Isn't
author: "Cam"
avatar: "img/authors/cam.png"
image: "img/hull-tinkercad.jpg"
date:   2015-01-15 14:00:00
---

### You seem a little nuts.

Yes. I'm taking a Geology class right now that focuses on the oceans, and was
asked to do a term project, made up of an 8-page paper and a 10-minute
presentation.

Because I don't generally do things the easy way, I decided I'd build and
program an instrument for oceanography rather than passively read about the
cool science we were studying. I discovered that the parts for temperature
sensing were pretty cheap, and so I went for it.

What you're reading now is my journey to building a submersible ocean
temperature measurement device for use in undergraduate ocean research.

### We can already take ocean temperature, buddy.

You're absolutely correct, and there is a great deal of existing instrumentation
for sensing temperature, on the surface and underwater. However, there are three
big issues.

  * Those instruments are generally expensive. A complete setup costs between
  $400 and $1000 dollars just to measure temperature underwater.
  * In that price range, instruments don't have very large memories. 64K might
  seem like plenty, but when you consider that you might leave an instrument
  for weeks at a time, sampling once per second...
  * They're not user programmable. If you need to modify the way the sensor
  works, you're out of luck.

I will do things differently.

  * My sensor will cost approximately $200.
  * My sensor will have memory measured in gigabytes, not kilobytes.
  * The software that runs my sensor will be open-source, forever.

And I've even got some stretch goals that could be game-changing if I achieve
them.

  * Measuring water salinity can be done electromagnetically, and may be within
  my electronics ability.
  * Measuring wave action with an accelerometer wouldn't be too hard.

And some super-stretch goals, like measuring dissolved oxygen and pH.

### Okay, you're definitely nuts. Please continue.

The first hard thing will be making a watertight container for my electronics,
and I've put a decent amount of thought into this already.

I can 3D print a spherical hull, and put the electronics safely inside. In an
ideal world, I could seal the hull using an O-ring and some latches or
threading. If the hull is cheap to produce, I may decide to just seal the thing
with marine epoxy instead and make a new hull for each deployment.

I may also need to cover the hull with an enamel of some kind to prevent water
getting in through the microscopic holes that a 3d printer may sometimes leave.

Here's a picture of the hull mocked up in TinkerCAD.

![Hull in TinkerCAD](/img/hull-tinkercad.jpg "Hull in TinkerCAD")

Those wide slots are for the electronics and the battery, and they will probably
change size and shape as I'm evaluating different development boards for
this project.

That's all for now. Stay tuned while I learn how to use a 3D printer!
