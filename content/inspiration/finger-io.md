+++
title = "FingerIO"
description = "Using sonar for small screen interaction"
date = "2016-03-23"
publishdate = "2016-03-23"
+++

{{% fig "fingerio.jpg" %}}**Figure 1** Detecting finger motion using fingerIO.{{% /fig %}}

I recently came across [fingerIO](http://fingerio.cs.washington.edu/), a system
developed at the University of Washington that uses active sonar to track
finger motion. The research created prototypes using a standard Android
handset and a smart watch. The [accompanying
video](https://www.youtube.com/watch?v=PpVUCEZvNjI) shows a nice demonstration
of the kinds of interactions that can be performed with their system, but also
the delay in processing and seeming coarseness in detecting the finger
position. It's clearly a prototype to demonstrate a novel way to interact and
it's not clear if this will every be practical. Still, it's remarkable that they
were able to use only sound emitted from the speaker to detect finger position
and speed. This is yet another attempt to move the interaction off of the
displays. Things like tablets and smart phones have seen remarkable success
using direct manipulation, but as screens get smaller as with wearables, this is
becoming less practical. Fingers obscure large portions of the interface and
motion is restricted to a smaller area. FingerIO is clever, but their
implementation also makes it look clumsy and slow. The prototypes nicely
demonstrates early stage technical feasibility, but perhaps lack somewhat in
communicating how this approach is better than direct manipulation even on a
watch. I did appreciate how it clearly demonstrates the current capabilities.
How is this relevant for my project? With each prototype, what am I trying to
test and what questions do I want to answer? Also, who is my audience and what
am I trying to communicate? Finally, touch is not great for small display
interaction, but many alternatives are problematic as well.

