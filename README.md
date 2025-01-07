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

## 🚀 Primitive Skill
- [**Primitive Skill-based Robot Learning from Human Evaluative Feedback**](http://arxiv.org/abs/2307.15801) [**arXiv 2023.07**] [[**🔗 Code**]](https://seediros23.github.io/)  
  **Authors**: Ayano Hiranaka*<sup>1</sup>, Minjune Hwang*<sup>2</sup>, Sharon Lee<sup>2</sup>, Chen Wang<sup>2</sup>, Li Fei-Fei<sup>2</sup>, Jiajun Wu<sup>2</sup>, Ruohan Zhang<sup>2</sup>  
  **Affiliations**:  
  <sup>1</sup>Department of Mechanical Engineering, Stanford University  
  <sup>2</sup>Department of Computer Science, Stanford University  

### 🌟 **Highlight**
<details>
    <summary><b>Click to expand</b></summary>

    ![SEED Architecture](./imgs/SEED.png)

    **Key Concepts**:
    - **Human Evaluation**: The human provides evaluative feedback to guide robot skill learning.
    - **Primitive Skill**: The model focuses on learning distinct robot manipulation skills based on human feedback.
    - **Parameter Policy**: Each skill is associated with a unique parameterization to adapt to varying task requirements.

    ---
    Neural network architecture for SEED:
    - **Skill Policy** (`π_θ`): Selects a skill based on state observation.
    - **Parameter Policy** (`π_φ`): Determines specific parameters for the selected skill.
    - **Human Critic Network**: Trains using human feedback to refine robot decision-making.
</details>

### 🖼️ **Figure**
![SEED Architecture](./imgs/SEED.png)  

*Fig. 2. Neural network architecture for SEED. This framework combines a skill policy, parameter policy, and human critic network to enable robots to learn efficient manipulation skills based on human feedback.*

---

  