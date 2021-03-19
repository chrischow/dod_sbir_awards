
Neural Net Control for Electric Propulsion in 3-Body Orbits
===========================================================

# Abstract


The proposed innovation, neural networks (NNs) for electric propulsion (EP) mdash; NNEP, leverages the fundamental principles of optimal control (OC) and a rich field of recent advancements in the area of artificial intelligence to automate spacecraft maneuver correction, resulting in improved spacecraft maneuver accuracy, lowered operations complexity, and cost savings. NNs are used as function approximators, learning the complex relationship between spacecraft state and the costates defining the OC to return to a reference trajectory.nbsp;The NNEP technology builds on the variety of technologies that exist for onboard navigation (such as GPS, CAPS, or OpNav). Once the spacecraft has generated a state estimate, it evaluates a pre-trained NN to find the corresponding costates (non-physical terms created in the process of solving an OC problem). The NNEP technology maps state errors to costates because the costates are always smoothly-varying, even for non-smooth OC. Within seconds of the nav update, the spacecraft autonomously determines the control required for the next several days and checks for constraint violations.The NNEP technology consists of both a novel application of NNs to relevant astrodynamics problems and an architecture for implementing this technology in real operational environments and in flight software (FSW). A proof of concept of the technology was developed during Phase I, including demonstration of the building blocks for a FSWnbsp;implementation. Phase II funding will mature the technology further and result in a prototype FSW implementation running on representative space hardware.nbsp;Many research groups are now investigating the use of NNs to automate spacecraft trajectory corrections. NNEP combines Advanced Spacersquo;s practical institutional experience of mission design, navigation, and operations for a wide variety of cutting-edge space missions with the powerful theoretical advantages of NNs and OC.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2020|$749,237||
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JT/#523)