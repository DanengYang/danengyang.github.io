---
permalink: /
title: "Daneng Yang's academic personal websites"
excerpt: "Postdoc in Physics at UCR"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Research interests
======
My recent research mainly focuses on understanding cosmic dark matter distribution. Dark matter comprises 80\% of the matter contents of the universe. Its evolution since the origin of the universe is a complicated non-linear process that has been modeled using cosmological simulations on supercomputers. Despite decades of research, its properties remain a mystery, including its mass and interactions beyond gravity. Aside from that, I have broad interests in cosmology and collider physics. Some of my previous works are related to the nature of symmetry breaking in the standard model of particle physics. 

Parametric and graph models
------
I put my efforts into searching for simple rules under complex data. In works with Prof. Hai-Bo Yu (UCR). I conducted N-body simulations to investigate the reason a fluid model can be used to describe the evolution of self-interacting dark matter (SIDM) halos. I proposed a way to reduce a generic elastic scattering cross section into a constant one in a specific halo. Making use of the reduction formula as well as the universal behavior of gravothermal evolution, I further proposed a parametric model to enable modeling a population of cosmic SIDM halos based on a few analytic equations. 

In another recent work with Prof. Yu, I realized that the distribution of dark matter halos has hidden topological structures that can be encoded using networks. I proposed a simple random graph model to generate these properties. This study provides a new angle of looking at the clustering of dark matter and is related to recent applications of graph neural networks in probing features of dark matter halos.

The nature of self-interacting dark matter
------
My research focuses on detecting SIDM effects through observations. With Prof. Yu, and Prof. Haipeng An (THU), we demonstrated in a PRL paper (Editor's suggestion) that SIDM could enhance the tidal stripping of core-forming halos, which can facilitate the formation of galaxies that lack dark matter. With Prof. Yu, we examined strong lensing features in light of an observational excess of small-scale lenses and highlighted the differences between SIDM and cold dark matter (CDM) scenarios. Recently, I collaborated with Dr. Nadler and Prof. Yu to perform high-resolution cosmological simulations and demonstrated promising features of some strong velocity-dependent SIDM models in reproducing observational features. I continue to employ a combination of high-precision N-body simulations and analytic/semi-analytic models to uncover clues of SIDM in observations.

Gauge boson searches
------
In a different direction, I worked with Prof. Qiang Li (PKU) and other collaborators on multiple collider experiments and phenomenology projects about multi-gauge-boson production and gauge boson self-interactions. I led the first measurement of W-gamma vector boson scattering analysis in the CMS experiment at the CERN Large Hadron Collider and actively participated in the first triboson production analysis at the LHC. I also contributed to some other experimental and phenomenological studies with published papers.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).


More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
