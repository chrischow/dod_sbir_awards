
ConnextLogger: Intelligent Data Logging for MDA Modeling and Simulation Systems
===============================================================================

# Abstract


MDA M&S systems generate a significant amount of simulation data, but correspondingly incur significant use of computing resources to process it. To avoid system instability and the introduction of operational latencies within these systems, only a minimal set of log data can be collected.MDA requires an intelligent data logging solution for their modeling & simulation (M&S) systems that reduces runtime and resource usage (CPU, memory, network, and storage) and collects relevant data, rather than blindly logging data in a best-effort fashion.We propose developing an intelligent, adaptive data-logging platform that will adjust to match the dynamic situation and the analysts needs. Our platform will continually collect and asynchronously buffer high-fidelity data (by sampling at high rate) in circular in-memory caches. This ensures low latency and high throughput while minimizing the impact to the application. This data is captured before and after events of interest occur; it will be analyzed to detect anomalies and other events, triggering the logging into permanent-storage of the fine-grain data. The event detection will utilize conditions programmed by users, statistical anomaly-detection techniques, as well as machine learning algorithms (both supervised and unsupervised).Approved for Public Release | 17-MDA-9395(24 Oct 17)  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Missile Defense Agency|2018|$149,965|logging, simulation, objective simulation framework, metadata, software architecture, data distribution service, real time, root cause analysis|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/CC/#1139)