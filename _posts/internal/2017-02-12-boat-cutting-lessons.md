---
title: Lessons from laser cutting boats
layout: gdoc
permalink: /internal/boat-cutting-lessons
project: internal
source-id: 1LlZYrUV8e5jM3_iUAHsdiuV-qE9m4gNQhPI64Zmtfyk
published: true
---
On Saturday, February 11, I was involved with an effort by the QEA NINJA team to laser cut 18 boats for the students in the class. We had four hours to accomplish this, and ultimately used just under three.

# What we did

1. By Friday night, we asked all of the student teams to submit their designs. We asked for...

    1. A PDF file for each sheet they wanted cut

    2. A zip file of all of the sources associated with each sheet using Solidworks' "pack and go" feature

    3. An image of their final assembly

    4. The sources associated with that assembly

2. On Saturday morning, I went through all of the submissions and assigned them a "grade" based on their readiness. I checked for...

    5. Did they have all of the files we asked for?

    6. Were there any construction lines or centerlines visible that would be cut by the laser?

    7. Did their design fit within the margins we specified?

    8. Was there anything else obviously wrong with their submission?

3. About half the teams passed that initial check, the rest mostly managed to fix their drawings before we started cutting at 1:00

4. From 1:00-5:00 we cut the boats. We had two lasers running simultaneously, and tracked the progress in a Google Sheet.

5. Late that night, we realized we had forgotten one boat, and needed to go back and cut it.

# What worked well

1. Asking for a PDF submission was good

    1. We could rapidly preview a boat design to see if it looked right

    2. We can cut directly from the PDF in most cases.

2. Cutting directly from a PDF was good

    3. It saves time, there is no need to load all of the dependent files from the zip

    4. Moving things around in a PDF is pretty easy with Illustrator or Inkscape, even between multiple files

    5. The preparation and printing can be done asynchronously, even when you don't know what machine you are preparing for

        1. Make sure you set line thickness to 0.001", 0.002” is too thinck for the Helix

3. Asking for source submission was good

    6. In some cases, especially when people didn't fix their designs, we could repair them ourselves with not too much effort in Solidworks.

    7. It allowed us to verify questionable things (like when somebody exported their drawing at 50% scale)

    8. Because our top priority was getting everything cut, we were willing to do that in-depth analysis in the few cases that needed it.

4. Having a sheet to track progress (status? Which machine?) 

5. Using post-its to track each cut as it is ongoing and once it is done 

# Things to do differently next time

1. Create the tracking sheet before entering the shop, and check carefully that it has everything on it. Leave placeholder rows for things that may come in.

2. In the tracking sheet, mark files that may require additional preparation so that work can be done whenever there is free time.

3. Make sure we get an email if someone changes something from the time we download things until when we're done cutting. It didn’t bite us this time, but could in the future.

4. Have an orthoganal mechanism to track how much is done and what needs to be done. Something as simple as counting finished boats would have prevented the need to do late night cutting.

5. Set up your laptop somewhere you can see and actively monitor the lasers.

6. Use all three machines, one was broken, which wasn't ideal.

7. Have a shared "staging" folder (probably in Sandbox) for all of the preprocessed PDFs. That way multiple people can print without issue.

