# FCPN
*FCPN* stands for "*Fuzzy Continuous Petri Nets*". The purpose of FCPN is to provide users with services to complete
the simulation and fuzzy inference by constructing Petri nets.
<br>
![Latest version](https://img.shields.io/badge/Latest%20version-1.0.0-blue.svg)
![Programming language](https://img.shields.io/badge/Programming%20language-C++-red.svg)
![Operating system](https://img.shields.io/badge/Operating%20system-Windows-yellow.svg)
<br>
*Authors*: Fei Liu, Wujie Sun, Yexuan Sun, Yuchen Zhou, Shijing Zhu, and Zhijie Zhang.
## News
2018-08-31 The first version of FCPN is finished and internally used.<br>
2018-12-05  New stable version of FCPN is released.
## Table of Contents
- [Background and Introduction](#background-and-introduction)
- [Features](#features)
- [Download and Get Started](#download-and-get-started)
- [Manual](#manual)
- [FAQs](#faqs)
- [Contact Us](#contact-us)
## Background and Introduction
Petri nets provide a formal and clear representation of systems based on their
firm mathematical foundation for the analysis of system properties. This software
provides fuzzy continuous Petri nets modeling and simulation functions
for researchers in the field of systems biology.
<br>
The purpose of this system is to provide users with services to complete
the simulation and fuzzy inference by constructing Petri nets. This software
includes three main functions: continuous Petri nets modeling, fuzzy modeling,
and hybrid simulation. Among them, the simulation is based on the transition
and fire of the Petri model input by the user, and the simulation results are
given.
<br>
In order to improve the user experience, we simplify the modeling page to
give users a more intuitive sense of use without affecting the function during the
design process. At the same time, the simulation and fuzzification are integrated
in the system, so that the users’ needs are satisfied as much as possible.
## Features
* Features for modeling
  * Concise and efficient interface design.
  * Drawing of the Petri net graph as usual.
  * Flexible user-defined functions.
  * Multiple fuzzy logic choices.
  * Simple and fast fuzzy logic settings.
  * Rich shortcut settings, such as undo, redo, save, print, etc.
* Features for simulation
  * Highly automated simulation process.
  * Diversified export of simulation results.
  * Custom simulation result drawing.
## Download and Get Started.
Please download the zip file [FCPN.zip](https://github.com/wjsunscut/fcpn/raw/master/FCPN.zip). Then unzip it and click the `FCPN.exe` to run the software.
<br>
Or you can choose to download [Setup.exe](https://github.com/wjsunscut/fcpn/raw/master/Setup.exe) and install it. Run `FCPN.exe` after installation.
## Manual
Manual can be found at [Manual.pdf](https://github.com/wjsunscut/fcpn/raw/master/Manual.pdf). The examples in the manual can be downloaded from [Examples](https://github.com/wjsunscut/fcpn/raw/master/Examples).
## FAQs
Q: How does a name in FCPN look like?
<br>
**A: At first all names have to be unique in a net. It can contain any of the following elements:
<br>
• letters a-z and A-Z
<br>
• numbers 0-9
<br>
• underscore _
<br>
The name has to start with a letter or underscore and followed by any combination of all elements above. Otherwise compiler errors might occur.**
<br>
**************************
Q: What does the function MassAction() mean?
<br>
**A: MassAction() is a macro that creates the rate function for a transition out of its preplaces and takes a parameter as argument.
<br>
For example, assume that t0 has two preplaces p0 and p1, and the parameter k is defined. Now you can specify the rate function of t0 to obey mass/action kinetics as k\*p0\*p1 or MassAction(k).
<br>
The results are same. MassAction() takes care of the structure. If you change the preplaces, the rate function is automatically adapted.**

## Contact us
FCPN is under active development. If you have any questions, please feel free to contact us.
<br>
**Email**: `wjsunscut@163.com`
<br>
**Address**: `University Town Campus of South China University of Technology, Guangzhou, Guangdong, China`
