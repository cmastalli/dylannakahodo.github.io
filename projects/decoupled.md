---
layout: post
title: 'Planning and Execution of Dynamic Whole-Body Locomotion for a Hydraulic Quadruped on Challenging Terrain'
---

  <iframe class="embed-responsive-item" allowfullscreen="allowfullscreen"
    width="420" height="237"
    src="https://www.youtube.com/embed/MF-qxA_syZg"
    style="float: right; "
    marginwidth="10">
  </iframe>


We present a framework for dynamic quadrupedal locomotion over challenging terrain, where the choice of appropriate footholds is crucial for the success of the behaviour. We build a model of the environment on-line and on-board using an efficient occupancy grid representation. We use Any-time-Repairing A* (ARA*) to search over a tree of possible actions, choose a rough body path and select the locally-best footholds accordingly. We run a n-step lookahead optimization of the body trajectory using a dynamic stability metric, the Zero Moment Point (ZMP), that generates natural dynamic whole-body motions. A combination of floating-base inverse dynamics and virtual model control accurately executes the desired motions on an actively compliant system. Experimental trials show that this framework allows us to traverse terrains at nearly 6 times the speed of our previous work, evaluated over the same set of trials.

  #### [Planning and Execution of Dynamic Whole-Body Locomotion for a Hydraulic Quadruped on Challenging Terrain (ICRA)](/assets/pdf/locomotion15icra.pdf)
  
  <a href="/assets/pdf/locomotion15icra.pdf">
    <img src="/assets/img/download.png" alt="Drawing" style="height: 20px;"/>
  </a>
  <a href="/assets/bibtex/locomotion15icra.bib">
    <img src="/assets/img/bibtex.jpeg" alt="Drawing" style="height: 20px;"/>
  </a>
