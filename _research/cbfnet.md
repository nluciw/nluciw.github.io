---
title: "Automated generation of cerebral blood flow maps using deep learning and multiple delay arterial spin-labelled magnetic resonance imaging"
collection: research
permalink: /research/cbfnet
excerpt: 'The <b> objective </b> of this work was to improve the efficiency of synthesis of blood flow images from MRI
<br> <br>
<b>Tools</b>: Python (TensorFlow, seaborn, numpy, Pandas), frequentist statistics'
date: 2020-08-01
venue: 'Proc. Intl. Soc. Mag. Reson. Med.'
paperurl: 'https://index.mirasmart.com/ISMRM2020/PDFfiles/1289.html'
citation: 'NJ Luciw, Z Shirzadi, SE Black, M Goubran, BJ MacIntosh. (2020). &quot;Automated generation of cerebral blood flow maps using deep learning and multiple delay arterial spin-labelled magnetic resonance imaging.&quot; <i>Proc. Intl. Soc. Mag. Reson. Med.</i>. 28, 1289.'
thumb: /images/bestworst_imgs.001.jpeg
---

[Download extended conference abstract here](https://index.mirasmart.com/ISMRM2020/PDFfiles/1289.html)

<img src="/images/bestworst_imgs.001.jpeg" alt="drawing" width="700" class="center"/>

The <b> objective </b> of this work was to improve the efficiency of synthesis of blood flow images from a type of MRI known as multi-delay arterial spin labelling. This type of functional MRI is non-invasive and accurate, but is limited by cumbersome and slow post-processing required to generate clinically useful images.

I trained a <i> convolutional neural network </i> in Python 3.5 (Keras API of Tensorflow 2.2) to perform this image generation task much more quickly than the standard processing approach. In the linked abstract, my co-authors and I explore the model's performance across brain regions, as well as demonstrate <i> Monte Carlo dropout </i> to estimate model uncertainty and gain insight into model performance, even without the ground truth for comparison.  

I am particularly proud that the significance of this work has been reconized by diverse audiences including world experts and local high school students: 

 <b>Magna Cum Laude Merit Award</b> (top 10% of accepted abstracts), ISMRM expert reviewers. 
 
 <b> Best Poster Presentation, Runner-Up</b>, Sunnybrook Research Institute Brain Sciences Symposium (judged by local high school students).

<i>Recommended citation</i>: NJ Luciw, Z Shirzadi, SE Black, M Goubran, BJ MacIntosh. (2020). &quot;Automated generation of cerebral blood flow maps using deep learning and multiple delay arterial spin-labelled magnetic resonance imaging.&quot; <i>Proc. Intl. Soc. Mag. Reson. Med.</i>. 28, 1289.