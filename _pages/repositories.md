---
layout: page
permalink: /repositories/
title: links of interest
description: General links of interest, my github profile, and some important repos.
nav: true
nav_order: 3
---

### Open Science resources
- [Open Science Framework](https://osf.io)
- [Open Microscopy Environment](https://www.openmicroscopy.org/omero/)
- [FAIR Data Principles](https://www.go-fair.org/fair-principles/)
- [BioImaging North America](https://www.bioimagingnorthamerica.org)

### My lab affiliations and general sleep and circadian questions you may have
- [Orie Shafer Lab](https://www.shaferlab.org)
- [Sheeba Vasu Lab](https://www.clockclub.org)
- [Sleep and Circadian FAQ](http://www-personal.umich.edu/~ojwalch/sleepfaq/)

### Tools to study what I study
- [_phaseR_](https://github.com/abhilashlakshman/phaseR) (The most recent version of my R-based software to analyse fly time-series and classify sleep stages in _Drosophila_)
- [Trikinetics](https://trikinetics.com) (The best way to record locomotor activity time-series in insects!)
- [RhythmicAlly](https://github.com/abhilashlakshman/RhythmicAlly) (R-based software to analyse biological timeseries)
- [PHASE](https://github.com/ajlopatkin/PHASE) (MATLAB-based software to analyse _Drosophila_ activity and sleep)

### Academic societies and science education
- [Society for Research on Biological Rhythms (SRBR)](https://srbr.org)
- [European Biological Rhythms Society (EBRS)](https://www.ebrs-online.org)
- [Resonance Journal of Science Education](https://www.ias.ac.in/Journals/Resonance_–_Journal_of_Science_Education/) (An incredibly interesting journal of science education brought to you by the [Indian Academy of Sciences](https://www.ias.ac.in))
- [Pueblo Brain Science](https://www.pueblobrainscience.org/home) (Learn about how an incredible team brings portable and accessible science to next-generation neuroscientists)

### Why the fly is awesome!!
- [Flybase](http://flybase.org)
- [Transgenic fly virtal lab](https://www.biointeractive.org/classroom-resources/transgenic-fly-virtual-lab)
- [The interactive fly](https://www.sdbonline.org/sites/fly/aimain/1aahome.htm)
- [Small fly, BIG Impact - Part 1](https://www.youtube.com/watch?v=qDbJnFLl3kU)
- [Small fly, BIG Impact - Part 2](https://www.youtube.com/watch?v=C9FSf6nhDSc)


------


### GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}


