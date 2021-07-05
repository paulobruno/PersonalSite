---
title: "Investigating Deep Q-Network Agent Sensibility to Texture Changes on FPS Games"
subtitle: "XIX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)"
thumbnail: /assets/images/investigating.jpg
header:
    teaser: /assets/images/investigating.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - ViZDoom
  - SBGames
---

*XIX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)*  

[Paulo Bruno de Sousa Serafim](https://paulobruno.github.io)<sup>1</sup>
  [Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)<sup>2</sup>
  [Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)<sup>2</sup>  
[Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)<sup>2</sup>
  [Rômulo Freire Férrer Filho](https://github.com/romulofff)<sup>3</sup>

<p style="font-size:0.7em">
    <sup>1</sup>Instituto Atlântico
     <sup>2</sup>Department of Computing (DC), Federal University of Ceara (UFC)<br>
    <sup>3</sup>Teleinformatics Engineering Department (DETI), Federal University of Ceara (UFC)
</p>

![Agents' sensibility](/assets/images/investigating.jpg)

---

Paper: [[PDF](https://www.sbgames.org/proceedings2020/ComputacaoFull/209515.pdf)]
 Page: [[IEEE](https://ieeexplore.ieee.org/document/9291626)]


### Abstract

<p style="text-align:justify;">
Graphical updates are very common in modern digital games. For instance, PC game versions usually receive higher resolution textures after some time. This could be a problem for autonomous agents trained to play a game using Convolutional Neural Networks. These agents use the pixels of the screen as inputs and changing them could harm their performance. In this work, we evaluate agents' sensibility to texture changes. The agents are trained to play a First-Person Shooter game and then are presented to different versions of the same scenario, in which the only difference among them is texture changes. As the testbed, we use a ViZDoom scenario with a static monster that should be killed by the agent. Four agents are trained using Deep Q-Networks in four different scenarios. Then, every agent is tested in all four scenarios. We show that although every agent can learn the behaviors to win the game when playing the same version in which it was trained, they cannot generalize to all other versions. Only in one case, the agent had a good performance in a different scenario. Most of the time, the agent moved randomly or just stood still, and shot continuously, indicating that it could not understand the current screen. Even when the background textures were kept the same, the agent could not identify the enemy. Thus, to ensure proper behavior, an agent needs to be retrained not only if the problem changes, but also when only the visual aspects of the problem are modified.
</p>


### Video

<p style="text-align:left;font-size:0.7em"><i>Presentation starts at 33:34</i></p>

{% include video id="Zp1_KQdWSI0" provider="youtube" %}


### BitTeX

<p style="text-align:left">
  <a  href="/assets/citations/serafim2020investigating.bib">Download</a>
</p>

```
@InProceedings{serafim2020investigating,
  title = {Investigating Deep Q-Network Agent Sensibility to Texture Changes on {FPS} Games},
  author  = {Serafim, Paulo Bruno Sousa and Nogueira, Yuri Lenon Barbosa and Vidal, Creto Augusto and Cavalcante-Neto, Joaquim Bento and F\'{e}rrer Filho, R\^{o}mulo Freire},
  booktitle = {Proceedings of the XIX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)},
  pages = {1--9},
  year = {2020},
  issn = {2179-2259},
  doi = {}
}
```
