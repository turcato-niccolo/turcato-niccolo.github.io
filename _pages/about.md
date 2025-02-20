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
        <!--<p>Abstract: Pick-and-place (PnP) operations, featuring object grasping and trajectory planning, are fundamental in industrial robotics applications. Despite many advancements in the field, PnP is limited by workspace constraints, reducing flexibility. Pick-and-throw (PnT) is a promising alternative where the robot throws objects to target locations, leveraging extrinsic resources like gravity to improve efficiency and expand the workspace. However, PnT execution is complex, requiring precise coordination of high-speed movements and object dynamics. Solutions to the PnT problem are categorized into analytical and learning-based approaches. Analytical methods focus on system modeling and trajectory generation but are time-consuming and offer limited generalization. Learning-based solutions, in particular Model-Free Reinforcement Learning (MFRL), offer automation and adaptability but require extensive interaction time. This paper introduces a Model-Based Reinforcement Learning (MBRL) framework, MC-PILOT, which combines data-driven modeling with policy optimization for efficient and accurate PnT tasks. MC-PILOT accounts for model uncertainties and release errors, demonstrating superior performance in simulations and real-world tests with a Franka Emika Panda manipulator. The proposed approach generalizes rapidly to new targets, offering advantages over analytical and Model-Free methods.</p>-->
        <p><a href="https://arxiv.org/pdf/2502.05595" target="_blank">Read on arXiv</a></p>
    </div>
    <div class="media">
      <iframe src="https://www.youtube.com/embed/0e8IWstunsc?si=CpZNN23oTZkc7GUL" frameborder="0" allowfullscreen></iframe>
    </div>
</div>


<div class="article">
    <div class="text">
        <h2>Reinforcement learning for athletic intelligence: Lessons from the 1st “ai olympics with realaigym” competition</h2>
        <p>Felix Wiebe, Niccolò Turcato, Alberto Dalla Libera, Chi Zhang, Theo Vincent, Shubham Vyas, Giulio Giacomuzzo, Ruggero Carli, Diego Romeres, Akhil Sathuluri, Markus Zimmermann, Boris Belousov, Jan Peters, Frank Kirchner, Shivesh Kumar</p>
        <!--<p>Abstract: As artificial intelligence gains new capabilities, it becomes important to evaluate it on real-world tasks. In particular, the fields of robotics and reinforcement learning (RL) are lacking in standardized benchmarking tasks on real hardware. To facilitate reproducibility and stimulate algorithmic advancements, we held an AI Olympics competition at IJCAI 2023 conference based on the double pendulum system in the RealAIGym project where the participants were asked to develop a controller for the swing up and stabilization task. This paper presents the methods and results from the top participating teams and provides insights into the realworld performance of RL algorithms with respect to a baseline time-varying LQR controller.</p> -->
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
        <!--<p>Abstract: In this paper, we investigate the use of ModelBased Reinforcement Learning (MBRL) for pick-and-throw tasks, which is a variation of the pick-and-place task. In pick-and-throw applications, objects are thrown instead of placed to increase time efficiency and enlarge the workspace reachable by the robot. The effectiveness of analytical methods for this task is limited by the complex system dynamics and the disturbances due to communication and control. Recently, the application of data-driven solutions, in particular Model-Free Reinforcement Learning (MFRL), has attracted attention. In this paper, we explore the use of a MBRL algorithm to solve the pick-and-throw task. Experiments carried out in simulation show the potentialities of our approach, in terms of accuracy and data efficiency, both with respect to analytical methods and a MFRL approach.</p> -->
        <p><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10284290" target="_blank">Read on IEEE Xplore</a></p>
    </div>
    <div class="media">
      <img src='/images/toss.gif'>
    </div>
</div>


<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>