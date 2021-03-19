
High Performance FPGA-based Embedded System for Decision Making in Scientific Environments
==========================================================================================

# Abstract


Recently, the Field-Programmable Gate Arrays (FPGA) System on Chip (SoC) gains overwhelming attention in edge computing and serves as a popular solution for Internet of Things and autonomous systems because of its advantages in high performance, low power, reusability, and reliability. However, the application of FPGA to the scientific environment that involves advanced data analysis and machine learning is exceptionally challenging because the hardware design skills are required to fill in the gap where FPGA design demands the register transfer level description while the mainstream programmers are only proficient in high-level programming languages. In this proposal, Sunrise Technology Inc. collaborates with Brookhaven National Laboratory and Los Alamos National Laboratory to bridge the gap and design an intelligent FPGA-based embedded control system for two scientific environments. Based on our successful effort of integrating deep convolutional neural network into an Altera FPGA SoC for recognizing images in real-time, we will extend this prototype with multiple deep learning network architectures to science domains. To bridge the gap between FPGA hardware and high-level software, we will introduce OpenCL, a High-Level Synthesis (HLS), to perform three main functions in software and hardware integration: scheduling, allocation, and binding. We will build our deep learning software on top of Intel Altera OpenCL SDK because it exposes the FPGA CAD features for advanced customization. In particular, we will fine-tune the scheduling of submodules and rearrange the execution order of computing tasks for better parallelism and data granularity and locality. We also trade off resources between different layers of neural networks and allocation of on-chip memory or off-chip storage for tensors in neural networks. The user-supplied hints will guide the HLS compiler to improve its three core functions. During the Phase I, we will provide two domain science cases with a cost- effective “intelligent-software-on-silicon” solution that remains fabless and inexpensive to meet the tight real-time requirements. All these system-level decisions and trade-off reply on an accurate understanding of domain sciences. The first application is to apply machine learning and decision making techniques in NSLS-II control systems that integrate real-time data from the subsystems (power supply, diagnosis, and RF systems) for beam optimization and therefore better reliability and stability, which are the two main DOE targets for all light source facilities. FPGA has been used as the primary control platform in NSLS-II, and our proposed efforts will ensure the optimization and decision in real-time on FPGA. The second application is to improve the trigger design for RHIC high energy nuclear physics sPHENIX experiment. The Monolithic- Active-Pixel-Sensor based silicon vertex detector system designed by Los Alamos National Laboratory for the sPHENIX experiment at RHIC is a 3D tracking device to generate a stack of 3D hit images. Our existing embedded deep neural network system provides a matching solution to recognize which stack of images have the sought patterns. We will build an FPGA-based Edge Computing trigger system to process the 3D images captured in real-time and make rapid decision on whether to record the events. Our proposed FPGA SoC has the flexibility and performance advantages and earn its commercial potentials in a range of autonomic applications including machine vision for recognizing defects in high speed (conveyor belt or fly-over), industrial and vehicle autonomy to reduce costs and time to market, and personalized healthcares for patient monitoring and supports.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2019|$225,000||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards#763)