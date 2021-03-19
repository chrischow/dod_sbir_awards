
TIS: Trusted Sensor Integration
===============================

# Abstract


Condition-based maintenance plus (CBM+), and cyber-physical systems (CPS) in general, depend on correct sensor data for analysis, decision making and control loops. If the sensor data that arrives at the point of processing is not correct, or more accurate, is outside its accepted error range, then any further processing will be incorrect as well. This could result in, in the case of CBM+, not detecting indicators of failing, e.g. of vibrations or noise. It could also be an incorrect input to a control loop, leading to destruction of a system. The challenge includes correctness of measurement, but also the integrity of communication between sensor and e.g. a Programmable Logic Controller (PLC) or another processing system. In our previous work in cyber-physical systems, e.g. in Supervisory Control and Data Acquisition (SCADA) or Industrial Control Systems (ICS), we have already identified the correctness of sensor data, in security terms their integrity, as major issue, and started work to detect spoof and faked sensor data at the processing device. We propose to build both analytical/statistical and Machine Learning (ML) based models of the static and dynamic behavior of individual sensors and systems. We propose for example to model the dynamic response of a sensor, because the input signal is transformed to the output signal with a specific noise, delay and hysteresis. In other words, we use the imperfections of the sensor in translating the physical input to a numeric output to derive a fingerprint. Unfortunately, we have seen in our previous work that this is not enough. A single sensor always has to be considered in the context of the system as a whole, under non-stable environmental influence. First of all, looking only at the sensor characteristics is not sufficient to decide whether the measurement itself is sound from a physical point of view. In addition, there is a difference between a laboratory environment for sensor fingerprinting and an operational environment, e.g. in temperature and vibrations spectrum. Therefore, we need to model the system as a whole. For modeling both individual sensors and sensors in a system, we propose to use analytical approaches like Matlab/Simulink or OpenModelica, and, complementary, Machine Learning (ML), incl. Recurrent Neural Networks (RNN). We expect that ML will be especially useful for sensor fingerprinting and system models detecting deviations in sensor signals, while analytical models will better allow to analyze the connection of a sensor and an engine. For practical model building in Phase I, we propose to stimulate a simple cyber-physical system, e.g. an engine, to measure the sensor output, and to feed both stimulation signals and sensor outputs into an RNN. The realistic training here depends on the realistic stimulation. We especially expect that it will not be possible to build a complete repository of failures, instead, we will define a failure as a deviation from expected behavior.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2020|$140,000|model simulation, modeling, openmodelica, matlab/simulink, cyber-physical systems, machine learning, integrity of sensor data, recurrent neural networks|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JH/#2221)