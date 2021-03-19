
Rapid Autonomous Data Ingest Algorithms (RADIA)
===============================================

# Abstract


PUNCH proposes a streaming data processing pipeline capable of ingesting heterogeneous data from multiple data providers in a timely, efficient, and accurate manner. The proposed solution will integrate machine learning algorithms to support automated load-based resource allocation, data classification, and automated updates to schemas as changes occur. PUNCHs solution will be highly available and persist data using a fault-tolerant and high-performance storage layer designed to handle streaming data inputs. This will be accomplished via three primary technical objectives: 1) formalize a flexible hierarchical ontology for classifying incoming data; 2) prototype an ETL pipeline that reliably processes, transports, and stores data streams, while tracking provenance; and 3) automatically infer input schemas and intelligently assign labels to incoming data. The hierarchical ontology of Objective 1 will provide the structure and initial content of the schema registry embedded within the ETL pipeline described in Objective 2. Additionally, the decision tree structure of this ontology will allow for easily interpretable labelling decisions made by the random forest classifier described in Objective 3, as at each node of the graph, the model determines which path should be followed to maximize classification accuracy. The classification model in Objective 3 outputs classification labels to incoming data streams.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2018|$124,835|graph, dynamic resource allocation, stream processing, supervised learning models, complex event processing, etl, hbase, machine learning|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/JH/#1957)