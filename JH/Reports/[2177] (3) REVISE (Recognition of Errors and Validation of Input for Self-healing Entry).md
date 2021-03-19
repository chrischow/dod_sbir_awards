
(3) REVISE (Recognition of Errors and Validation of Input for Self-healing Entry)
=================================================================================

# Abstract


The promise of big data analytics cannot be fully realized without effective data healing processes. Data healing has traditionally been a process that requires human intervention and some level of domain specific knowledge to correlate, combine, and deconflict data.  In order to meet the requirement to support Naval Depot Modernization and Sustainment, we propose to leverage CHI Systems’ own existing AI technologies to develop an advanced, automated system based on understanding usage context to correct errors and heal data – the REVISE (Recognition of Errors and Validation of Input for Self-healing Entry) system.  Context is central to individual human cognition in many functions, including decision-making, sense-making, and planning. Under the sponsorship of ONR and NASA, CHI previously developed the Integrated Context Engine (ICE) as a computational means to define and represent an executable model of context. ICE provides a core data fusion capability through an AI-inspired, hierarchically organized ‘whiteboard’ knowledge structure. This whiteboard consists of several levels of information which are successively merged/abstracted into higher levels by multiple self-activated reasoning elements. ICE builds and maintains the context representation and applies reasoning to regulate the flow of data between whiteboard levels and coordinates the application of processes (e.g., Neural Networks (NN), Natural Language Processing (NLP), and custom software methods) to build additional context or perform on-the-fly data fusion tasks.  ICE technology has been demonstrated to be TRL 4.  Most recently, in the US Army’s Fusion Analytics program (2019), ICE was demonstrated for ingestion, transformation, deconfliction, and reasoning on asymmetric warfare data.  ICE has also been demonstrated for human-robot coordination in the context of simulated tasks for the International Space Station.  ICE will be the central repository of reasoning data within the REVISE system and has several whiteboard levels.  These levels begin with raw data as text, html, or xml representing background information such as system documentation, manuals, procedures, and reports. Raw data is processed via machine learning to derive a model that represents the patterns of usage within this dataset and is stored on the second level of the whiteboard.  This learned model of data usage patterns can then be utilized by an error correction module to process and automatically heal new data ingested by the system.  Healed data will be promoted to the third level of the whiteboard where it can be accessed by external systems or serve as the data basis for internal reasoning regarding trends or root cause analyses, to be stored on the fourth level.  Phase I will produce a prototype that can ingest data describing a domain to generate a usage model that can demonstrate data healing.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2020|$199,720|machine learning, artificial intelligence, natural language processing, data healing, data fusion, maintenance data analysis, context model|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/JH/#2177)