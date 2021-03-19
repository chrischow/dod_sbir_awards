
Inertial Navigation System Inspection and Detection of Evolving Roles (INSIDER)
===============================================================================

# Abstract


Inertial Navigation System Inspection and Detection of Evolving Roles (INSIDER) is an automated inertial navigation system (INS) performance normalcy monitor and fault detector and predictor. INSIDER reasons over raw INS sensor readings (directional and rotational accelerations, velocities, positions; and alerts) to (i) learn individual sensor normalcy patterns, (ii) understand complex correlations among INS sensor outputs, and (iii) detect and predict sensor faults. INSIDER fuses two unsupervised machine learning methods: (1) A graph-based approach that converts performance alert time series (generated from the raw sensor outputs using signal processing tools) into time-varying graphs of performance characteristics (nodes) connected by co-occurrences among characteristics (weighted edges); normal correlations among the performance characteristics time series are learned as the topology of a large graph, and deviations from this normal topology are classified as anomalies. (2) A Bayesian forecasting approach that reasons over the evolution of the graph properties, as well as raw and processed outputs of individual sensors, to learn normalcy over a moving time window and predict near-future signal values; deviations from the prediction are classified as abnormal trends or anomalies potentially arising from system faults. INSIDER monitors the performance of the INS unit by reasoning over the entire normalcy graph and entire alert graphs, but it can also monitor INS subsystems by focusing on corresponding subgraphs. Finally, INSIDER can predict faults or abnormal trends by observing degradations in system-wide normalcy as well as in the normalcy of individual sensors and subsystems. By the end of Phase I, INSIDER will detect performance anomalies in high-fidelity, simulated INS data (with corresponding reference data) at the sensor, subsystem, and system-wide levels, and demonstrate a capability to detect degradation as a predictor of sensor faults.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2020|$139,982|graph-based approach, normalcy monitoring, sensor fault detection, inertial navigation system, signal processing, anomaly detection, bayesian forecasting, machine learning|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JH/#2172)