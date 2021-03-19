
An Interoperable HL7 FHIR-based Medical Device Data System (MDDS) For Accessing And Integrating Live Point-Of-Care Data From High-Acuity Bedside Patient Monitoring Equipment
=============================================================================================================================================================================

# Abstract


Abstract
The overall goal of this proposal is to combine expertise and approaches from biomedical engineering and critical
care medicine to design a universal system to acquire, record and transmit physiological signals from bedside
monitored patients. Patient monitors generate over a million datapoints of information per hour, however, only a
tiny fraction of those data are transmitted or recorded. In order to improve data exchange in healthcare, the Fast
Healthcare Interoperability Resources (FHIR) standard was published in 2014. However, it has yet to make a
significant impact on Medical Device Integration (MDI), which is the process of automating the flow of clinical
data from bedside medical devices, such as patient monitors, to external systems such as Electronic Medical
Records (EMR). Also, MDI is a complex task because data from these devices are high-frequency and high-
volume and because most devices use proprietary protocols and outdated interfaces such as serial cables.
Hospitals and researchers have therefore been left with few options except to use expensive and vendor-specific
MDI solutions to access these data or to use manual data entry into the patient EMR, which leads to data entry
errors, late entry of data, and lost time for clinical care. Manual data entry only captures a tiny fraction of the
available data, and with increased research interest in Artificial Intelligence (AI) and Machine Learning, there is
a growing need for a standardized way to access the vast amounts of data from bedside devices. This project
will develop a vendor-neutral software-based Medical Device Data System (MDDS) that acquires and records
data from bedside devices across a hospital network and makes live data available to 3rd party systems using
a FHIR application programming interface (API). The proposed proof-of-concept will consist of three elements:
[i] a transmitter which encrypts and transmits patient signals across the network, [ii] an aggregator which
receives, translates and records the signals to a central location, and [iii] a FHIR Server with API for allowing
external systems to access live data as FHIR resources. This proposal seeks to create a novel design that will
overcome a critical barrier in healthcare, medicine and research. The proposed MDDS will be valuable to
hospitals, clinicians, researchers and app developers because it makes data accessible which were previously
only available to clinicians at the bedside in real-time.Narrative
MediCollector’s proposed vendor-neutral medical device data system (MDDS) will be a valuable research tool
to access, acquire and record high-frequency bedside patient monitor data for facilitating clinical research in
hospitals. In addition, it will make live patient monitor data accessible to external systems through an HL7 FHIR
application programming interface (API), thereby improving interoperability in hospitals and opening the doors
to the integration of live data into external systems, such as smartphone apps and artificial intelligence
algorithms, which can improve clinical workflow and healthcare in general.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|National Institutes of Health|2020|$210,642||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JH/#2428)