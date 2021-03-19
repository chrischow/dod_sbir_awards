
Early Prediction and Prevention of Frac Screen-out using Deep Reinforcement Learning
====================================================================================

# Abstract


Screen-out is a costly problem in hydraulic fracturing operations for stimulation of conventional and unconventional reservoirs that could potentially lead to massive downtime and increased capital spending on a well. It can happen due to either operational reasons, such as equipment malfunction, or issues related to the formation. We believe that screen-out can be potentially diagnosed ahead of time with the help of advanced Machine Learning ML). Being proactive in identifying screen-out using ML can significantly save on the cost of operations, depending on the size of completions and activity level. Considering the extent of hydraulic fracturing operations in the United States in conventional and unconventional resources and numerous occurrences of frac screen-out events, the benefits of having access to an intelligent system that alerts screen-out risk on a real-time basis is remarkable. The objective of the proposed study is to design a machine learning ML) model to predict screen-out events before their occurrence. This will be carried out by analyzing the hidden dynamics of control and feedback signals such as bottom-hole net pressure, surface treating rate, bottom-hole proppant concentration among others. While classical approaches such as 1-nearest neighbor classifier equipped with dynamic time warping distance measure generally perform well for time series classification problems, in the case of ‘Early’ detection tasks, they fall short. Although they can reliably label the screen-out events after happening, it is hard to label the early sequences leading to scree-out in future. We propose to tackle this problem using a deep Reinforcement Learning RL) framework. In this view, the controllable parameters such as surface pressure can be considered the actions made by the RL agent and, the environment’s feedbacks in the RL setting consist of all the readings from bottom-hole pressure sensors among other viable signals. In this novel framework, each operation’s data is an episode used for training of the RL, and we assign rewards only for the states labeled as screen-out events. The discount factor in this RL setting controls the earliness factor of the detection. Ultimately, by learning the value function in the RL setting, the probability of screen- out events in the future can be estimated. The Phase I outcome will be a fully trained RL model based on data from several shale basins in the United States. This novel methodology provides great opportunities for improved hydraulic fracturing diagnostic for unconventional wells. The results of the Phase I research can be used in Phase II to design a fully autonomous system operating without an expert operator to prevent screen-out events. A code will be developed in conjunction with a Real Time Operation Center RTOC) to enable real-time prediction of screen-out. The development and automation of the proposed framework has the potential to change the future of hydraulic fracturing by reducing the risks and lowering the costs. It could eventually lead to reduced overhead on site and managing all operations on a real-time basis without having to rely on personnel on site.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2020|$199,914||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#814)