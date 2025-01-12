# Awesome Papers about VLM for Embodiment Task

A curated list of influential papers about VLM for embodiment task which is maintained by [Wananci](https://github.com/Wananci). 

## Table of Contents
- [Introduction](#introduction)
- [🤖Reinforcement Learning](#reinforcement-learning)
  - [Primitive Skill](#primitive-skill)
- [👀Vision Language Action Model](#vision-language-action-model)

# Introduction

Embodied agents are AI-driven systems designed to interact with the physical or virtual world through a body or avatar, enabling perception, action, and communication. These agents combine sensory inputs (e.g., vision, speech) with cognitive processes to perform tasks, simulate human-like behaviors, or engage in immersive interactions. They are widely used in robotics, virtual assistants, and gaming for more natural and context-aware interactions.

<a id="reinforcement-learning"></a>

# 🤖 Reinforcement-Learning

<a id="primitive-skill"></a>

# Primitive Skill
- [**Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor**](http://arxiv.org/abs/1801.01290) [**arXiv 2018.08**] [[**Code**]](https://github.com/haarnoja/sac)

  <details>
    <summary>🔍 <b>Highlight</b></summary>
    <em>"Our method instead combines off-policy actorcritic training with a stochastic actor, and further aims to maximize the entropy of this actor with an entropy maximization objective."</em>  

    - **Maximum Entropy**
    - **Stochastic Actor**

  </details>

  **Authors**: Tuomas Haarnoja<sup>1</sup>, Aurick Zhou<sup>1</sup>, Pieter Abbeel<sup>1</sup>, Sergey Levine<sup>1</sup>  
  <sup>1</sup>University of California, Berkeley  

- [**Augmenting Reinforcement Learning with Behavior Primitives for Diverse Manipulation Tasks**](http://arxiv.org/abs/2110.03655) [**arXiv 2022.06**] [[**Code**]](https://ut-austin-rpl.github.io/maple)

  <details>
    <summary>🔍 <b>Highlight</b></summary>

    - **Hierarchical Policy: high-level for primitive and low-level for parameters** 
    - **Agent tends to use high-level primitive rather than atomic action**
    - **Exploration with Affordances**

    ![Maple Architecture](./imgs/MAPLE.png)
  </details>

  **Authors**: Soroush Nasiriany<sup>1</sup>, Huihan Liu<sup>1</sup>, Yuke Zhu<sup>1</sup>  
  <sup>1</sup>The University of Texas at Austin  

- [**Primitive Skill-based Robot Learning from Human Evaluative Feedback**](http://arxiv.org/abs/2307.15801) [**arXiv 2023.07**] [[**Code**]](https://seediros23.github.io/)

  <details>
    <summary>🔍 <b>Highlight</b></summary>

    - **Human Evaluation** 
    - **Primitive Skill**
    - **Parameter Policy**

    ![SEED Architecture](./imgs/SEED.png)
  </details>

  **Authors**: Ayano Hiranaka*<sup>1</sup>, Minjune Hwang*<sup>2</sup>, Sharon Lee<sup>2</sup>, Chen Wang<sup>2</sup>, Li Fei-Fei<sup>2</sup>, Jiajun Wu<sup>2</sup>, Ruohan Zhang<sup>2</sup>  
  <sup>1</sup>Department of Mechanical Engineering, Stanford University  
  <sup>2</sup>Department of Computer Science, Stanford University  

<a id="vision-language-action-model"></a>

# 👀 Vision Language Action Model

<a id="world-model"></a>

# World Model
- [**Learning Universal Policies via Text-Guided Video Generation**](http://arxiv.org/abs/2302.00111) [**arXiv 2023.11**] [[**Code**]](https://universal-policy.github.io/)
  
  <details>
    <summary>🔍 <b>Highlight</b></summary>

    - **Diffusion model - Tiling** 
    - **Coarse-to-fine generate video**

    ![Unipi](./imgs/UniPi.png)
  </details>

  **Authors**: Yilun Du*<sup>†‡</sup>, Mengjiao Yang*<sup>‡§</sup>, Bo Dai<sup>‡¶</sup>, Hanjun Dai<sup>‡¶</sup>, Ofir Nachum<sup>‡</sup>, Joshua B. Tenenbaum<sup>†</sup>, Dale Schuurmans<sup>‡‖</sup>, Pieter Abbeel<sup>§</sup>  
  <sup>†</sup>MIT  
  <sup>‡</sup>Google DeepMind  
  <sup>§</sup>UC Berkeley  
  <sup>¶</sup>Georgia Tech  
  <sup>‖</sup>University of Alberta

- [**Learning Interactive Real-World Simulators**](http://arxiv.org/abs/2310.06114) [**arXiv 2024.09**] [[**Code**]](https://universal-simulator.github.io)

  <details>
    <summary>🔍 <b>Highlight</b></summary>

    - **Multi-source data**  
    - **Diffusion model**
    - **Generate video through past observation and input action**   
  
    ![UniSim](./imgs/UniSim.png)
  </details>

  **Authors**: Sherry Yang<sup>1,2</sup>, Yilun Du<sup>3</sup>, Seyed Kamyar Seyed Ghasemipour<sup>2</sup>, Jonathan Tompson<sup>2</sup>, Leslie Kaelbling<sup>3</sup>, Dale Schuurmans<sup>2,4</sup>, Pieter Abbeel<sup>1</sup>  
  <sup>1</sup>UC Berkeley  
  <sup>2</sup>Google DeepMind  
  <sup>3</sup>MIT  
  <sup>4</sup>University of Alberta  

- [**Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](http://arxiv.org/abs/2412.15109) [**arXiv 2024.12**] [[**Code**]](https://nimolty.github.io/Seer/)

  <details>
    <summary>🔍 <b>Highlight</b></summary>

    - **End-to-End model**  
    - **Unidirectional Attention Mask**  
    - **Predict future image and action**  

    ![Seer](./imgs/Seer.png)
  </details>

  **Authors**: Yang Tian<sup>1,4,*</sup>, Sizhe Yang<sup>6,1,*</sup>, Jia Zeng<sup>1</sup>, Ping Wang<sup>3,4,5</sup>, Dahua Lin<sup>6</sup>, Hao Dong<sup>2</sup>, Jiangmiao Pang<sup>1,†</sup>  
  <sup>1</sup>Shanghai AI Laboratory  
  <sup>2</sup>CFCS, School of CS, Peking University  
  <sup>3</sup>National Engineering Research Center for Software Engineering, Peking University  
  <sup>4</sup>School of Software & Microelectronics, Peking University  
  <sup>5</sup>Key Laboratory of High Confidence Software Technologies (PKU), Ministry of Education  
  <sup>6</sup>Chinese University of Hong Kong
