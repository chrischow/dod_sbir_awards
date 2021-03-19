
9-1-1 Network Modeling Based Upon PARIDINE NIDE Model
=====================================================

# Abstract


SecureLogix is a current performer on the PARIDINE project and is focused on defining and detecting NIDEs such as Telephony Denial of Service (TDoS) and other call pattern-based attacks against 9-1-1 networks. Our approach is to enhance our cloud-based Call Authentication Service (CAS), extending its inherent authentication and spoofing detection capabilities, with the ability to use machine learning to detect NIDEs. CAS has a well-defined API and can be used outside of our PolicyGuru solution. We propose to build a 9-1-1 simulator around CAS, which lets us leverage its very high fidelity TDoS/NIDE detection capabilities. The simulator will share concepts such as sites, with their accompanying attributes, and data models, which are based on the data stored in CAS for real 9-1-1 sites. The data model is used by the simulator to generate realistic normal traffic for sites. The simulator shares this information with CAS and then generates both normal call traffic, in addition to what-if traffic for various types of TDoS/NIDEs. This includes making actual queries to CAS and retrieving the results. The simulator will then simulate various mitigation strategies, to include terminating calls, rerouting calls in an ESInet, and adjusting queues and priorities. This will allow 9-1-1 managers to simulate various types of TDoS/NIDEs and determine which mitigation strategies work best for different levels of attacks. Finally, the West/ECaTS dashboard will be used, with its playback capability to visualize the simulation.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2019|$147,677|9-1-1, ng9-1-1, paridine, tdos, telephony denial of service|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/DJ/#1801)