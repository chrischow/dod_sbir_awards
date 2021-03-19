
Synthetic Training Data for Explosive Detection Machine Learning Algorithms
===========================================================================

# Abstract


Deep learning offers a powerful and extensible toolset to achieve or exceed human-level accuracy for automatic object detection in stream of commerce data. However, in order to train deep machine learning-models for 2D and 3D screening a significant quantity of high-quality ground-truth training data is required.We propose SoCPhysics: A Stream-of-Commerce Physics-Based Data Generation Application, which leverages an implementation stragegy widely used in high performance computing environments for this purpose. We will generate lightweight Python wrappers around existing X-Ray/MMW simulation codes that may be written in C/C++/Fortran, and allow them to be called as Python modules. This allows the codes to retain the performance of native code, while allowing them to interact with other Python libraries and data structures (e.g. MakeHuman, Blender, BulletPhysics, etc.). This also allows us to deliver the code in formats that are useful across the model development cycle, and to different users who may have variable needs we make the code accessible via: 1) integration/extension of Blender's GUI through a custom input panel, 2) via a scriptable command-line interface, and 3) as an importable Python module which can be used to generate training data on-the-fly during model development, training, validation and testing (essential!). Critically, our proposed integration plan allows us to achieve this with no duplication of core code or libraries, meaning the code is easier to develop, test, verify and validate, and will result in fewer bugs and lower maintenance costs for the lifecycle of the SoCPhysics product.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
||2019|$149,938|synthetic data generation, x-ray simulation, millimeter wave simulation, stream of commerce, passenger screening, deep learning, baggage screening, modeling and simulation, explosive detection, object detection|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/DJ/#1798)