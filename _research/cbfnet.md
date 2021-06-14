---
title: "Automated Generation of Cerebral Blood Flow Maps Using Deep Learning and Multiple Delay Arterial Spin-Labelled MRI"
collection: research
permalink: /research/cbfnet
excerpt: 'The <b> objective </b> of this work was to improve the efficiency of synthesis of blood flow images from MRI.
<br> <br>
The <b> technical challenge </b> of this work was to develop a processing pipeline suitable for clinical use: fast, accurate, generalizable, and with uncertainty estimates.
<br> <br>
<b>Tools</b>: Python (TensorFlow, seaborn, numpy, Pandas)'
date: 2021-06-06
venue: 'Proc. Intl. Soc. Mag. Reson. Med.'
paperurl: 'https://www.biorxiv.org/content/10.1101/2021.06.04.446768v1.abstract'
citation: 'Luciw N. J., Shirzadi Z., Black S. E., Goubran M., MacIntosh B. J. (2021) Automated Generation of Cerebral Blood Flow Maps Using Deep Learning and Multiple Delay Arterial Spin-Labelled MRI. bioRxiv 2021.06.04.446768; doi: https://doi.org/10.1101/2021.06.04.446768'
thumb: /images/cbfnet_Fig1.pdf
---

[Download pre-print article here](https://www.biorxiv.org/content/10.1101/2021.06.04.446768v1.abstract)

<img src="/images/cbfnet_Fig1.pdf" alt="drawing" width="700" class="center"/>

The <b> objective </b> of this work was to improve the efficiency of synthesis of blood flow images from a type of MRI known as multi-delay arterial spin labelling. This type of functional MRI is non-invasive and accurate, but is limited by cumbersome and slow post-processing required to generate clinically useful images.

The <b> technical challenge </b> of this work was to develop a processing pipeline suitable for clinical use: fast, accurate, generalizable, and with uncertainty estimates.

I trained a <i> convolutional neural network </i> in Python 3.5 (Keras API of Tensorflow 2.2) to perform this image generation task much more quickly than the standard processing approach. In the linked paper, my co-authors and I explore the model's performance across brain regions, as well as demonstrate <i> Monte Carlo dropout </i> to estimate model uncertainty and gain insight into model performance, even without the ground truth for comparison.  

I am particularly proud that the significance of this work has been reconized by diverse audiences including world experts and local high school students: 

 <b>Magna Cum Laude Merit Award</b> (top 15% of accepted abstracts), ISMRM expert reviewers. 
 
 <b> Best Poster Presentation, Runner-Up</b>, Sunnybrook Research Institute Brain Sciences Symposium (judged by local high school students).

<i>Recommended citation</i>: Luciw N. J., Shirzadi Z., Black S. E., Goubran M., MacIntosh B. J. (2021) Automated Generation of Cerebral Blood Flow Maps Using Deep Learning and Multiple Delay Arterial Spin-Labelled MRI. bioRxiv 2021.06.04.446768; doi: https://doi.org/10.1101/2021.06.04.446768