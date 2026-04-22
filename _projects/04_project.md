---
layout: page
title: phaseR
description: New and improved analysis application. Use this to study sleep states in flies, and much more!
img: assets/img/sleepStages_schematic.jpg
importance: 1
category: tools
---

phaseR is a new Shiny application that I've built with an easy-to-navigate GUI. It has all the amazing things [RhythmicAlly](https://journals.sagepub.com/doi/full/10.1177/0748730419862474) and [PHASE](https://journals.sagepub.com/doi/abs/10.1177/07487304221093114) can do, but in one place.

Its intended design is to be a one-stop shop for all rhythm visualizing and analyzing needs for _Drosophila_ data sets.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/phaseR1.png" title="Scalograms" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/phaseR2.png" title="Bout distribution" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/phaseR3.png" title="Hypnograms" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In addition, phaseR does some new analyses that no other software is designed to provide. It can help users transform long-term activity records in flies (using the [DAM system](https://trikinetics.com)) into discrete sleep states, analyse sleep bout distrubutions, perform wavelet transforms on time-series data, and extract ultradian rhythm parameters in long records of fly time-series. The user interface function exactly like [RhythmicAlly](https://journals.sagepub.com/doi/full/10.1177/0748730419862474). For the user's convenience, phaseR also allows batch processing of data. Stay tuned for a detailed user manual..
