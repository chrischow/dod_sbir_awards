
Computationally Efficient Deep Learning-Powered EWS Radar Data Preprocessor (CELER)
===================================================================================

# Abstract


The inability of dismounted radar-based Electronic Warfare System (EWS) systems to process and analyze track data in realtime poses a potential barrier to increased effectiveness during some Marine Corps missions. The Computationally Efficient Deep Learning-Powered EWS Radar Data Preprocessor (CELER) is a system designed to process millions of EWS radar data points per second using Recurrent Neural Networks. Using Xilinx’s Zynq UltraScale+ SoC to process the data in realtime allows the system to be carried with backpack EWS systems like SNC’s Modi II, with the system measuring less than 12” x 6” x 4” and weighing less than 5 lbs., including the battery. Using an FPGA allows CELER to be efficient in terms of computing power per Watt, particularly over GPUs. The system will learn to model noise typically found in EWS radar data, filtering out noise and classifying signals of interest in the radar data. We will use a physics-based simulation of vehicles and EM clutter to provide realistic training data for our neural networks. CELER is ideal for battery powered systems, including small unmanned air and ground vehicles, where using the latest machine learning-based inference methods would provide more advanced capabilities, but those systems are power constrained.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2020|$139,956|tensorflow, keras, electronic warfare systems, ews, fpga, rnn, recurrent neural networks, gru|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/JH/#2037)