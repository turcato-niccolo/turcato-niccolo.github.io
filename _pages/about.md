---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<h1>Featured Research</h1>

<div class="article">
    <div class="text">
        <h2>Data efficient Robotic Object Throwing with Model-Based Reinforcement Learning</h2>
        <p>Niccolò Turcato, Giulio Giacomuzzo, Matteo Terreran, Davide Allegro, Ruggero Carli, Alberto Dalla Libera</p>
        <details>
          <summary>Abstract</summary>
          <p>Pick-and-place (PnP) operations, featuring object grasping and trajectory planning, are fundamental in industrial robotics applications. Despite many advancements in the field, PnP is limited by workspace constraints, reducing flexibility. Pick-and-throw (PnT) is a promising alternative where the robot throws objects to target locations, leveraging extrinsic resources like gravity to improve efficiency and expand the workspace. However, PnT execution is complex, requiring precise coordination of high-speed movements and object dynamics. Solutions to the PnT problem are categorized into analytical and learning-based approaches. Analytical methods focus on system modeling and trajectory generation but are time-consuming and offer limited generalization. Learning-based solutions, in particular Model-Free Reinforcement Learning (MFRL), offer automation and adaptability but require extensive interaction time. This paper introduces a Model-Based Reinforcement Learning (MBRL) framework, MC-PILOT, which combines data-driven modeling with policy optimization for efficient and accurate PnT tasks. MC-PILOT accounts for model uncertainties and release errors, demonstrating superior performance in simulations and real-world tests with a Franka Emika Panda manipulator. The proposed approach generalizes rapidly to new targets, offering advantages over analytical and Model-Free methods.</p>
        </details>
        <p><a href="https://arxiv.org/pdf/2502.05595" target="_blank">Read on arXiv</a></p>
    </div>
    <div class="media">
      <iframe src="https://www.youtube.com/embed/0e8IWstunsc?si=CpZNN23oTZkc7GUL" frameborder="0" allowfullscreen></iframe>
    </div>
</div>

<div class="article">
    <div class="text">
        <h2><a href="https://turcato-niccolo.github.io/papers/towardsARL/index.html">Towards Autonomous Reinforcement Learning for Real-World Robotic Manipulation with Large Language Models</a></h2>
        <p>Niccolò Turcato, Matteo Iovino, Aris Synodinos, Alberto Dalla Libera, Ruggero Carli, Pietro Falco</p>
        <details>
          <summary>Abstract</summary>
          <p>Recent advancements in Large Language Models (LLMs) and Visual Language Models (VLMs) have significantly impacted robotics, enabling high-level semantic motion planning applications. Reinforcement Learning (RL), a complementary paradigm, enables agents to autonomously optimize complex behaviors through interaction and reward signals. However, designing effective reward functions for RL remains challenging, especially in real-world tasks where sparse rewards are insufficient and dense rewards require elaborate design. In this work, we propose Autonomous Reinforcement learning for Complex HumanInformed Environments (ARCHIE), an unsupervised pipeline leveraging GPT-4, a pre-trained LLM, to generate reward functions directly from natural language task descriptions. The rewards are used to train RL agents in simulated environments, where we formalize the reward generation process to enhance feasibility. Additionally, GPT-4 automates the coding of task success criteria, creating a fully automated, one-shot procedure for translating human-readable text into deployable robot skills. Our approach is validated through extensive simulated experiments on single-arm and bi-manual manipulation tasks using an ABB YuMi collaborative robot, highlighting its practicality and effectiveness. Tasks are demonstrated on the real robot setup.</p>
        </details>
        <p><a href="https://arxiv.org/abs/2503.04280" target="_blank">Read on arXiv</a></p>
    </div>
    <div class="media">
      <iframe src="https://www.youtube.com/embed/kaTxZ4oqD6Y?si=SH87tSijp8h2kEhC" frameborder="0" allowfullscreen></iframe>
    </div>
</div>


