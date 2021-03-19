
Keymaker: Network Measurement and Congestion Analysis
=====================================================

# Abstract


Network operators, both within and without the Federal Government, gather a large amount of data about their networks using sophisticated collection tools. In particular, the Department of Energy operates many heavily-trafficked networks, and has done an excellent job implementing processes and developing applications which collect significant amounts of network measurement data.Unfortunately, data analysis often lags; most collected data sits unused, unable to help network operators improve quality of service or glean insight about network performance. When some of this data is excavated and inspected, typically during a network incident postmortem, analysis is laborious and often done by hand. Current network tools exclusively use static signature-based algorithms to inspect this type of network data; the current proposal uses dynamic signatures arising from the data itself to make sense of complex network interactions. The current lack of sophisticated automated data processing devalues the existing data collection infrastructure in both governmental and commercial realms and fails to extract insight from or otherwise take advantage of immense quantities of assiduously harvested network measurement data. The proposed effort builds on Phase I efforts to create software for the detection of congestion conditions/anomalies in data streams collected from network measurements in the form of time-series data. The software will be configurable to alert for smaller or larger congestion conditions as some network operators might only want to be notified for major events, while others may want to receive numerous notifications daily. Clostra is using machine learning techniques to identify the sometimes subtle differences between typical network behavior and abnormal/anomalous conditions. In Phase I Clostra proved the ability of their machine learning-based network anomaly detection system, and was able to identify all anomalies in the test dataset. Clostra used perfSONAR data for training, testing, and refining their machine learning algorithm, producing a system that alerted users when anomalies were identified. In Phase II Clostra will extend the perfSONAR data types used for testing, include other network measurement data, explore arbitrary time-series data, and product a refined analytic dashboard, tied to the anomaly detection algorithm, for monitoring and alerts. Commercial Applications and Other Benefits: The commercial application Clostra is developing, Keymaker, uses Phase I’s machine learning algorithms to monitor and classify a wide variety of network conditions. It also learns using historical, previously gathered network data (which is plentiful), to construct a dynamic baseline defining “normal” for a given network, allowing “abnormal” to be more easily spotted.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2019|$1,499,994||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/CC/#770)