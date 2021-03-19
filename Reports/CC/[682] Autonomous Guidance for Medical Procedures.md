
Autonomous Guidance for Medical Procedures
==========================================

# Abstract


Problem: Mars missions will not have real-time communications with Mission Control Center (MCC), and correspondinglynbsp;limited access tonbsp;supervision for complex medical scenarios that lie outside the skill set of crew members. Thus we neednbsp;solutions that can provide just-in-time training, monitoring, and autonomous guidance of medical procedures, to make the crew independent of MCC.Solution: We propose a system for automatically building computational models of a complex physical task, such as a medical procedurenbsp;performed by humans, givennbsp;only a handful of recorded expert demonstrations of the task. Once such a model is built, ournbsp;system cannbsp;finely analyze the same task being performed in live video, to provide measurements and analytics, improve efficiency, guide a crew member through the task, or provide just-in-time training.We combine recent advances in machine learning and computer vision, including our own prior work, in human pose estimation, 3D object estimation, action classification, and long-term causal reasoning to build novelnbsp;systems that can understand goal-driven multi-step activities in live video feed.Existing commercial solutions: Somenbsp;AI platforms offer capabilities to estimate human skeletal poses,nbsp;locate objects, as well as classify simple actions in video.nbsp;However in order to understand a certainnbsp;multi-step activity (e.g. a medical procedure), a solution provider still needs a team of computer vision or IoT engineers, who write customized computer code to represent that specific activity, relating human pose changes with object movements over time, i.e. building this temporal causation structure on top of the capabilities provided by the existing AI platforms.nbsp;In contrast, our solution is able to learn complex activities that combine human-object and human-human interaction over time merely from example demonstrations of the activity. Our system does not require customization at the level of new programming to model a new activity and scenario.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2020|$124,588||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/CC/#682)