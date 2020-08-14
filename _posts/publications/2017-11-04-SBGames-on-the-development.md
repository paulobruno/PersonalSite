---
title: "On the Development of an Autonomous Agent for a 3D First-Person Shooter Game Using Deep Reinforcement Learning"
subtitle: "16th Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)"
thumbnail: /assets/images/all_scenarios_color.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - ViZDoom
  - SBGames
---

*16th Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)*  
**Best Paper Award Nominee**

[Paulo Bruno de Sousa Serafim](paulobruno.github.io)
  [Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)  
[Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)
  [Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)

<p style="font-size:0.7em">
    Department of Computing (DC), Federal University of Ceara (UFC)
</p>

![Scenarios, render view](/assets/images/all_scenarios_color.jpg)
![Scenarios, agent's PoV](/assets/images/all_scenarios_grey.png)

---

Paper: [[PDF](https://www.sbgames.org/sbgames2017/papers/ComputacaoFull/175301.pdf)]
 Proceedings: [[IEEE](https://ieeexplore.ieee.org/document/8400328)]
 Code: [[GitHub](https://github.com/paulobruno/ViZDoom/tree/SBGames)]


### Abstract

<p style="text-align: justify">
First-Person Shooter games have always been very popular. One of the challenges in the development of First-Person Shooter games is the use of game agents controlled by Artificial Intelligence because they can learn how to handle very distinct situations presented to them. In this work, we construct an autonomous agent to play different scenarios in a 3D First-Person Shooter game using a Deep Neural Network model. The agent receives as input only the pixels of the screen and should learn how to interact with the environments by itself. To achieve this goal, the agent is trained using a Deep Reinforcement Learning model through an adaptation of the Q-Learning technique for Deep Networks. We evaluate our agent in three distinct scenarios: a basic environment against one static enemy, a more complex environment against multiple different enemies and a custom medikit gathering scenario. We show that the agent achieves good results and learns complex behaviors in all tested environments. The results show that the presented model is suitable for creating 3D First-Person Shooter autonomous agents capable of playing different scenarios.
</p>


### Video

{% include video id="JTNZCXO1r2Y" provider="youtube" %}


### BitTeX

<p style="text-align:left">
  <a  href="/assets/citations/serafim2017on.bib">Download</a>
</p>

```
@InProceedings{serafim2017on,
  title = {On the Development of an Autonomous Agent for a 3D First-Person Shooter Game Using Deep Reinforcement Learning},
  author  = {Serafim, Paulo Bruno Sousa and Nogueira, Yuri Lenon Barbosa and Vidal, Creto Augusto and Cavalcante-Neto, Joaquim Bento},
  booktitle = {Anais do XVI Simpósio Brasileiro de Jogos e Entretenimento Digital (SBGames)},
  pages = {477--483}, 
  year = {2017},
  doi = {10.1109/SBGames.2017.00025}
}
```
