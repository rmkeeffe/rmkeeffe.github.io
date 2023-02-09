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

What might instantly catch your eye in this video is the gold marker embedded in the tongue tip - yes, it really is stretching behind the back of the skull after the frog closes its mouth! We measured the distances the tongue stretched during both tongue protrusion (when the tongue is moving forward) and tongue retraction (when the tongue is moving backward), and found that, on average, the tongue stretches more during retraction than during protrusion.

You may also notice the two purple markers moving a lot following mouth closure. These are tracking the moments of the front part of the hyoid apparatus, which is a thin, bendable structure made of cartilage. Several muscles of the tongue are connected to the hyoid, which moves far backward and downward to facilitate the amazing backward stretching of the tongue. It also moves quickly upward following maximum tongue retraction, which may be helping to 'scrape' the prey off of the sticky tongue and into the esophagus.

This is a complicated process, which can be illustrated more clearly in this figure from our paper.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure_8.jpg" title="Cane_toad_swallowing_diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An illustration of the major events that encompass a full feeding event for a cane toad. Upper panels are ventral views and lower panels are the same event in lateral view. Percentages listed between the upper and lower panels indicate at what % through a feeding cycle that frame occurs, followed by a brief description of the event in parentheses. The horizontal black lines of all dorsal view panels indicate the initial positions of the hyoid markers and those of all lateral view panels indicate the initial margins of the skull and pectoral girdle. Color designations are as follows: gray = bones of the skull, lower jaw, and pectoral girdle; light gray = posteromedial bones of the hyoid apparatus; blue = the cartilaginous hyoid apparatus; yellow = arytenoid cartilages of the glottis; pink = the protrusible part of the tongue; dark red = the heart; tan = the stomach and buccal cavity; red = tantalum XROMM markers; brown = the prey item. Silhouette of the toad is indicated by a gray transparency.
</div>

The results of this work suggest the hyoid apparatus plays an important role in prey transport, that the tongue travels consistently behind the back of the skull during swallowing, and that tongue protrusion comprises only a small portion of a full feeding cycle. This work raises new questions about the evolution of feeding in frogs, as well as how the diversity of pectoral and buccal anatomy observed across anurans may influence feeding kinematics.

For example, many frogs have structures on the roof of the mouth such as vomerine teeth or pharyngeal folds that have unknown functional significance. Are these involved in the hyoid scrape mechanism we observed in cane toads? What about frogs with hyoids of different shapes? We are excited for future steps of this project, such as examining the biomechanics of swallowing in other frog species with different morphologies and examining the role of the hyoid in other behaviors such as breathing and vocalizing.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure_2.jpg" title="Frog_hyoid_diversity_diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An illustration of various anuran hyoid morphologies in ventral view, cartilaginous regions are blue and the posteromedial and parahyoid bones are light gray. Species depicted are as follows: (A) R. marina, (B) Hyla annectans, (C) Hemisus marmoratus, (D) Heterixalus madagascariensis, (E) Pipa pipa, and (F) Rhinophrynus dorsalis. Abbreviations: al = alary process; ap = anterior process; h = hyale; hp = hyoid plate; hs = hyoglossal sinus; plp = posterolateral process; pm = posteromedial process. A–D adapted from Trewavas 1932; E from Ridewood 1897; and F from Duellman and Trueb 1986. The asymmetry of R.marina is not typical for the species.
</div>

Please be sure to check out the open access article <a href="https://academic.oup.com/iob/article/4/1/obac045/6769806">here</a> to read more about the details of the project. There are also been <a href="https://www.floridamuseum.ufl.edu/science/a-hard-pillbug-to-swallow/">some wonderful</a> <a href="https://www.newscientist.com/article/2345616-cane-toads-fling-their-tongues-so-hard-the-recoil-slaps-their-heart/">news coverage</a> of the paper as well. And be sure to keep an eye out for future work on this topic from us!

Co-authors:
<a href="https://directory.nau.edu/departments?id=10211&person=cjm964&src=biological-sciences">Christopher J. Mayerl</a> |
<a href="https://www.floridamuseum.ufl.edu/blackburn-lab/personnel/principal-investigator/">David C. Blackburn</a> | 
<a href="https://www.clemson.edu/science/academics/departments/biosci/about/profiles/rblob">Richard Blob</a>

Funding: This work was supported by the National Science Foundation Graduate Research Fellowship [grant numbers DGE-1315138, DGE-1842473] to RK, the Brian Riewald Memorial Fund Research Grant to RK, and the Zirpolo Fund of Northeast Ohio Medical University.

Acknowledgements: We greatly appreciate the German Lab, Rebecca German, Kendall Steer, Chloe Edmonds, and Max Johnson for their assistance during data collection. We thank Gator City Reptiles (Gainesville, FL) for their help supplying the animals for this project and providing husbandry advice. We thank Edward Stanley and Jaimi Gray for assistance and advice regarding CT and diceCT procedures. We also thank Rob Robins, Mary Brown, and Autumn Brown for helping collect toads for dissection assays, and also Coleman M. Sheehy III for his help with accessioning and dissecting specimens. We also extend our thanks to Patricia Brennan for her help with the Spanish translation of the abstract. We had several fruitful discussions on hyoid and jaw mechanics with Katherine Bemis and Alan Richmond for which we are grateful.
