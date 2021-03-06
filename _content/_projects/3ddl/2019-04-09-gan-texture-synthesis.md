---
layout: project_page
team: 3ddl
categories: 3ddl
front_id: 1

title: User-Controllable Multi-Texture Synthesis with Generative Adversarial Networks
authors:
  - name: Aibek Alanov
    affiliation: '1,2,3,∗'
  - name: Max Kochurov
    affiliation: '1,2,∗'
  - name: Denis Volkhonskiy
    affiliation: 2
  - name: Daniil Yashkov
    affiliation: 5
  - name: Evgeny Burnaev
    affiliation: 2
  - name: Dmitry Vetrov
    affiliation: '1,4'
affiliation:
  - Samsung AI Center Moscow
  - Skolkovo Institute of Science and Technology
  - National Research University Higher School of Economics
  - Samsung-HSE Laboratory, National Research University Higher School of Economics
  - Federal Research Center ”Computer Science and Control” of the Russian Academy of Sciences
venue: arXiv 2019

excerpt: We propose a novel multi-texture synthesis model based on generative adversarial networks (GANs) with a user-controllable mechanism. The user control ability allows us to explicitly specify the texture which should be generated by the model. This property follows from using an encoder part which learns a latent representation for each texture from the dataset.
abstract: We propose a novel multi-texture synthesis model based on generative adversarial networks (GANs) with a user-controllable mechanism. The user control ability allows to explicitly specify the texture which should be generated by the model. This property follows from using an encoder part which learns a latent representation for each texture from the dataset. To ensure a dataset coverage, we use an adversarial loss function that penalizes for incorrect reproductions of a given texture. In experiments, we show that our model can learn descriptive texture manifolds for large data sets and from raw data such as a collection of high-resolution photos. Moreover, we apply our method to produce 3D textures and show that it outperforms existing baselines.

thumbnail: /assets/img/projects/gan_texture_synth/thumbnail.jpg
visual_abstract: /assets/img/projects/gan_texture_synth/teaser-pic.jpg
visual_abstract_description: 'One can take 1) New Guinea 3264 × 4928 landscape photo, learn 2) a manifold of 2D texture embeddings for this photo, visualize 3) texture map for the image and perform 4) texture detection for a patch using distances between learned embeddings'
#bibtex: '<span style="background-color: #F00;color: #FFF">Somebody fill this with bibtex when it is published'

materials:
    - name: Paper
      url: https://arxiv.org/pdf/1904.04751.pdf
      icon: fa fa-file-pdf-o
---
