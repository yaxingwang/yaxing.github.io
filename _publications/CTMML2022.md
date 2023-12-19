---
title: "Real image Inversion by learning classifier-free guidance in text-driven diffusion model"
collection: publications
permalink: /publication/CTMML2022
excerpt: ''
date: 2022-07-23
authors:
  - 'Boshi LI'
venue: 'Workshop on Continuous Time Methods in Machine Learning (CTMML) at the 39th International Conference on Machine Learning (ICML)'
paperurl: 'http://yaxingwang.github.io/files/2022_ctmml/paper.pdf'
rawciteurl: 'http://yaxingwang.github.io/files/2022_ctmml/citation.txt'
---

One appealing feature of diffusion models is their exceptional ability to generate diverse and high-quality images. Consequently, significant efforts have been invested in editing real images using these pretrained diffusion models. These efforts typically involve finetuning the pretrained model or inverting the image within the latent space of the frozen pretrained model. However, these methods encounter two challenges: (I) They demand users to provide a complete text prompt accurately describing every visual object in the input image. (II) They result in unsatisfactory outcomes for selected regions and unexpected changes in non-selected regions. To tackle these issues, we propose two enhancements for editing real images with a frozen pretrained diffusion model: (I) We invert the real image,
and learn a CFG w embedding. This facilitates learning more precise structure maps and an approximate trajectory for reconstructing the real image. Extensive experimental results on various images and prompt editing demonstrate, both qualitatively and quantitatively, that our method achieves more powerful editing capabilities compared to existing and current works.
