---
title: "Towards Playing a 3D First-Person Shooter Game Using a Classification Deep Neural Network Architecture"
subtitle: "19th Symposium on Virtual and Augmented Reality (SVR)"
thumbnail: /assets/images/mnist_vizdoom.jpg
header:
    teaser: /assets/images/mnist_vizdoom.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - ViZDoom
  - SVR
---

*19th Symposium on Virtual and Augmented Reality (SVR)*  

[Paulo Bruno de Sousa Serafim](https://paulobruno.github.io)
  [Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)  
[Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)
  [Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)

<p style="font-size:0.7em">
    Department of Computing (DC), Federal University of Ceara (UFC)
</p>

![Mnist problem and ViZDoom's Scenarios](/assets/images/mnist_vizdoom.jpg)

---

Paper: [[PDF](https://www.researchgate.net/profile/Creto_Vidal/publication/321174607_Towards_Playing_a_3D_First-Person_Shooter_Game_Using_a_Classification_Deep_Neural_Network_Architecture/links/5d8b59e6299bf10cff0b80e1/Towards-Playing-a-3D-First-Person-Shooter-Game-Using-a-Classification-Deep-Neural-Network-Architecture.pdf)]
 Page: [[IEEE](https://ieeexplore.ieee.org/document/8114428)]
 Code: [[GitHub](https://github.com/paulobruno/ViZDoom/tree/SVR_2017)]


### Abstract

<p style="text-align:justify;">
In this work, we present a network architecture to solve a supervised learning problem, the classification of a handwritten dataset, and a reinforcement learning problem, a complex First-Person Shooter 3D game environment. We used a Deep Neural Network model to solve both problems. For classification, we used a Softmax regression and cross entropy loss to train the network. To play the game, we used a Q-Learning adaptation for Deep Learning to train the autonomous agent. In both cases, the input was only the pixels of an image. We show that this single network architecture is suitable for the classification task and is capable of playing the 3D game. This result gives us an insight into the possibility of a general network architecture, capable of solving any kind of problems, regardless of the learning paradigm.
</p>


### Video

{% include video id="3MQRcfnaD1Q" provider="youtube" %}


### BibTeX

<p style="text-align:left">
  <a  href="/assets/citations/serafim2017towards.bib">Download</a>
</p>

```
@InProceedings{serafim2017towards,
  title = {Towards Playing a 3D First-Person Shooter Game Using a Classification Deep Neural Network Architecture},
  author  = {Serafim, Paulo Bruno Sousa and Nogueira, Yuri Lenon Barbosa and Vidal, Creto Augusto and Cavalcante-Neto, Joaquim Bento},
  booktitle = {Proceedings of the 19th Symposium on Virtual and Augmented Reality (SVR)},
  pages = {120--126},
  year = {2017},
  doi = {10.1109/SVR.2017.24}
}
```
