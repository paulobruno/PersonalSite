---
title: "Assessing the Robustness of Deep Q-Network Agents to Changes on Game Object Textures"
subtitle: "XX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)"
thumbnail: /assets/images/assessing.jpg
header:
    teaser: /assets/images/assessing.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - ViZDoom
  - SBGames
---

*XX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)*  

[Paulo Bruno de Sousa Serafim](https://paulobruno.github.io)<sup>1</sup>
  [Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)<sup>2</sup>  
[Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)<sup>2</sup>
  [Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)<sup>2</sup>

<p style="font-size:0.7em">
    <sup>1</sup>Instituto Atlântico
     <sup>2</sup>Department of Computing (DC), Federal University of Ceara (UFC)<br>
</p>

![Assessing robustness](/assets/images/assessing.jpg)

---

Paper: [[PDF](https://www.sbgames.org/proceedings2021/ComputacaoFull/217993.pdf)]


### Abstract

<p style="text-align:justify;">
The research in autonomous agents aspires to achieve Artificial General Intelligence, where agents, like humans, are able to understand concepts and learn how to solve tasks. We would like to observe this ability on game agents as well. Recent research on autonomous agents for game playing uses a combination of Deep Neural Networks and Reinforcement Learning algorithms. Commonly, Neural Networks present vision-based models, usually Convolutional Neural Networks (CNN). However, those models can undergo performance degradation when dealing with different pixel patterns, an issue that also happens with vision-based autonomous agents in games. Prior works have shown that CNN-based autonomous agents cannot reproduce the behavior learned in one scene when they are placed into a brand new version with different textures. In this work, we evaluate whether the agents educe high-level elements, such as enemy, foreground, and background. Instead of testing the agent in a completely different scene, we designed two experiments based on slight changes. In the first experiment, we change only a subset of the game objects. In the second experiment, the agents play in an interpolated version of two scenes. Even when changing only a single game object texture, the agents are not guaranteed to present good behavior. We show that, depending on the training scenario, the agents are not fully robust to generalize a high-level concept of game objects.
</p>


### Video

<p style="text-align:left;font-size:0.7em"><i>Presentation starts at 49:04</i></p>

{% include video id="RmV6rUZQaeE" provider="youtube" %}


### BitTeX

<p style="text-align:left">
  <a  href="/assets/citations/serafim2021assessing.bib">Download</a>
</p>

```
@InProceedings{serafim2021assessing,
  title = {Assessing the Robustness of Deep Q-Network Agents to Changes on Game Object Textures},
  author  = {Serafim, Paulo Bruno Sousa and Nogueira, Yuri Lenon Barbosa and Cavalcante-Neto, Joaquim Bento and Vidal, Creto Augusto},
  booktitle = {Proceedings of the XX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)},
  pages = {1--9},
  year = {2021}
}
```
