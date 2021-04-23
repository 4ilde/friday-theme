---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Friday Theme
---

## abstract


We present a multimodal dataset for the analysis of human affective states. The electroencephalogram (EEG) and peripheral physiological signals of 32 participants were recorded as each watched 40 one-minute long excerpts of music videos. Participants rated each video in terms of the levels of arousal, valence, like/dislike, dominance and familiarity. For 22 of the 32 participants, frontal face video was also recorded. A novel method for stimuli selection was used, utilising retrieval by affective tags from the last.fm website, video highlight detection and an online assessment tool.

The dataset is made publicly available and we encourage other researchers to use it for testing their own affective state estimation methods. The dataset was first presented in the following paper:[DEAP: A Database for Emotion Analysis using Physiological Signals (PDF)](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/doc/tac_special_issue_2011.pdf) S. Koelstra, C. Muehl, M. Soleymani, J.-S. Lee, A. Yazdani, T. Ebrahimi, T. Pun, A. Nijholt, I. Patras, EEE Transactions on Affective Computing, vol. 3, no. 1, pp. 18-31, 2012

## how to use

This web site is the documentation for the theme and also provides examples of how you can use and modify it. TIt is built using Friday Theme directly from the [GitHub repo](https://github.com/sfreytag/friday-theme) and published to GitHub pages.

[The documentation]({{ site.baseurl }}{% link list/projects.md %}) covers the basics of installing and using it, and is an example of how you could write documentation about your own projects.

[The blog]({{ site.baseurl }}{% link list/posts.html %}) has a bunch of tips about how to use Friday Theme. These show how the blog works, including the tags. There's the three most-recent posts below included below.

<hr />

### credits

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