<div class="article">
    <div class="text">
        <h2>Reinforcement learning for athletic intelligence: Lessons from the 1st “ai olympics with realaigym” competition</h2>
        <p>Felix Wiebe, Niccolò Turcato, Alberto Dalla Libera, Chi Zhang, Theo Vincent, Shubham Vyas, Giulio Giacomuzzo, Ruggero Carli, Diego Romeres, Akhil Sathuluri, Markus Zimmermann, Boris Belousov, Jan Peters, Frank Kirchner, Shivesh Kumar</p>
        <details>
          <summary>Abstract</summary>
          <p>As artificial intelligence gains new capabilities, it becomes important to evaluate it on real-world tasks. In particular, the fields of robotics and reinforcement learning (RL) are lacking in standardized benchmarking tasks on real hardware. To facilitate reproducibility and stimulate algorithmic advancements, we held an AI Olympics competition at IJCAI 2023 conference based on the double pendulum system in the RealAIGym project where the participants were asked to develop a controller for the swing up and stabilization task. This paper presents the methods and results from the top participating teams and provides insights into the realworld performance of RL algorithms with respect to a baseline time-varying LQR controller.</p>
        </details>
        <p><a href="https://www.researchgate.net/profile/Niccolo_Turcato/publication/382788511_Reinforcement_Learning_for_Athletic_Intelligence_Lessons_from_the_1st_AI_Olympics_with_RealAIGym_Competition/links/66d0231db1606e24c2a6592a/Reinforcement-Learning-for-Athletic-Intelligence-Lessons-from-the-1st-AI-Olympics-with-RealAIGym-Competition.pdf" target="_blank">Read paper</a></p>
    </div>
    <div class="media">
        <iframe src="https://www.youtube.com/embed/eYDH1v1FqF8?si=lkUBxVSZi0Vo-qdV?autoplay=0" frameborder="0" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/-1qCz1fJmT4?autoplay=0" frameborder="0" allowfullscreen></iframe>
    </div>
</div>

<div class="article">
    <div class="text">
        <h2>Teaching a Robot to Toss Arbitrary Objects with Model-Based Reinforcement Learning</h2>
        <p>Niccolò Turcato, Alberto Dalla Libera, Giulio Giacomuzzo, Ruggero Carli</p>
        <details>
          <summary>Abstract</summary>
          <p>In this paper, we investigate the use of ModelBased Reinforcement Learning (MBRL) for pick-and-throw tasks, which is a variation of the pick-and-place task. In pick-and-throw applications, objects are thrown instead of placed to increase time efficiency and enlarge the workspace reachable by the robot. The effectiveness of analytical methods for this task is limited by the complex system dynamics and the disturbances due to communication and control. Recently, the application of data-driven solutions, in particular Model-Free Reinforcement Learning (MFRL), has attracted attention. In this paper, we explore the use of a MBRL algorithm to solve the pick-and-throw task. Experiments carried out in simulation show the potentialities of our approach, in terms of accuracy and data efficiency, both with respect to analytical methods and a MFRL approach.</p>
        </details>
        <p><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10284290" target="_blank">Read on IEEE Xplore</a></p>
    </div>
    <div class="media">
      <img src='/images/toss.gif'>
    </div>
</div>


<div class="article">
    <div class="text">
        <h2>Nonlinear Model Predictive Control of a BMI-Guided Wheelchair for Navigation in Unknown Environments</h2>
        <p>Davide De Lazzari, Piero Simonetto, Niccolò Turcato, Luca Tonin, Ruggero Carli</p>
        <details>
          <summary>Abstract</summary>
          <p>The ability to discern human intentions from brain signals has opened the possibility of leveraging Brain-Machine Interfaces (BMIs) for the control of robotic devices, especially benefiting individuals with severe motor disabilities. In this work, we present a novel approach for navigating a semiautonomous wheelchair towards targets generated by a BMI, all while ensuring collision avoidance. Our approach employs Nonlinear Model Predictive Control (NMPC) for real-time trajectory generation in unknown and dynamic environments. The empirical results obtained from real-world experiments clearly demonstrate the advancements of our solution over current state-of-the-art techniques. Our implementation is proven to outperform well-established methods in terms of both smoothness and alignment with the user's intended behavior.</p>
        </details>
        <p><a href="https://ieeexplore.ieee.org/abstract/document/10591234/" target="_blank">Read on IEEE Xplore</a></p>
    </div>
    <div class="media">
      <iframe src="https://www.youtube.com/embed/rCUJUujnWH0?si=w7hJ1oklsqaDHF4M" frameborder="0" allowfullscreen></iframe>
      <!--
      <video id="teaser" autoplay muted loop playsinline style="width: auto; height: 50%;">
        <source src="/videos/wheelchair_test_15s_single_obj.mp4"
                type="video/mp4">
      </video>-->
    </div>
</div>

