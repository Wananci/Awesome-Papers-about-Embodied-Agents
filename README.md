# Awesome Papers about VLM for Embodiment Task

A curated list of influential papers about VLM for embodiment task which is maintained by [Wananci](https://github.com/Wananci). 

## Table of Contents
- [Introduction](#introduction)
- [Paper Categories](#paper-categories)
  - [Primitive Skill](#primitive-skill)
  - [Learning in Embodied Agents](#learning-in-embodied-agents)
  - [Simulation Environments](#simulation-environments)
  - [Applications](#applications)
- [Contributing](#contributing)
- [License](#license)

# Introduction

Embodied agents are AI-driven systems designed to interact with the physical or virtual world through a body or avatar, enabling perception, action, and communication. These agents combine sensory inputs (e.g., vision, speech) with cognitive processes to perform tasks, simulate human-like behaviors, or engage in immersive interactions. They are widely used in robotics, virtual assistants, and gaming for more natural and context-aware interactions.

# Paper Categories
# Primitive Skill
- [**Primitive Skill-based Robot Learning from Human Evaluative Feedback**](http://arxiv.org/abs/2307.15801) [**arXiv 2023.07**] [**code**](https://seediros23.github.io/)  
  Ayano Hiranaka*<sup>1</sup>, Minjune Hwang*<sup>2</sup>, Sharon Lee<sup>2</sup>, Chen Wang<sup>2</sup>, Li Fei-Fei<sup>2</sup>, Jiajun Wu<sup>2</sup>, Ruohan Zhang<sup>2</sup>  
  <sup>1</sup>Department of Mechanical Engineering, Stanford University  
  <sup>2</sup>Department of Computer Science, Stanford University  
  <details>
    <summary><b>Abstract</b></summary>
    <img src="./imgs/SEED.png" alt="Abstract Image" width="800">  
    <em>Reinforcement learning (RL) algorithms face significant challenges when dealing with long-horizon robot manipulation tasks in real-world environments due to sample inefficiency and safety issues. To overcome these challenges, we propose a novel framework, SEED, which leverages two approaches: reinforcement learning from human feedback (RLHF) and primitive skill-based reinforcement learning. Both approaches are particularly effective in addressing sparse reward issues and the complexities involved in long-horizon tasks. By combining them, SEED reduces the human effort required in RLHF and increases safety in training robot manipulation with RL in real-world settings. Additionally, parameterized skills provide a clear view of the agent’s high-level intentions, allowing humans to evaluate skill choices before they are executed. This feature makes the training process even safer and more efficient. To evaluate the performance of SEED, we conducted extensive experiments on five manipulation tasks with varying levels of complexity. Our results show that SEED significantly outperforms state-of-the-art RL algorithms in sample efficiency and safety. In addition, SEED also exhibits a substantial reduction of human effort compared to other RLHF methods. Further details and video results can be found at https: //seediros23.github.io/.</em>
  </details>
  