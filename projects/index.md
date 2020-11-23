---
layout: page
---
<ol>
<h1><li>Generating a variety of counter-examples</h1><br/>
<a href="https://www.sciencedirect.com/science/article/pii/S2405896318311376" target="_blank">[ADHS'18]</a>
<a href="https://ieeexplore.ieee.org/document/9147430" target="_blank">[ACC'20]</a>
<a href="http://www.sciencedirect.com/science/article/pii/S000510982030203X" target="_blank">[AUT'20]</a> <br/>
Control design for linear systems typically involves pole placement and computing Lyapunov functions. While these tools are useful for ensuring stability, they are not always helpful in ensuring safety. Control designers can employ model checking as a 
tool for checking safety. We believe that supple- menting the model checker to provide various types of counter- examples for the safety specification would help the control designer in the control development process. In this work, we describe a technique for obtaining the variety of counterexamples for a safety violation in linear hybrid systems. More specifically, we develop algorithms to extract the longest counterexample --- the execution that stays in the unsafe set for the longest time, deepest counterexample --- the execution that ventures the most into the unsafe set in a user specified direction, and the robust counterexample --- the unsafe execution from which some bounded perturbation yields a new counterexample. These measures for classifying counter- examples can further assist in quantifying controllers' performance.<br/><br/>
</li>
<p align="center"> <img width="420" src="/public/images/v_t_2.png" alt="ACC Controller"></p>

<h1><li>NeuralExplorer: State space exploration using neural networks</h1><br/>
<a href="http://proceedings.mlr.press/v120/goyal20a.html" target="_blank">[L4DC'20]</a>
<a href="https://ieeexplore.ieee.org/document/9147430" target="_blank">[ATVA'20]</a> [DARS'19]<br/>

In this work, we propose a framework for performing state space exploration of closed loop control systems. Our approach involves approximating sensitivity and a newly introduced notion of inverse sensitivity by a neural network. We show how the approximation of sensitivity and inverse sensitivity can be used for computing estimates of the reachable set. We then outline algorithms for performing state space exploration by generating trajectories that reach a neighborhood. We demonstrate the effectiveness of our approach by applying it not only to standard linear and nonlinear dynamical systems, but also to nonlinear hybrid systems and also neural network based feedback control systems.<br/><br/>

<p align="center"> <img width="420" src="/public/images/fig-inv-sen-basic.png" alt="reachTarget using inverse sensitivity"/> </p>
</li>
</ol>
