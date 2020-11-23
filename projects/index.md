---
layout: page
title: Projects
---

<h1>Generating a variety of counterexamples</h1><br/>
Control design for linear systems typically involves pole placement and computing Lyapunov functions. While these tools are useful for ensuring stability, they are not always helpful in ensuring safety. Control designers can employ model checking as a tool for checking safety. We believe that supplementing the model checker to provide various types of counterexamples for the safety specification would help the control designer in the control development process. In this work, we describe a technique for obtaining the variety of counterexamples for a safety violation in linear hybrid systems. More specifically, we develop algorithms to extract the longest counterexample --- the execution that stays in the unsafe set for the longest time, deepest counterexample --- the execution that ventures the most into the unsafe set in a user specified direction, and the robust counterexample --- the unsafe execution from which some bounded perturbation yields a new counterexample. These measures for classifying counterexamples can further assist in quantifying controllers' performance.<br/>

<img align="left" width="400" src="/public/images/v_t_1.png" alt="ACC Controller 1">
<img align="right" width="400" src="/public/images/v_t_2.png" alt="ACC Controller 2">
