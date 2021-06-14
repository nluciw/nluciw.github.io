---
title: "A deep learning approach to estimate voxelwise cardiac-related brain pulsatility from BOLD MRI"
collection: research
permalink: /research/cbfnet
excerpt: 'The <b> objective </b> of this work was to estimate the signature of cardiac pulsations in functional brain MRI without use of a separately recorded cardiac trace for reference. 
<br> <br>
The <b> technical challenge </b> of this work was to develop a processing pipeline suitable for complex 4D data aimed to extract a signal whose characteristic frequency is faster than our sampling rate.
<br> <br>
<b>Tools</b>: Python (PyTorch, seaborn, numpy, Pandas)'
date: 2021-05-20
venue: 'Proc. Intl. Soc. Mag. Reson. Med.'
paperurl: 'https://index.mirasmart.com/ISMRM2021/PDFfiles/0659.html'
citation: 'Luciw N.J., Cameron W., Robertson A., Atwi S., MacIntosh B.J. (2021) A deep learning approach to estimate voxelwise cardiac-related brain pulsatility from BOLD MRI. Proceedings of the 29th annual meeting of Intl. Soc. Mag. Reson. Med.'
thumb: /images/pulsemap_Fig1.pdf
---

[Download pre-print article abstract here](https://index.mirasmart.com/ISMRM2021/PDFfiles/0659.html)

<img src="/images/pulsemap_Fig1.pdf" alt="drawing" width="700" class="center"/>

The <b> objective </b> of this work was to estimate the brain signature of cardiac pulsations in functional brain MRI. This usually requires a separately recorded cardiac trace, which is often not acquired in the clinic or by the researcher. Our approach does not require this separate recording, and instead uses deep learning to accurately estimate cardiac-related brain pulsatility.

The <b> technical challenge </b> of this work was to develop a processing pipeline suitable for complex 4D data aimed to extract a signal whose characteristic frequency is faster than our sampling rate.

I trained a <i> convolutional neural network </i> in Python 3.5 (PyTorch) to perform this image synthesis task. We used the pre-trained ResNet 34 architecture as the encoder arm of a UNet architecture.

I am particularly proud that this work was recognized by international colleagues: 

<b>Summa Cum Laude Merit Award</b> (top 5% of accepted abstracts), ISMRM expert reviewers. 

<i>Recommended citation</i>: Luciw N.J., Cameron W., Robertson A., Atwi S., MacIntosh B.J. (2021) A deep learning approach to estimate voxelwise cardiac-related brain pulsatility from BOLD MRI. Proceedings of the 29th annual meeting of Intl. Soc. Mag. Reson. Med.