---
layout: page
title: Frog Feeding Biomechanics
description: How do frogs eat and swallow their prey?
img: /assets/img/6-21-22.jpg
importance: 1
category: Professional
---

Frog feeding mechanics has been a popular topic over the last few decades due to the amazing ballistic mechanism of the frog tongue and its potential biomimetic applications and evolutionary insights. As you can see in the video below, the frog tongue is attached in the front of the mouth and flips completely over before striking a prey item.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Picture1_cut.gif" title="Cane_toad_strike" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A slow-motion video of a cane toad catching a cricket with its tongue.
</div>

Most of the previous work done on this system has used high-speed light video like this to study movements of the tongue, but as a result many important movements have not yet been visualized, leaving many questions about frog feeding mechanics unresolved.

Questions such as: how do frogs swallow prey when it's attached to their sticky tongue? What role do the different parts of their anatomy play during swallowing?

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure_9.jpg" title="Cane_toad_feeding_anatomy" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An illustration showing some of the complex throat anatomy of a cane toad. Abbreviations: gh = m. geniohyoideus; ggm = m. genioglossus medials; hg = m. hyoglossus; oh = m. omohyoideus; pha = m. petrohyoideus anterior; php1 = m. petrohyoideus posterior primus; php3 = m. petrohyoideus tertius; sh = m. sternohyoideus.
</div>

To answer these questions, myself and my colleagues use an imaging technique called <a href="https://www.xromm.org/">XROMM</a> (X-ray reconstruction of moving morphology) to visualize the structures of interest throughout the feeding cycle. XROMM allows us to visualize elements which are normally externally hidden such as the <a href="https://journals.biologists.com/jeb/article/219/17/2650/15407/Pelvic-girdle-mobility-of-cryptodire-and">pelvic girdle of a turtle</a>, or the hyoid (the frog's version of an Adam's apple) and tongue of a frog during swallowing.

XROMM involves placing X-ray dense markers onto the structures of interest to track their movements.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure_1.jpg" title="Cane_toad_marker_positions" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A diagram of a frog skull in ventral and dorsal view, with our marker positions indicated in red. We have four markers on the skull, six in the lower jaw, two in the tongue, two in the hyoid, and a number on both halves of the pectoral girdle (the bones of the frog's chest), which in our study species is unfused at the midline.
</div>

We conducted <a href="https://academic.oup.com/iob/article/4/1/obac045/6769806">our most recent study</a> on cane toads, since they are notoriously voracious feeders. Once the markers were attached to our toads, we placed them in the XROMM setup and recorded them eating. We collected both high speed light and X-ray videos at 250 FPS for at least 50 strikes per toad. We digitized the videos in XMALab and MAYA and performed analyses in R. The results we found were remarkable!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/RM01_successful_strike.gif" title="Cane_toad_successful_strike" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A cane toad completing a successful feeding event. Motions of the skull, lower jaw, and pectoral girdle are indicated with pale yellow 3D mesh files produced via CT-scans of the toad. Motions of the XROMM markers are indicated with small spheres (not to scale), with markers associated with solid bone in pale yellow, the hyoid apparatus in purple, the tongue base in teal, and the tongue tip in gold. The lateral X-ray video (250 FPS) from which these motions were derived plays behind all animating objects. Animations were rendered in Maya (2022, Autodesk Inc., San Rafael, CA).
</div>

What might instantly catch your eye in this video is the gold marker embedded in the tongue tip - yes, it really is stretching behind the back of the skull after the frog closes its mouth! We measured the distances the tongue stretched during both tongue protrusion (when the tongue is moving forward) and tongue retraction (when the tongue is moving backward), and found that, on average, the tongue stretches more during retraction than during protrusion. We believe that
The tongue tip hits the closed glottis, which is the opening of the windpipe, every time regardless of how far out the tongue goes during protrusion. The tongue consistently stretches behind the back of the skull during swallowing, which amazingly rivals the distance it stretches during prey capture!


The results suggest the hyoid apparatus plays an important role in prey transport, that the tongue travels consistently behind the back of the skull during swallowing, and that tongue protrusion comprises only a small portion of a full feeding cycle. This work raises new questions about the evolution of feeding in frogs, as well as how the diversity of pectoral and buccal anatomy observed across anurans may influence feeding kinematics.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


Please be sure to check out the open access article here to read more about the details of the project. There are also been some wonderful news coverage of the paper as well. And be sure to keep an eye out for future work on this topic from us!

Collaborators:
