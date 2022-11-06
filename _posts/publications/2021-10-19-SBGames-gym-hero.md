---
title: "Gym Hero: A Research Environment for Reinforcement Learning Agents in Rhythm Games"
subtitle: "XX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)"
thumbnail: /assets/images/gymhero.jpg
header:
    teaser: /assets/images/gymhero.jpg
categories:
  - Publication
tags:
  - Deep Reinforcement Learning
  - GymHero
  - SBGames
---

*XX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)*  

[Rômulo Freire Férrer Filho](https://github.com/romulofff)<sup>1</sup>
  [Yuri Lenon Barbosa Nogueira](http://www.lia.ufc.br/~yuri/)<sup>2</sup>
  [Creto Augusto Vidal](http://www.lia.ufc.br/~cvidal/)<sup>2</sup>  
[Joaquim Bento Cavalcante Neto](http://www.lia.ufc.br/~joaquimb/)<sup>2</sup>
  [Paulo Bruno de Sousa Serafim](https://paulobruno.github.io)<sup>3</sup>

<p style="font-size:0.7em">
    <sup>1</sup>Teleinformatics Engineering Department (DETI), Federal University of Ceara (UFC)<br>
    <sup>2</sup>Department of Computing (DC), Federal University of Ceara (UFC)  
     <sup>3</sup>Instituto Atlântico
</p>

![Gym Hero](/assets/images/gymhero.jpg)

---

Paper: [[PDF](https://www.sbgames.org/proceedings2021/ComputacaoFull/217884.pdf)]
 Page: [[IEEE](https://ieeexplore.ieee.org/document/9637691)]


### Abstract

<p style="text-align:justify;">
This work presents a Reinforcement Learning environment, called Gym Hero, based on the game Guitar Hero. It consists of a similar game implementation, developed using the graphics engine PyGame, with four difficulty levels, and able to randomly generate tracks. On top of the game, we implemented a Gym environment to train and evaluate Reinforcement Learning agents. In order to assess the environment's capacity as a suitable learning tool, we ran a set of experiments to train three autonomous agents using Deep Reinforcement Learning. Each agent was trained on a different level using Deep Q-Networks, a technique that combines Reinforcement Learning with Deep Neural Networks. The input of the network is only the pixels of the screen. We show that the agents were capable of learning the expected behaviors to play the game. The obtained results validate the proposed environment as capable of evaluating autonomous agents on Reinforcement Learning tasks.
</p>


### Video

<p style="text-align:left;font-size:0.7em"><i>Presentation starts at 14:52</i></p>

{% include video id="eJRgUhP-88E" provider="youtube" %}


### BibTeX

<p style="text-align:left">
  <a  href="/assets/citations/ferrer2021gymhero.bib">Download</a>
</p>

```
@InProceedings{ferrer2021gymhero,
  title = {Gym Hero: A Research Environment for Reinforcement Learning Agents in Rhythm Games},
  author  = {F\'{e}rrer Filho, R\^{o}mulo Freire and Nogueira, Yuri Lenon Barbosa and Vidal, Creto Augusto and Cavalcante-Neto, Joaquim Bento and Serafim, Paulo Bruno Sousa},
  booktitle = {Proceedings of the XX Brazilian Symposium on Computer Games and Digital Entertainment (SBGames)},
  pages = {87--96},
  year = {2021},
  doi = {10.1109/SBGames54170.2021.00020}
}
```
