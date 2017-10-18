---
layout: page
title: Intrinsic3D
subtitle: 
show-avatar: false
social-share: true
share-img: https://robmaier.github.io/img/maier2017intrinsic3d.jpg
published: true
---

Intrinsic3D: High-Quality 3D Reconstruction by Joint Appearance and Geometry Optimization with Spatially-Varying Lighting
<br>
Robert Maier, Kihwan Kim, Daniel Cremers, Jan Kautz, Matthias Nießner
<br>

![Intrinsic3D]({{site.baseurl}}/img/maier2017intrinsic3d.jpg){: .center-image }
<br>

### Abstract
<div style="text-align: justify">
We introduce a novel method to obtain high-quality 3D reconstructions from consumer RGB-D sensors. Our core idea is to simultaneously optimize for geometry encoded in a signed distance field (SDF), textures from automatically-selected keyframes, and their camera poses along with material and scene lighting. To this end, we propose a joint surface reconstruction approach that is based on Shape-from-Shading (SfS) techniques and utilizes the estimation of spatially-varying spherical harmonics (SVSH) from subvolumes of the reconstructed scene. Through extensive examples and evaluations, we demonstrate that our method dramatically increases the level of detail in the reconstructed scene geometry and contributes highly to consistent surface texture recovery.
</div>

<div style="text-align: center">
<a href="http://www.rmaier.net/pub/maier2017intrinsic3d.pdf" target="_blank">
<button class="button buttonpaper"> pdf </button>
</a>
<a href="http://www.rmaier.net/pub/maier2017intrinsic3d_slides.pdf" target="_blank">
<button class="button buttonpaper"> slides </button>
</a>
<a href="http://www.rmaier.net/pub/maier2017intrinsic3d_poster.pdf" target="_blank">
<button class="button buttonpaper"> poster </button>
</a>
<a href="http://www.rmaier.net/pub/maier2017intrinsic3d.bib" target="_blank">
<button class="button buttonpaper"> bibtex </button>
</a>
</div>

### Bibtex
```
@inproceedings{maier2017intrinsic3d,
	title={Intrinsic3D: High-Quality {3D} Reconstruction by Joint Appearance and Geometry Optimization with Spatially-Varying Lighting},
	author={Maier, R. and Kim, K. and Cremers, D. and Kautz, J. and Nie{\ss}ner, M.},
	booktitle={International Conference on Computer Vision (ICCV)},
	year={2017},
	month={October},
	address={Venice, Italy}
}
```

### Share on
{% include social-share.html %}
