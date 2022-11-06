---
title: "Autonomous Foraging with SARSA-based Deep Reinforcement Learning"
subtitle: "XXII Symposium on Virtual and Augmented Reality (SVR)"
thumbnail: /assets/images/autonomous_foraging.jpg
header:
    teaser: /assets/images/autonomous_foraging.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - Foraging
  - SVR
---
<!--__faltando: links pra pdf, ieee e apresentação no youtube, doi no bibtex*__-->
*XXII Symposium on Virtual and Augmented Reality (SVR)*  

[Anderson Oliveira Mesquita](https://www.linkedin.com/in/anderson-oliveira-b65099133/)<sup>1</sup>
  [Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)<sup>1</sup>
  [Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)<sup>1</sup>  
[Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)<sup>1</sup>
  [Paulo Bruno de Sousa Serafim](https://paulobruno.github.io)<sup>2</sup>

<p style="font-size:0.7em">
    <sup>1</sup>Department of Computing (DC), Federal University of Ceara (UFC)<br>
    <sup>2</sup>Instituto Atlântico
</p>

![Autonomous foraging](/assets/images/autonomous_foraging.jpg)

---

Page: [[IEEE](https://ieeexplore.ieee.org/document/9262697)]


### Abstract

<p style="text-align:justify;">
This work proposes an autonomous system capable of foraging in an environment that has food and poisons distributed throughout a scenario. We use Deep Learning framework to process color images. These images simulate the agent's vision. The foraging task is modeled as a reinforcement learning problem, in which an input constituted by raw pixels is processed by a convolutional neural network resulting in an set of actions. An algorithm based on SARSA was used. During training, the agent selects the actions based on a probability distribution called Softmax. The objective of this work is to present an agent capable of searching for food and distinguishing it from poisons through continuous learning and without the help or external intervention from humans. The experiments show that the agent is able to distinguish food from poisons without the hints or markings in it's vision input. This highlights the advantages of combining Deep Learning with reinforcement learning for the foraging problem. The results of this work form an initial basis for understanding the relationship among autonomy, cognition and perception in artificial agents.
</p>


### Video

<p style="text-align:left;font-size:0.7em"><i>Presentation starts at 1:47</i></p>

{% include video id="RwAUlDVUEhw" provider="youtube" %}


### BibTeX

<p style="text-align:left">
  <a  href="/assets/citations/mesquita2020autonomous.bib">Download</a>
</p>

```
@InProceedings{mesquita2020autonomous,
  title = {Autonomous Foraging with {SARSA}-based Deep Reinforcement Learning},
  author  = {Mesquita, Anderson Oliveira and Nogueira, Yuri Lenon Barbosa and Vidal, Creto Augusto and Cavalcante-Neto, Joaquim Bento and Serafim, Paulo Bruno Sousa},
  booktitle = {Proceedings of the XXII Symposium on Virtual and Augmented Reality (SVR)},
  pages = {1--9},
  year = {2020},
  doi = {10.1109/SVR51698.2020.00070}
}
```
