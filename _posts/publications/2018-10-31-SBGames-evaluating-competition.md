---
title: "Evaluating Competition in Training of Deep Reinforcement Learning Agents in First-Person Shooter Games"
subtitle: "17th Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)"
thumbnail: /assets/images/two_agents.jpg
header:
    teaser: /assets/images/two_agents.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - ViZDoom
  - SBGames
---

*17th Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)*  

[Paulo Bruno de Sousa Serafim](https://paulobruno.github.io)
  [Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)  
[Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)
  [Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)

<p style="font-size:0.7em">
    Department of Computing (DC), Federal University of Ceara (UFC)
</p>

![Both agents facing each other](/assets/images/two_agents.jpg)

---

Paper: [[PDF](https://www.sbgames.org/sbgames2018/files/papers/ComputacaoFull/188165.pdf)]
 Proceedings: [[IEEE](https://ieeexplore.ieee.org/document/8636940)]
 Code: [[GitHub](https://github.com/paulobruno/ViZDoom/tree/pbmaster)]


### Abstract

<p style="text-align:justify">
This work evaluates competition in training of autonomous agents immersed in First-Person Shooter games using Deep Reinforcement Learning. The agents are composed of a Deep Neural Network, which is trained using Deep QLearning. The inputs of the networks are only the pixels of the screen, allowing the creation of general players, capable of handling several environments without the need for further modifications. ViZDoom, an Application Programming Interface based on the game Doom, is used as the testbed because of its appropriate features. Fifteen agents were divided into three groups, two of which were trained by competing with each other, and the third was trained by competing against opponents that act randomly. The developed agents were able to learn adequate behaviors to survive in a custom one-onone scenario. The tests showed that the competitive training of autonomous agents leads to a greater number of wins compared to training against non-intelligent agents.
</p>


### Videos

{% include video id="g6E_c2DgB24" provider="youtube" %}
{% include video id="LVtxSdJiW4c" provider="youtube" %}


### BibTeX

<p style="text-align:left">
  <a  href="/assets/citations/serafim2018evaluating.bib">Download</a>
</p>

```
@InProceedings{serafim2018evaluating,
  title = {Evaluating competition in training of Deep Reinforcement Learning agents in First-Person Shooter games},
  author  = {Serafim, Paulo Bruno Sousa and Nogueira, Yuri Lenon Barbosa and Vidal, Creto Augusto and Cavalcante-Neto, Joaquim Bento},
  booktitle = {Proceedings of the XVII Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)},
  pages = {468--477},
  year = {2018},
  doi = {10.1109/SBGAMES.2018.00023}
}
```
